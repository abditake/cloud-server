LAB 16 - AWS Cloud Server 
========

- Deploy a simple Node.js server to EC2, using Elastic Beanstalk

      - Choose a server you’ve built previously
        - Option 1: A simple API or Web Server
          Option 2: A socket.io event Hub
    - The server should not require a database
    - Check in your server to GitHub
---------------

### Author: Abdinasir Yussuf

### Links and Resources


- **Just displays Route message**

  - [Simple-express-server](http://simple-express-server.eba-p3xtxutf.us-west-2.elasticbeanstalk.com/)


- **Utilizes the signin and singup route to authenticate the user and authorize**
  - [AWS deployed Basic-Auth-server](http://basic-auth-cloud.eba-w8xxtchn.us-west-2.elasticbeanstalk.com/) 




#### `.env` requirements

-   none, just bearer and basic tokens

#### Running the app

-   `npm start`
-   Endpoint:   
              `/Signup`
              `/Signin`

    -   Returns Object

        ```
        {
          "username": "tester",
          "password": "$2b$05$N5J/F6339f9wKNsyWGeKQOrGFTaeLjp1yg93D8PKNDXoDpt5KkV5m",
          "updatedAt": "2022-06-21T21:23:46.610Z",
          "createdAt": "2022-06-21T21:23:46.610Z"
        }

        ```

#### Tests

-   Unit Tests: `npm test`

#### UML - Class example

![uml design for token](./assets/class-example-uml.png)
