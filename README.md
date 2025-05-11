🤖 Intelligent Chatbot with Speech Recognition¶

Project Type: AI Chatbot | Technology Stack: Python, NLTK, SpeechRecognition

Welcome to the intelligent chatbot project. This notebook demonstrates how to build a conversational agent using NLP and speech recognition technologies. The chatbot interacts using both text and voice input/output.
This project implements a simple chatbot interface using Python's Tkinter for the GUI and basic Natural Language Processing techniques for chatbot responses. It's designed for educational and beginner-friendly purposes to demonstrate how chatbots work.

📚 Table of Contents¶
Introduction
Library Imports
Data Preparation
Model Definition
Speech Recognition Integration
Chat Interface
Conclusion


Requirements:
1. numpy
2. NLTK toolkit
3. tkinter
4. pyttsx3 
5. jupyter notebook

🧰 Features
* GUI-based chatbot built with Tkinter
* Rule-based responses using basic if-else logic
* Easy to extend with more NLP logic or datasets

 How to run:
1. import the required libraries.
2. import the chatr file and after downloading chatr file change the path according to your system.
3. download and import the nltk tools like punkt and wordnet and run them all once only not run every time while executing the project.
4.run every cell one by one in jupyter notebook 
5. chatbot interface will open
6. start asking quieries related to vantharr technologies.
7. send, pause button and stop button is used in this project to controll the voice messages:
   * if you click on pause button it starts speaking
   * if you click on stop button it stop speaking and only messages are displayed recarding to you query

* note: you can change the dataset in the chatr file, i had a dataset related to my institution.


*note: before installing the libraries create a virtual environment using this commands in cmd(command prompt) in your project folder:
1. python -m venv myenv(to create a env file, create only once)
2. myenv\Scripts\activate(to activate the env file, run this command every time while you are running your project) in cmd

3. after activating the env starting installing using pip in cmd:
* pip install nltk
* pip install pyttsx3

💡 Future Improvements
* Integrate with a real NLP model (e.g., ChatterBot, Rasa, or OpenAI's GPT)
* Add voice input/output support
* Use JSON/YAML to store response templates

Advantages:
* you can change color theme and fonts which you like
* this chatbot has speech recognization which converts text to audioable speech
* it has help support also regarding to the chabot
* it has clear and exit option also
* it has a playbutton and stop button for speech

Disadvantage:
* Very Limited Conversation Capability: It cannot handle multi-turn conversations or context-aware interactions
* No Backend or API Integration:It cannot fetch data from external APIs or databases, making it static and limited in functionality.
* No Error Handling: User input is not cleaned or validated. Unexpected input might cause crashes or no response.
* Poor User Experience: There’s no fallback mechanism if the chatbot doesn’t understand something. It may feel robotic or frustrating for users without intelligent response handling.

Sreenshots:

<img width="296" alt="image" src="https://github.com/user-attachments/assets/93d5e2fc-821d-4b28-9d82-6752a87d1ca1" />   
<img width="298" alt="image" src="https://github.com/user-attachments/assets/4ccb31ad-e08b-4652-bd76-bc3cdcb28f47" />
<img width="536" alt="image" src="https://github.com/user-attachments/assets/3f3d4c07-7724-468e-b20d-eb2efbd64ac1" />
<img width="540" alt="image" src="https://github.com/user-attachments/assets/15887af2-b8eb-435e-9c4e-8cc9e3075d59" />
<img width="514" alt="image" src="https://github.com/user-attachments/assets/6adf0e57-1262-4f87-904f-7ce9c39efb5a" />





