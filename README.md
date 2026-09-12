<h1>FitAI</h1>
<h2>AI fitness trainer that can generate a workout plan, diet plan, and many more for the user.</h2>
<h2> CS50W Final Project</h2>

Distinctiveness and Complexity:

My project reaches the complexity and distinctiveness requirements because of its use of the ChatGPT api. My project utilizes the ChatGPT api to generate answers for the user. The user will first type in the question and enter it in. ChatGPT gets the question and through the api, it sends the question to my server and displays it on screen. My project uses the POST method to display the answer on screen. The ChatGPT Ai is also customized and trained to only answer fitness based questions. It is also trained to make better diet, and workout plans specific to the users request. The AI will listen to specific words given in the question. If one where to ask about a workout plan to lose weight, ChatGPT will give a custom workout plan only to lose weight. It is trained to give custom plans based on the bodytype, age, height, weight, and fitness goals of the user. It also stores the answer inside of the user database, on a history page where only the user can access it. I used SQL to store the answers, and kept them along with a table where all the users are. Before accessing the AI, the user must log-in. I made a custom login, and registration page to access the website. The user can only access the site only if they are logged in. I made that possible by using the ```@login_required function```. My project also requires the user to re-enter their password when they register for the site. 


Contents inside folders:

My project contains many files to maintain the project. In the folder ```chatbot```, it contains folders and files necessary for making the project function. In ```views.py```, it contains the api key, and all the functions for the project. The file ```urls.py``` contains all the links and URLs to get to each page in my project. ```models.py``` Contains the ```Chat``` model which stores the users chats with the ai. It includes the message, user, response generated, and the time it was created. Finally ```static``` contains the CSS files for the project, and the Javascript file to import the ChatGPT api. Inside of ```django-chatbot```, it has all the files to load the project and it connects it to the ```chatbot``` app. All of the HTML files are stored in the folder called ```templates```. It has all the files to load each page such as ```index.html```, and for the layout page ```layout.html```. 

How to run the applicaton:
To run the project, first run ```python manage.py runserver```, to start the server. Next, you will be taken to the ```Login page```. Register for an account and login. Once you have logged-in, you may now ask the fitness AI to generate you a diet or workout plan. Type in the question in the text box and click Send. It will take a few seconds, but ChatGPT will receive the question, and will give you the answer within 30 seconds. If you'd like to view your past conversations with the AI, you can click on the Chat History page. 

<a href="https://youtu.be/3Ra01rz8gBY"><h2>App Demonstration</h2></a>
