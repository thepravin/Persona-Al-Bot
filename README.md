# Persona-Al-Bot

**Persona-Al-Bot** is an AI-powered chatbot that emulates the teaching style of Hitesh Choudhary, a renowned tech educator. Built using Streamlit and Google's Gemini API, this chatbot provides responses in Hindi, maintaining a friendly and instructional tone.

## Features

* Interactive chat interface powered by Streamlit.
* Emulates Hitesh Choudhary's teaching style and tone.
* Responds in Hindi.
* Utilizes Google's Gemini API for generating responses.
* Session-based chat history for seamless conversations.


## 🚀 Live Demo

```

https://persona-al-bot-pravin.streamlit.app/

```


## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/thepravin/Persona-Al-Bot.git
   cd Persona-Al-Bot
   ```



2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```



3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```



4. **Set up your Gemini API key:**

   You can provide your Gemini API key in two ways:

   * **Option 1:** Create a `.env` file in the project root directory and add your API key:

     ```env
     GEMINI_API_KEY=your_api_key_here
     ```

   * **Option 2:** If you don't set the API key in a `.env` file, the application will prompt you to enter it upon launching.

## Usage

To start the chatbot, run:

```bash
streamlit run app.py
```



The application will open in your default web browser.

## File Structure

```plaintext
Persona-Al-Bot/
├── .devcontainer/        # Development container configuration
├── .gitignore            # Git ignore file
├── CLI-App.py            # Command-line interface version (optional)
├── app.py                # Main Streamlit application
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```



## Dependencies

* Python 3.7 or higher
* Streamlit
* google-generativeai
* python-dotenv

Install all dependencies using the provided `requirements.txt` file.

## Contributing

Contributions are welcome! If you'd like to enhance the chatbot or fix any issues, please fork the repository and submit a pull request.


## Acknowledgments

* [Hitesh Choudhary](https://www.youtube.com/c/HiteshChoudharyOfficial) for his inspiring teaching style.
* [Streamlit](https://streamlit.io/) for the intuitive web app framework.
* [Google's Gemini API](https://ai.google.dev/) for powering the chatbot's responses.


<div align="center">
<h1>🧑‍💻 Happy coding!</h1>
</div>

