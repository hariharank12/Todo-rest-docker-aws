# To Deploy Spring Boot Applications to AWS Elastic Beanstalk

## Standard Microservice Design Conventions following DDD and 12 factor methodology. To run,
   * mvn clean package.
   * docker run --name todos-api --publish 5000:5000 --link mysql:mysql hariharank12/todo-rest-api-mysql:1.0.0.RELEASE.