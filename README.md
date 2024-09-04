# My Cloud Service

#### Additional setup required to run the application:
1. Add your oracleDB credentials to the `DatabaseConnectionHandler.java` and `application.properties` files.
2. Setup SSH tunneling into the UBC CS department undergrad servers.
3. Navigate to the backend directory and run `./gradlew clean build`
4. Open the `ServicesApplication.java` file and run it
5. Navigate to the frontend directory and run `npm install` and `npm run dev`
6. Open `http://localhost:3000` in your browser

## Project Summary
The project models a cloud service provider, offering customers the ability to create and manage projects. Users can utilize various services, create and manage instances, configure security settings for them and also compute the total costs associated with their cloud service usage.

## Frontend Views
- [Login Page](./docs/frontend_views/LoginPage.png)
- [Sign Up Page](./docs/frontend_views/SignUpPage.png)
- [Sign Up Billing Page](./docs/frontend_views/SignUpBillingPage.png)
- [Project Page Empty](./docs/frontend_views/ProjectPageEmpty.png)
- [Project Page Populated](./docs/frontend_views/ProjectPagePopulated.png)
- [Create Project](./docs/frontend_views/CreateProject.png)
- [Create Instance](./docs/frontend_views/CreateInstance.png)
- [Billing Detail Page](./docs/frontend_views/BillingDetailPage.png)