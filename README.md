# Node_Gohst
Ghost is a free and open source blogging platform written in JavaScript and distributed under the MIT License, designed to simplify the process of online publishing for individual bloggers as well as online publications.

With this solution you can quickly create a Docker instance of Ghost and MySQL using Docker Compose.

## Recomendations
Before creating a publicly available instance ensure you review the image and set the passwords to a secure password or add them as an environemnt variable.

## Getting Started
To create a compose service run the below command from the folder where your ___docker-compose.yml___ file is located

```
docker-compose up -d
```
If you run ```docker-compose ps``` you will see two instances, one for Ghost and on for MySQL
