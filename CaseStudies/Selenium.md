# Selenium automated test

## Code: 

var webdriver = require('selenium-webdriver'),
    By = webdriver.By,
    until = webdriver.until;

var driver = new webdriver.Builder()
    .forBrowser('chrome')
    .build();

driver.get('https://www.armorgames.com');


driver.sleep(3300).then(function() {
  driver.getTitle().then(function(title) {
    if(title === 'Play Free Games Online at Armor Games') {
      console.log('The test was successful');
    } else {
      console.log('The test was unsuccessful');
    }
    driver.quit();
  });
});

## Results: 

C:\Users\Ushank Shabak\Desktop\SeleniumTest>node armorgamestest

DevTools listening on ws://127.0.0.1:50596/devtools/browser/4a29e086-3027-45d3-8938-c5626dec1e24
The test was successful
