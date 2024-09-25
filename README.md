#🦙💬 Llama 2 Chatbot using Streamlit & Replicate API
This project is an interactive chatbot built using the Llama 2 language model from Meta, integrated with Streamlit for the web interface and hosted via the Replicate API. Users can interact with the chatbot, choose between different models, and customize parameters for generating responses.

Why Llama 2 and not ChatGPT?
Although I have my own chatbot, I chose to use Llama 2 for this project to explore and showcase the capabilities of open-source models like Llama 2, which provide more flexibility for fine-tuning, customization, and deployment. Unlike proprietary models like ChatGPT, Llama 2 offers control over the model and is ideal for learning how to integrate large language models with custom workflows.

🚀 Features
Streamlit Web App: Interactive web UI built using Streamlit.
Model Selection: Choose between Llama2-7B and Llama2-13B models.
Customizable Parameters:
Temperature: Adjust the creativity of the model's responses.
Top-p: Control the diversity of the generated tokens.
Max Length: Define the maximum response length.
Real-Time Responses: Get real-time responses from the Llama 2 model.
Persistent Chat: Conversation history is stored for a continuous chat experience.
Clear Chat History: Users can reset the chat and start a new conversation.
📚 Usage
Open the web app in your browser.
Enter your Replicate API token in the sidebar or use the stored token.
Select the Llama 2 model (either Llama2-7B or Llama2-13B).
Customize parameters like temperature, top_p, and max_length.
Enter your prompts in the chat interface and see the model's responses in real-time.
Clear the chat using the Clear Chat History button if needed.
🧩 Project Structure
bash
Copy code
llama2-streamlit-chatbot/
│
├── .gitignore           # Ignore sensitive and unnecessary files
├── README.md            # Project documentation
├── requirements.txt     # List of Python dependencies
├── app.py               # Main Streamlit app script
└── secrets.toml         # API key storage (not pushed to Git)
🌟 Key Components
Replicate API: Used for accessing the Llama 2 models hosted on Replicate.
Streamlit: Web interface for interacting with the chatbot.
Llama 2: Open-source LLM from Meta.
📬 Contact
Feel free to reach out if you have any questions or feedback!

LinkedIn: https://www.linkedin.com/in/ambatibhargavi/
