# LAB - Class 16

## Project: AWS: Cloud Servers

### Author: Timothee Odushina

### Problem Domain  

Deploy a simple Node.js server to EC2, using Elastic Beanstalk

* Choose a server you’ve built previously
  * Option 1: A simple API or Web Server
  * Option 2: A socket.io event Hub
  * The server should not require a database
  * Check in your server to GitHub


Task 1:

* Create a new environment, using Elastic Beanstalk from the AWS Control Panel (GUI)
* Manually deploy your application to this environment by uploading a .zip file

Task 2:

* Using the same server, create a new environment using Elastic Beanstalk from your terminal
* Manually deploy your application to this environment by using eb deploy

### Links and Resources

- [Elastic Beanstalk from the AWS Control Panel GUI](http://lab16cloudserver-env.eba-jhcyx6jq.us-east-2.elasticbeanstalk.com/)
- [Elastic Beanstalk CLI](http://basic-express-server-cli-dev.us-west-2.elasticbeanstalk.com/)
- [GitHub link](https://github.com/timothee2022/cloud-server.git)

### Setup

#### `.env` requirements

PORT=3002

DATABASE_URL=postgres://localhost:5432/api-app

#### How to initialize/run your application (where applicable)

- [Elastic Beanstalk from the AWS Control Panel GUI](http://lab16cloudserver-env.eba-jhcyx6jq.us-east-2.elasticbeanstalk.com/)
- [Elastic Beanstalk CLI](http://basic-express-server-cli-dev.us-west-2.elasticbeanstalk.com/)

#### Features / Routes

- GET : `/bad` - specific route to hit
- GET : `/` - specific route to hit

