# BobApp

Clone project:

> git clone XXXXX

## Front-end

Go inside folder the front folder:

> cd front

Install dependencies:

> npm install

Launch Front-end:

> npm run start

### Docker Frontend Container

Build the frontend container:

> docker build -t bobapp-front .

Start the frontend container:

> docker run -p 4200:80 --name bobapp-front -d bobapp-front

## Back-end

Go inside folder the back folder:

> cd back

Install dependencies:

> mvn clean install

Launch Back-end:

> mvn spring-boot:run

Launch the tests:

> mvn clean install

### Backend Docker Container

Build the backend container:

> docker build -t bobapp-back .

Start the backend container:

> docker run -p 8080:8080 --name bobapp-back -d bobapp-back

---

### Docker Compose : Starting both container at the same time

you can start both container a the same type executing the "docker-compose up" command from the root folder
