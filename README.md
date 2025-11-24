In order to run the application first we need to create the db

> docker compose up -d

Then run the project like normal

The application can be interacted with via REST on the /services (GET) and /deploy (POST)

there is a swagger frontend available on http://localhost:8080/swagger-ui/index.html thanks to the springdoc package. here all endpoints can be tested
