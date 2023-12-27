
# Order Tracking Chatbot

This document provides comprehensive information on setting up, configuring, and utilizing our chatbot designed to enhance the customer experience in tracking and adding orders.


## Tech Stack


**Server:** FastAPI

**Database:** Management: MySQL Workbench

**Client:** HTML, CSS, JavaScript

**Natural Language Processing:** Dialogflow
Integrated for natural language understanding and processing. 
## Features

- Add and Remove Items: Allow users to add or remove items from their orders through natural language interactions.

- Order Tracking by Order ID:Enable users to track specific orders by providing the order ID.

All these features are interacted with database...

- Demo Integration:Integrate a demo environment to showcase the chatbot's capabilities without deploying to a live server.

- Toggle Chat Button in Frontend:Provide a user-friendly way to toggle the visibility of the chat interface on the frontend.



## Screenshots

Trained th model with intents and entities:-

![App Screenshot](https://github.com/Harikrishna050/chatBot_FoodService/blob/main/demo_images/Screenshot%20(226).png?raw=true)

Demo Screenshots:-

![App Screenshot](https://github.com/Harikrishna050/chatBot_FoodService/blob/main/demo_images/Screenshot%20(227).png?raw=true)

![App Screenshot](https://github.com/Harikrishna050/chatBot_FoodService/blob/main/demo_images/Screenshot%20(228).png?raw=true)

![App Screenshot](https://github.com/Harikrishna050/chatBot_FoodService/blob/main/demo_images/Screenshot%20(229).png?raw=true)






## Run Locally

First of all,enabled the required fullfillments for intents that interact with backend

Clone the project

In pycharm
Go to the project directory

```bash
  cd MychatBot
```

Install dependencies

```bash
  pip install fastapi
  pip install mysql-connector-python
```

Start the server

```bash
  uvicorn main:app --reload
```

Integrated the chatBot from Dialogflow to frontend part in succesfully with toggle chat Button....

