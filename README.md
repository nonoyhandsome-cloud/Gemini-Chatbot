# 🚀 Setup and Run the Gemini Chatbot App
1. Install Required Software: Visit the official website (https://nodejs.org), then  install the LTS (Long Term Support) version. After installation, open Command Prompt or Terminal and verify the installation by running: node -v and npm -v. If the installation is successful, version numbers for Node.js and npm will appear.

2. Extract the Project Files: Locate the downloaded file, right-click the file then select extract all after that choose a location where the project folder will be stored.

3. Open the Project in VS Code: Launch Visual Studio Code, click file → open folder then select the extracted project folder after that click open.

4. Install Project Dependencies: In the terminal, type: npm install (This command will download and install all required dependencies listed in the project's package.json file.)

5. Add Your Gemini API Key: Open the .env file located in the project folder then find the following line: GEMINI_API_KEY=your_api_key_here after that replace your_api_key_here with your actual Gemini API key. If you do not yet have an API key, create one through Google AI Studio: https://aistudio.google.com

6. Run the Server: Start the application server by running one of the following commands in the terminal: npm start or node server.js (The server will start and run locally on your machine.)

7. Open the Application in Your Browser: Once the server is running: Open any web browser then navigate to: http://localhost:3000 (The application should now be accessible.)
