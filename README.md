# Q&A Chatbot with OpenAI

This project is an interactive and customizable chatbot built using OpenAI's GPT models and Streamlit. It provides an easy-to-use interface for users to ask questions and receive responses, making it suitable for a variety of Q&A applications.

---

## Features

- **Streamlit Interface**: A simple and responsive UI for interacting with the chatbot.
- **Customizable Settings**:
  - Select the desired OpenAI GPT model (`gpt-4o`, `gpt-4-turbo`, `gpt-4`).
  - Adjust temperature for creative or precise responses.
  - Configure the maximum token limit for answers.
- **Environment Configuration**: Securely manage API keys using `.env` files.

---

## Prerequisites

- Python 3.8 or higher
- OpenAI API key
- Installed dependencies (see below)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/qa-chatbot.git
   cd qa-chatbot
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the root directory and add your OpenAI API key:
   ```
   LANGCHAIN_API_KEY=your_openai_api_key
   ```

---

## Usage

1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

2. Open the app in your browser at `http://localhost:8501`.

3. Use the sidebar to:
   - Input your OpenAI API key.
   - Select a GPT model.
   - Customize temperature and max tokens.

4. Ask your question in the input field and get instant responses.

---

## File Structure

- **`app.py`**: Contains the main Streamlit application code.
- **`.env`**: Stores environment variables securely (e.g., API keys).
- **`requirements.txt`**: Specifies the required Python dependencies.

---

## Dependencies

This project uses the following Python libraries:
- `streamlit`
- `openai`
- `langchain_openai`
- `langchain_core`
- `python-dotenv`

---

## Future Enhancements

- Add support for additional AI models.
- Include conversation history tracking.
- Enable cloud deployment (e.g., AWS, Azure, or Streamlit Cloud).

---

## Contributing

Contributions are welcome! If you have any ideas or improvements, feel free to open an issue or submit a pull request.

---

## License

This project is licensed under the MIT License.

---
