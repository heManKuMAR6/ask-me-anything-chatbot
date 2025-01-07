# ask-me-anything-chatbot

💻 Zenix Finance Website
Zenix Finance is a modern, black-and-white themed finance website designed to provide users with financial insights and educational resources. This platform allows users to analyze financial queries and displays relevant YouTube videos for additional guidance and learning.

🌟 Features
🔎 Financial Query Analysis: Users can type any financial-related question and get an instant response.
🎥 Educational Videos: Displays curated YouTube videos related to the user's query.
🎨 Aesthetic Design: Features a sleek, artistic black-and-white theme for a professional and elegant look.
⚡ Responsive UI: Fully responsive design for seamless experience across all devices.
🛠️ Tech Stack
Frontend:
HTML5: Structure of the website.
CSS3: Styling and layout.
JavaScript: Interactive user interface.
Backend:
Python: Core backend logic.
Flask: Lightweight web framework for API and routing.
APIs:
YouTube Data API: Fetches video suggestions based on user queries.
📂 Project Structure
bash
Copy code
zenix-finance-website/
├── app.py              # Flask backend application
├── requirements.txt    # Python dependencies
├── .env                # API keys (excluded in deployment)
├── static/             # Static files directory
│   ├── index.html      # Frontend HTML file
│   ├── styles.css      # CSS file
│   ├── script.js       # JavaScript file
│   └── zenix-logo.png  # Logo image
🚀 Getting Started
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
4. Set Up API Keys
Create a .env file in the project directory.
Add the following:
plaintext
Copy code
YOUTUBE_API_KEY=your-youtube-api-key
5. Run the Application
bash
Copy code
python app.py
Visit the app at http://127.0.0.1:5000.

🧪 How It Works
User Query: Enter a finance-related question into the input box (e.g., "How to start investing?").
Analyze Query: The app processes the query and displays a mock analysis result.
Educational Videos: Curated YouTube videos related to the query are displayed on the right side.
🖼️ Screenshots
Homepage

YouTube Videos Section

🛠️ Deployment
Deploy on Render
Push your code to a GitHub repository.
Create a free account on Render.
Connect your GitHub repository.
Add environment variables (YOUTUBE_API_KEY) in Render.
Deploy the application.
Alternative: Deploy on Fly.io
Install the Fly.io CLI:
bash
Copy code
curl -L https://fly.io/install.sh | sh
Initialize the project:
bash
Copy code
flyctl launch
Deploy using:
bash
Copy code
flyctl deploy
🏗️ Future Enhancements
Integrate advanced AI/ML models for financial analysis.
Add support for dynamic charts and data visualization.
Include additional APIs for market trends and insights.
📝 License
This project is licensed under the MIT License.
