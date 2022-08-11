# E-COMMERCE
eCommerce application based on the microservices architecture built using Spring Boot and ReactJS.

**TOOLS USED**

- **ReactJS:** Front-end Javascript framework.
- **Spring Boot 2.0:** Back-end JAVA framework to build microservices using Spring Rest Controller and Spring JPA.
- **MySQL:** Stores product and user information.
- **Cloudinary:** CDN server for storing product images. 
- **Google OAuth:** 3rd Party authentication service for quick login by retrieving user profile information. 
- **Stripe:** Payment service API to handle user payment requests.
- **Heroku Cloud Platform:** Deploying microservices on Heroku.
- **Docker-Compose:** Easy way to bring up the application using containerization and behaves similarly in the production environment.
 
**MICROSERVICES**

- **Authentication Service:** Creates user account and handles username/password authentication.
- **Payment Service:** Handles payment requests from the client and makes a subsequent request to Stripe API for money deduction. 

**Execution in local system**

- **Git clone this repository (Link)[https://github.com/RohanWork/E-Commerce.git]
- **Open command prompt in yout cloned repository
- **Type start-all.sh command in command prompt
- **Bingo
