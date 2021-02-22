# server-deployment-practice
lab01

Heroku Deployment: 
  Dev: https://taylor-server-deploy-dev.herokuapp.com/
  Production: https://taylor-server-deploy-prod.herokuapp.com/

Github Actions: https://github.com/thornrae/server-deployment-practice/actions 

Pull Requests:
https://github.com/thornrae/server-deployment-practice/pulls?q=is%3Apr+is%3Aclosed 


To get this app deployed thru Heroku, I had to go in and add a "start" property with value "node index.js" to the scripts object in the package.json file.

I also have to move the index.js file outside of the server folder to get the server to run locally using nodemon. 


