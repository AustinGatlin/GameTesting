# Heroku:  uses in testing environments
## The Developer Environment
One technology that Heroku offers that is useful in this environment is Heroku CI. Heroku CI runs automatic tests on all code that
it recieves, helping developers run their unit tests in this environment. Pipelines is another useful functionality
with Heroku that is beneficial for all environments. Pipelines allows developers to manage multiple environments at once, 
allowing developers to easily have a development, QA, Staging and Production environments.

## The QA Environment
A great tool that Heroku has for the QA environment is Review Apps. Once a pull-request has been made, Heroku can automatically make a 
webiste with a unique URL that hosts a version of the app with the requested changes, allowing QA testers to easily test and review changes
before they are implimented. 

## The Staging/Pilot Environment 
Heroku also allows you to have a staging environment on their platform. This is useful for many things, one of which would be stress testing.
With the Heroku staging environment, you can stress test to find out what their server's capacity is so that you know how many servers you need
and also test a program's network functionality. 

## Production Environment 
Another tool that Heroku has that's useful for the production phase is their Release tool. With this tool, developers can easily push changes
from the staging environment directly to their production environment.

## How I would use it
