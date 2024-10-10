# Simple Rest Service Application using Java Spring Boot



## How to Run the Application
Click on the `Run` button in the IDE in the top right corner of SimpleRestServiceApplication.java file to run the application.
![how to run](screenshots/run.png)


By default, the application will start on port `8080`.

## How to Test the API

Once the application is running, you can use Postman or cURL to make GET requests to the following endpoint:

- **Without query parameter:**
  ```
  http://localhost:8080/greeting
  ```

- **With query parameter (`name`):**
  ```
  http://localhost:8080/greeting?name=YourName
  ```

This will return a greeting message from the application.

## Screenshots
### With no query parameter

![with no query parameter](screenshots/greeting.png)

### With query parameter Alex

![with query parameter Alex](screenshots/alex.png)

### With query parameter Gaurav

![with query parameter Gaurav](screenshots/gaurav.png)
