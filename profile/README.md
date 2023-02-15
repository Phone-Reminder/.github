# Reminders App 

- [Reminders App](#reminders-app)
  - [About](#about)
  - [Getting Started](#getting-started)
    - [Installation (for local setup):](#installation-for-local-setup)
  - [Project Review](#project-review)
    - [Main Takeaways:](#main-takeaways)
    - [Future ideas:](#future-ideas)


## About
**Date of completion: 16/02/2023**

**Authors: Benjamin Tracey and Sweta Shah**

**Deployed Website: https://reminders-bt-ss.netlify.app/**
 
This is a full-stack passion project. A REST API was developed with **Go** using [Gin](https://github.com/gin-gonic/gin) framework. A React client was developed using **TypeScipt**. 

A user can enter their phone number, the date/time they want a reminder to be sent, and the message contents. These details are then stored using **MongoDB**. Then using Twilio API, the user will recieve the reminder as an SMS at the given time. **However, due to Twilio free-trial limiations the app will only work with phone numbers verified by Twilio.**

## Getting Started

### Installation (for local setup):

- Clone the server git repo
```
    git clone https://github.com/Phone-Reminder/server.git
```
- Install dependencies in root of project 
  
  ```
  cd server
  go mod download
  ```

- Start server by entering `sever` directory (ensure nothing is already running on port: 4000).
    ```
    cd server
    go run main.go 
    ```


-Clone the Client

```
    git clone 
    https://github.com/Phone-Reminder/client.git
```

- Start react app by entering `client` directory (ensure nothing is already running on port: 3000).

    ```
    cd client
    npm i
    npm start
    ```

## Project Review

### Main Takeaways:
- Developed REST API using Go with Gin Framework.
- Using TypeScript instead of JavaScript to build a react APP.
- Deploying a Go Gin App. 
- Use of GO Routines for concurrent code execution. 

### Future ideas:
- Move away from Twilio free trial to allow any user to use the app. 
- Develop the android/IOS version.

  




