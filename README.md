# ask-me-anything-chatbot

Zenix Finance Website
Zenix Finance is a beautifully designed black-and-white themed website for financial analysis and education. It allows users to ask financial-related questions and view relevant YouTube videos for learning.

Features
Elegant black-and-white design with an aesthetic, professional look.
Analyze financial goals and get instant responses.
Display educational YouTube videos related to the user's query.
Fully responsive and interactive design.
Table of Contents
Features
Technologies Used
Project Structure
Installation
Deployment
Usage
Screenshots
License
Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: Python, Flask
APIs:
OpenAI API (optional for analysis)
YouTube Data API for fetching videos
Hosting: Render (or Fly.io/Vercel)
Project Structure
bash
Copy code
chatgpt-finance-website/
├── app.py              # Flask backend application
├── requirements.txt    # Python dependencies
├── .env                # API keys (not included in the repo)
├── static/             # Static files directory
│   ├── index.html      # Frontend HTML file
│   ├── styles.css      # CSS file
│   ├── script.js       # JavaScript file
│   └── zenix-logo.png  # Logo image
Installation
1. Clone the Repository
bash
Copy code
git clone https://github.com/your-username/zenix-finance.git
cd zenix-finance
2. Create a Virtual Environment
bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
bash
Copy code
pip install -r requirements.txt
4. Set Up Environment Variables
Create a .env file in the project directory and add your API keys:

plaintext
Copy code
CHATGPT_API_KEY=your-chatgpt-api-key
YOUTUBE_API_KEY=your-youtube-api-key
5. Run the Application
bash
Copy code
python app.py
The app will be available at http://127.0.0.1:5000.

Deployment
Using Render
Push your code to a GitHub repository.
Create a free account on Render.
Connect your GitHub repository.
Add environment variables (CHATGPT_API_KEY and YOUTUBE_API_KEY) in Render.
Deploy your app and get a live URL.
Using Fly.io
Install the Fly.io CLI.
Run flyctl launch to initialize the project.
Add a Dockerfile to the project (optional).
Deploy using flyctl deploy.
Access your app via the provided URL.
Usage
Open the deployed app in your browser.
Enter your financial query in the text box (e.g., "How to start saving for retirement?").
Click Analyze to see an analysis and relevant YouTube videos.
View educational videos on the right side of the page.
Screenshots
Homepage

Video Section

Contributing
We welcome contributions to improve Zenix Finance! Feel free to submit a pull request or open an issue on the repository.

License
This project is licensed under the MIT License.
