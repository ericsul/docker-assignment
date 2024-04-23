# docker-challenge-template
1. Setting Up the Environment First, I created a new folder named challenge3 to organize my work. Then, I added all the files provided in the challenge3.zip to the root folder of my challenge.

2. Configuration with Environment Variables To configure the services properly, I created a .env file in the root folder and added the necessary environmental variables according to the instructions. These variables include details like database root password, database name, username, password, and host for both the application and the database.

3. Writing the Docker Compose File Next, I created a docker-compose.yml file in the root folder to define the services: nginx, node-service, and db. In this file, I specified the Docker images for each service and configured them to use the environmental variables defined in the .env file.

4. Verifying Services I made sure all services were running properly by executing the command docker-compose up in the terminal. Then, I opened my browser and navigated to http://localhost:8080/api/books and http://localhost:8080/api/books/1 to check if the application was serving the expected JSON messages. If there were any issues, I went back to fix them based on the error messages or unexpected results.

5. Committing Changes and Pushing to Repository Once everything was working as expected, I committed all the files including the .env file, the docker-compose.yml file, and any other changes I made, and pushed them to the remote repository.

6. Submission Finally, I submitted the repository's URL in D2L and documented all the steps I followed to achieve the results.

Expected Outcomes Upon successfully completing the challenge, the application should respond correctly to requests made to http://localhost:8080/api/books and http://localhost:8080/api/books/1, providing JSON messages with all books and a single book respectively. Additionally, running the command docker-compose ps should display information about all running services, including their names, images, commands, status, and exposed ports.
