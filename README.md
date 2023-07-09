# Q&A System based on GPT3.5 and Document retrival using Langchain


## Installation

To use the LangChain Q&A System, follow the steps below:

1. Clone the repository using the following command:
```
 git clone https://github.com/tanav2202/langchain-gpt.git
```

2. Navigate to the project directory:

```
cd langchain-gpt
```

3. Install the required dependencies by running the following command:
```
    pip install -r requirements.txt
```

## Usage

To use the LangChain Q&A System, you need to provide an API key from OpenAI. Follow these steps to get started:

1. Sign up or log in to your [OpenAI](https://openai.com/) account.

2. Generate an API key if you haven't already. Make sure you have the necessary permissions to access the GPT-3.5 language model.

3. Open the `test.py` file in a text editor.

4. Locate the line of code that sets the API key:
```python
os.environ["OPENAI_API_KEY"] = "<INSERT API KEY>"
```

5. Replace <INSERT API KEY> with your actual API key from OpenAI.

6. Save the test.py file.

7. Run the test.py file using the following command:
```
python test.py
```
8. The program will prompt you to enter a question. Type your question and press Enter.
9. To exit press ``` q ```

# License
The project is licensed under the MIT License. Feel free to use and modify the code for your own purposes.

# Disclaimer
The LangChain GPT project is an open-source project and not affiliated with OpenAI. The project uses the OpenAI GPT-3.5 language model, but any issues or questions regarding the language model itself should be directed to OpenAI.
