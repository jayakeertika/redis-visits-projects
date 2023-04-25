# redis-visits-projects

#Docker compose with multiple containers

#Scenario
A docker container that contains a web application that simply displays inside the browser the number of times that someone visited the server.
webserver:To respond HTTP requests and generate some HTML to show inside of the brower
Database: Redis in memory datastore to log the number of times someone visited the page.

#package.json: will hold all the dependencies
#index,js: will hold all the apploication code
DockerFile: Setting up all the steps to be executed one after the other in a sequential manner.
