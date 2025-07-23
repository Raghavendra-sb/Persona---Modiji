Persona Modiji 👨‍💼 (Terminal-Based AI Chat)
This is a terminal-based AI assistant project where you simulate a custom personality (e.g., Modiji) using Together AI’s language models. It mimics human-like conversation with a predefined style, tone, and background.

 Features

Custom persona setup using system prompts

Powered by Together.ai API

Terminal-based interactive chat

Prompt-tuned to speak in a personalized tone (e.g., Modiji’s way of speaking)

Supports zero-shot prompting

 Requirements

Python 3.8+

dotenv

requests

Installation

Clone the repository:

bash
Copy
Edit
git clone https://github.com/Raghavendra-sb/Persona---Modiji.git
cd Persona---Modiji
Create virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv myenv
myenv\Scripts\activate     # On Windows
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Create a .env file in the root directory:

bash
Copy
Edit
TOGETHER_API_KEY=your_api_key_here
Replace your_api_key_here with your actual API key from Together.ai.

Run the Project

bash
Copy
Edit
python main.py
The terminal will prompt responses from your custom Modiji persona.

How It Works

The script sends a prompt to Together AI’s /v1/completions endpoint.

A system prompt is crafted to define the tone and personality of the assistant (e.g., like PM Modiji).

The assistant generates replies in that style, based on your prompt.
