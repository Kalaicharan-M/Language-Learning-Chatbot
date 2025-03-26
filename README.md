1.How It Works
• User selects a language and scenario.
• Chatbot initiates a conversation using the selected scene.
• User interacts with the chatbot, and responses are processed via LangChain.
• Bot identifies mistakes and logs them in SQLite.
• At the end of the session, a progress report is generated.
2. Code Structure
 language-learning-bot/
 │── language_bot.py # Main script
 │── bot/
 │ ├── core.py # Handles conversation logic
 │ ├── database.py # SQLite-based mistake tracking
 │ ├── prompts.py # AI-generated prompts
 │── requirements.txt # Dependencies
3. Installation & SetupStep
 1: Install Dependencies
 pip install -r requirements.txtStep
 2: Run the Chatbot
 python language_bot.py
