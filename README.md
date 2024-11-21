# AI-chatbot-G
# AI Chatbot with OpenAI and Gradio

This is a Python-based AI chatbot application that uses OpenAI's GPT-3.5-turbo model and Gradio for the user interface. The chatbot can handle a wide variety of user queries and provides intelligent responses.

## Features
- *Chat Interface*: Interact with the chatbot through a simple and clean Gradio web interface.
- *Secure API Integration*: The OpenAI API key is stored securely in a config.yaml file.
- *Customizable*: Easily modify the chatbot's behavior by changing the system message.
- *Easy Sharing*: Share your chatbot online with Gradio's shareable link.

---

## Requirements

Before running this project, ensure you have the following:
- Python 3.7 or higher
- OpenAI API key (Sign up at [OpenAI](https://platform.openai.com/) if you don’t have one)

---

## Installation

1. *Clone the repository*:
   bash
   git clone https://github.com/gauravpapnai03/AI-chatbot-G
   cd ai-chatbot
   

2. *Install the required Python libraries*:
   bash
   pip install openai gradio pyyaml
   

3. *Create a config.yaml file*:
   In the project directory, create a config.yaml file and add your OpenAI API key:
   yaml
   api: "sk-************************************************"
   

4. *Run the application*:
   bash
   python app.py
   

---

## File Structure


├── app.py           # Main application script
├── config.yaml      # Configuration file for API key
├── requirements.txt # (Optional) List of dependencies
└── README.md        # Project documentation


---

## Usage

1. Start the application:
   bash
   python app.py
   
2. Open the Gradio interface in your browser (a link will be provided in the terminal).
3. Interact with the chatbot by typing in your questions.

---

## Example Interaction

*User*: "What is the capital of France?"  
*Chatbot*: "The capital of France is Paris."

---

## Notes
- Keep your config.yaml file private and secure. Avoid sharing or committing it to version control.
- If you encounter issues with the OpenAI API, ensure your API key is valid and has sufficient usage limits.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to modify this file to include additional details or features about your project!
