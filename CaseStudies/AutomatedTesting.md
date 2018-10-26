# Selenium automated testing
## Code : 
```javascript

var webdriver = require('selenium-webdriver'),
    By = webdriver.By,
    until = webdriver.until;

var driver = new webdriver.Builder()
    .forBrowser('chrome')
    .build();

driver.get('https://store.steampowered.com/');

driver.findElement(By.name('term')).sendKeys('morrowind');

driver.sleep(9000).then(function() {
  driver.findElement(By.name('term')).sendKeys(webdriver.Key.ENTER);
});

driver.sleep(22000).then(function() {
  driver.getCurrentUrl().then(function(url) {
    if(url == 'https://store.steampowered.com/search/?term=morrowind') {
      console.log('Test passed');
    } else {
      console.log('Test failed');
    }
    driver.quit();
  });
});
```


## Results
C:\Users\Ushank Shabak\Desktop\SeleniumTest>node steamtest

DevTools listening on ws://127.0.0.1:62616/devtools/browser/0bc60678-8a4e-4b97-8ae4-32252994bc43
Test passed

C:\Users\Ushank Shabak\Desktop\SeleniumTest>
