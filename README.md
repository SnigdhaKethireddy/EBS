# EBS

creating workflow from git actions and deploying a node js application on elastic bean stalk using docker

create an environemnt - web server and given the application name
we use platform as docker
the zip folder i.e; node js application is uploaded in it
then all the vpc, subnets etc which are necessary are bulit up and we can see the env running
the 2 jobs I have used to deploy the node app are
create an elastic beanstalk version which creates a new version for elastic beanstalk’s application and stores it in a custom S3 bucket.
deploy to elastic beanstalk environment which deploys new version to the environment we created.
I created secret respositories to store access and secret keys
Now files can be pushed and actions are implemented on them and will will be successful if the workflow is green , says that the application is deployed on the elastic bean stalk and stored in s3 bucket.
When we click the link the webserver hello master should be up and running

