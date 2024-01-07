Hello,

- This is a CI/CD project to practice some of the DevOps approaches.
- It's a Java application has some data about cars (model, price, age, color and etc...).
- Our pipeline contains of CI (Continous Integration) and CD (Continous Deployment)
- The CI stages are :
    - Building the Code using Gradle
    - Testing: Smoke Testing
    - Testing: Static Analysis using PMD
    - Testing: Unit Testing 
- The CD stage :
    - Moving the .jar file to S3 bucket on AWS
    - Deploying the Application on AWS ElasticBeanstalk.

Attached:
- The Java application.
- The pipeline file written and applied on gitlab-ci.

Regards