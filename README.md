# My Steam Analyzer 🎮

A simple web application that uses the Steam Web API to fetch and display my owned games in Steam library. 
It includes a visual chart of my most played games and a list of my entire game library. 



### ✨ Features

* Steam API Integration: Fetches real-time data from the Steam Web API.
* Top 10 Chart: Visualizes the top 10 most played games using Chart.js.
* Game List: Displays a complete list of the user's owned games.
* Responsive Design: The app is fully responsive and works on both desktop and mobile devices.


### ⚙️ Technologies Used

* HTML5: Structure of the web application.
* CSS3: Styling and responsive design.
* JavaScript : Core logic, DOM manipulation and data vizualisation
* Python : Flask, Requests, and Flask-CORS



### 📦 Setup and Installation

Prerequisites
* Python 3.x
* `pip` (Python package installer)

1. Clone the repository:

`git clone https://github.com/ouarda101/mySteamAnalyzer.git`

2. Get Your Steam Web API Key :
   
* Go to the Steam Web API Key registration page.
* Log in with your Steam account.
* Register a new key by entering a domain name (you can use localhost for local development).
* Copy the generated API key.

3. Configure the Backend :
   
* Open the `app.py` file.
* Find the `STEAM_API_KEY` variable and paste your API key into the empty quotes.
* Find the `STEAM_ID` variable and replace the placeholder ID with your 64-bit Steam ID. You can find this using a tool like SteamID.io.


4. Run the Backend Server

* Install the required Python packages:

`pip install Flask requests flask-cors`

* Run the Flask server from your terminal:

`python app.py`

The server will start on http://127.0.0.1:5000.

5. View the Frontend :

* Open the index.html file in your web browser.
* The frontend will automatically connect to the running backend and display your game library.

  
### 🖼️  Demo


<img width="1920" height="4720" alt="full website screen" src="https://github.com/user-attachments/assets/b1ceb492-3493-4a0d-ab80-bca52dc8a6c7" />



📄 **Feel free to explore, fork, and contribute!**
