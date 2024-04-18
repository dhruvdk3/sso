# SSO Based weather app

First of we all, we will populate the environment variables. 
For this store youre client id and client secrete id in .env

There are two ways to run the project:

### Without Docker
```bash
node index.js
```

### With docker 

To build the docker image:

```bash
docker build . -t dhruv/sso:v1 
```
To run the docker image:

```bash
docker run -d -p 5001:5001 dhruv/sso:v1
```
