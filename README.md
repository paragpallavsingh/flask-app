# flask-app
Sample Flask app for testing docker compose

To start your application
```
docker-compose up
```

To build or rebuild services

```
docker-compose up --build
```

<kbd><img width="577" alt="image" src="https://github.com/paragpallavsingh/flask-app/assets/40052830/d6087950-e539-4eb2-a10f-dabd8fdb0f3c"></kbd>

To check more about it, refer [**Docker Compose**](https://docs.docker.com/compose/gettingstarted/)

# Jenkins Test Runs

```
docker-compose up
```

<kbd><img width="713" alt="jenkins server ss" src="https://github.com/paragpallavsingh/flask-app/assets/40052830/4c4857a7-1701-406c-bd1d-eee2a83d4b39"></kbd>


```
docker-compose up -d
```

<kbd><img width="403" alt="jenkins server dc up down" src="https://github.com/paragpallavsingh/flask-app/assets/40052830/df3da2ce-96df-4225-9728-40e6c3acd512"></kbd>

**Running app after successful build**

<kbd><img width="454" alt="jenkins flask run" src="https://github.com/paragpallavsingh/flask-app/assets/40052830/4adbaec9-282f-4e1d-8b37-a5f612293074"></kbd>

**Fetching changes from Github**

<kbd><img width="621" alt="jenkins after change" src="https://github.com/paragpallavsingh/flask-app/assets/40052830/049dd2d7-67dc-4dcc-b77d-4dd807b97ba5"></kbd>

**SCM Polling**

<kbd>![image](https://github.com/paragpallavsingh/flask-app/assets/40052830/8d512a9c-40e7-476c-a49e-4471f3ddf8c0)</kbd>

## Steps to Set Webhook on Github
1: Go to repository --> Settings --> Webhooks
2: In the Payload URL, paste your "Jenkins server URL"github-webhook/
3: Select the event (PUSH/everything/individual event) for trigger 
4: Save Webhook

<kbd>![image](https://github.com/paragpallavsingh/flask-app/assets/40052830/1e3e64cb-6010-4d39-802c-421b2f270c87)</kbd>




