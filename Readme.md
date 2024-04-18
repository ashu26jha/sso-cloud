# SSO Based weather app

First of we all, we will populate the environment variables. 

There are two ways to run the project:

### Without Docker
```bash
node index.js
```

### With docker 

To build the docker image:

```bash
docker build . -t ashutosh_jha/sso:v1 
```
To run the docker image:

```bash
docker run -d -p 5001:5001 ashutosh_jha/sso:v1
```