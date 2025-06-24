Third Wave Coffee Research Chatbot (RAG + Mistral AI)
A Retrieval-Augmented Generation (RAG) chatbot built with Flask and Mistral AI, designed to help users explore concepts, studies, and terminology from the world of third wave coffee.

Powered by World Coffee Research, scientific literature, and other specialty coffee resources.

This educational chatbot helps coffee professionals, enthusiasts, and researchers access knowledge about coffee genetics, processing methods, sensory science, and sustainability innovations.

About the Creator
Website: www.halimmadi.com

Instagram: @yalla_halim

Setup
Clone the repository

Create a virtual environment:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Create a .env file with your Mistral API key:

ini
Copy
Edit
MISTRAL_API_KEY=your_api_key_here
Add your coffee-related content source as essay.txt in the project root. You can include text from World Coffee Research or other trusted sources.

Local Development
Run the Flask application:

bash
Copy
Edit
python app.py
Then navigate to http://localhost:5001 in your browser.

Deployment to Vercel
Push your code to GitHub

Connect your GitHub repository to Vercel

Add the environment variable MISTRAL_API_KEY in the Vercel dashboard

Deploy!

Environment Variables
MISTRAL_API_KEY: Your Mistral AI API key (required)

Project Structure
app.py: Main Flask application logic

templates/: HTML templates for the UI

static/: CSS and JavaScript files

essay.txt: The corpus of coffee research material for the chatbot

requirements.txt: Python dependencies

vercel.json: Vercel deployment configuration

Usage and Licensing
This project is provided as a learning and exploration tool for coffee educators, baristas, researchers, and anyone interested in deepening their understanding of specialty coffee. You are welcome to:

Use this project for education and research

Customize it with your own coffee resources

Share it with others in the coffee community

Use it in workshops, meetups, or educational settings

For questions or contributions, reach out to Halim Madi.

