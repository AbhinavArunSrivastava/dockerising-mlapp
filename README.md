# dockerising-mlapp


**LINK** - https://docker-mlprediction-test.herokuapp.com/

**Introduction**:
In this project, I have used dockerised container to deploy my Machine Learning app on heroku.
(for more information on the machine learning methods, you can follow this link: https://github.com/AbhinavArunSrivastava/predictiveModelDeploy.
I have used my previous built ML app to build a docker container)

In addition to ML app, we have two more files here 
1. Dockerfile: A Dockerfile is a text document that contains all the commands a user could call on the command line to assemble an image. 
               Using docker build users can create an automated build that executes several command-line instructions in succession. 
            
2. main.yaml - It is used to configure our application's services. Inside of it, you will find HEROKU_EMAIL, HEROKU_APP_NAME, HEROKU_API_KEY mentioned.
               To set these three attributes, we go to the settings option of the current repository --> click on Secrets on the left-->
               Select Actions --> Click on NEW REPOSITORY SECRET and add each of the three attributes one by one.
               (Note: We can fetch our heroku api key from account settings options of our heroku account)
               
               
*THANK YOU!*
