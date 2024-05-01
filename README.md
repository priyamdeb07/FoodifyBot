# FoodifyBot

# Description
This project is about a food chatbot that provides a conversational interface that can assist users with various food-related tasks such as placing orders and answering inquiries.

# Libraries Used
1. FastAPI
2. Request Class from FastAPI
3. MySQL-connector-python
4. re
5. JSON Response as a subclass of Response
# Installation
1. MySQL connector should be installed
##
    pip install mysql-connector
2. FastAPI is to be necessarily installed
##
    pip install fastapi[all]
# Execution
1. To run fastapi backend server<br>
   a. Go to backend directory in your command prompt<br>
   b. Run this command:
   ##
        uvicorn main:app --reload
3. Ngrok for https tunneling<br>
   a. To install ngrok, go to [https://ngrok.com/download] and install ngrok version that is suitable for your OS<br>
   b. Extract the zip file and place ngrok.exe in a folder<br>
   c. Open windows command prompt, go to that folder and run this command:
   ##
       ngrok http 8000
   NOTE: ngrok can timeout. you need to restart the session if you see session expired message.
# Output
1. Creation of Intents
   
   <img width="450" alt="image" src="https://github.com/priyamdeb07/FoodifyBot/assets/131014885/2dabb9dd-4360-440c-86a4-eaf896f978c7">
2. Integration followed by Web Demo
   
   <img width="450" alt="image" src="https://github.com/priyamdeb07/FoodifyBot/assets/131014885/69582538-5678-4bb5-b89d-a9bf0426babd">
3. User Interface of the Bot

   <img width="450" alt="image" src="https://github.com/priyamdeb07/FoodifyBot/assets/131014885/35cd7200-90c6-4c11-99ac-61f859c9de6f">



   
