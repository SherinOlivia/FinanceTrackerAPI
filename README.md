
# Week 8 Assignment Overview

For Week 8's Assignment, we are to create a simple REST API Server 

## API Endpoints

| Name  | HTTP Method | Endpoint | 
| ----------- | ----------- | ----------- |
| **Homepage** | `GET` |[/](https://roofinancetracker-prod.up.railway.app/)
| **List All Transaction Data** | `GET` | [/transactions](https://roofinancetracker-prod.up.railway.app/transactions)
| **Get Transaction Data by ID** | `GET` | [/transactions/:id](https://roofinancetracker-prod.up.railway.app/transactions/1) |
| **Create New Transaction Data** | `POST` | [/transactions](https://roofinancetracker-prod.up.railway.app/transactions) |
| **Update Whole Transaction Data by ID** | `PUT` | [/transactions/:id](https://roofinancetracker-prod.up.railway.app/transactions/1) |
| **Update Transaction Type by ID** | `PATCH` | [/transactions/ttype/:id](https://roofinancetracker-prod.up.railway.app/transactions/ttype/1) |
| **Update Transaction Name by ID** | `PATCH` | [/transactions/tname/:id](https://roofinancetracker-prod.up.railway.app/transactions/tname/1) |
| **Update Transaction Detail by ID** | `PATCH` | [/transactions/tdetail/:id](https://roofinancetracker-prod.up.railway.app/transactions/tdetail/1) |
| **Update Transaction Amount by ID** | `PATCH` | [/transactions/tamount/:id](https://roofinancetracker-prod.up.railway.app/transactions/tamount/1) |
| **Delete Transaction Data by ID** | `DELETE` | [/transactions/:id](https://roofinancetracker-prod.up.railway.app/transactions/1) |


## Postman & Thunder Client

<p>Through Postman or Thunder Client, we will be able to test our API's routing and codes to ensure 
functionalities.</p> 

**Postman** 
: an API platform for building and using APIs

![postman-download]( )

1. To download postman, head to [**postman.com**](https://www.postman.com/downloads/)

![postman-overview]( )

<p>Although we don't have to create an account for Postman, creating one will allow us to access workspace, a space on the side where we can create our API requests.</p>

2. An example of neat workspace

![postman-workspace]( )

**Thunder Client** 
: a lightweight GUI based Rest API Client Extension for Visual Studio Code

## Deployement through Railway
<p align="center">
<a href="https://roofinancetracker-prod.up.railway.app/">roofinancetracker-prod.up.railway.app/</a>
</p>

**Railway** 
: a Platform as a Service (PaaS) that offers a complete platform for building and delivering programs to the backend of the cloud. Which means <strong>Railway</strong> is one of the many options where we can deploy our back-end codes.

1. First, head to [**railway.app**](https://railway.app/), and click login with github account.
- ![railway-web]( )
- ![railway-login]( )

2. Click New Project and the github repository that houses your backend sourcecode
![railway-newproject]( )
![railway-projectrepo]( )

3. Railway will proceed to start building and deploying your project, when completed, you may set the web
![railway-domainname]( )

4. Your project is ready for use.
### Contact Me:

<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-7-SherinOlivia/3dd7cdf0d5c9fc1828f0dfcac8ef2e9c057902be/assets/gmail-icon.svg" width="15px" background-color="none">[SOChronicle@gmail.com](mailto:SOChronicle@gmail.com) [Personal]

<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-7-SherinOlivia/3dd7cdf0d5c9fc1828f0dfcac8ef2e9c057902be/assets/gmail-icon.svg" width="15px" background-color="none">[SOlivia@gmail.com](mailto:SOlivia198@gmail.com) [Work]

[![Roo-Discord](https://raw.githubusercontent.com/RevoU-FSSE-2/week-5-SherinOlivia/bddf1eca3ee3ad82db2f228095d01912bf9c3de6/assets/MDimgs/icons8-discord.svg)](https://discord.com/users/shxdxr#7539)[![Roo-Instagram](https://raw.githubusercontent.com/RevoU-FSSE-2/week-5-SherinOlivia/bddf1eca3ee3ad82db2f228095d01912bf9c3de6/assets/MDimgs/icons8-instagram.svg)](https://instagram.com/shxdxr?igshid=MzRlODBiNWFlZA==)[![Roo-LinkedIn](https://raw.githubusercontent.com/RevoU-FSSE-2/week-5-SherinOlivia/bddf1eca3ee3ad82db2f228095d01912bf9c3de6/assets/MDimgs/icons8-linkedin-circled.svg)](https://www.linkedin.com/in/sherin-olivia-07311127a/)