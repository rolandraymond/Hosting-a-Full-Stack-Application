# Hosting-a-Full-Stack-Application

Deployment a Full-sack-Application

---

In this project I learn how to take a newly developed Full-Stack application built for a retailer and deploy it to a cloud service provider so that it is available to customers. I used the aws console to start and configure the services the application needs such as a database to store product information and a web server allowing the site to be discovered by potential customers , modify my package.json scripts and replace hard coded secrets with environment variables in my code.

then I used CircleCi and connect my Github account to it. Based on the manual steps used to deploy the app, write a config.yml file that will make the process reproducible in CircleCi. when I use git to push set up the process to be executed automatically based when code is pushed on the main Github branch.

The project will also include writing documentation and runbooks covering the operations of the deployment process. Those runbooks will serve as a way to communicate with future developers and anybody involved in diagnosing outages of the Full-Stack application.

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

## links

> RDS : database-1.ctkkngwdbiad.us-east-1.rds.amazonaws.com

> Elastic Beanstalk: http://udagram-api-dev.eba-w55dp8fa.us-east-1.elasticbeanstalk.com

> Bucket : http://rowland-udagram.s3-website-us-east-1.amazonaws.com

1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.
