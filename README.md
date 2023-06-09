# Virtual Assistant

This is a virtual assistant program implemented in Python. It utilizes natural language processing (NLP) techniques to interpret user commands and perform various tasks. The virtual assistant is capable of answering questions, providing information, performing web searches, and executing system commands.

## Features

- **Speech Recognition**: The virtual assistant can understand voice commands using the SpeechRecognition library.
- **Text-to-Speech**: It can respond to user queries by converting text to speech using the pyttsx3 library.
- **Web Search**: The virtual assistant can perform web searches using the requests library and retrieve information from the web.
- **System Commands**: It can execute system commands, such as opening applications or files, using the os library.


## Installation

1. Clone the repository:

```
git clone https://github.com/abhisheklahase29/virtual-assistant.git
```

2. Change into the project directory:

```
cd virtual-assistant
```

3. Install the required dependencies:

```
import speech_recognition as sr
import pyttsx3
import pywhatkit
import datetime
import wikipedia
import pyjokes
from AppOpener import open
```

4. Run the virtual assistant:

```
python virtual_assistant.py
```

## Usage

Once the virtual assistant is running, it will listen for user commands. You can interact with it using your voice . Here are some example commands:

- **"Who is elon musk ?"**: Asks the assistant about celebrities.
- **"Search for cats on the web"**: Performs a web search for cats.
- **"Open Notepad"**: Opens the Notepad application.
- **"Play some music"**: Plays a random selection of music.

Feel free to explore and customize the program to suit your needs!

## Customization

You can customize the virtual assistant by modifying the existing modules or adding new ones. Here's a brief overview of the project structure:

- **virtual_assistant.py**: The main script that handles user input, performs NLP, and executes appropriate actions.
- **modules**: This directory contains various modules that define the assistant's capabilities. You can modify or add modules to extend its functionality.
- **utils.py**: Utility functions used by the virtual assistant.

To add a new module, follow these steps:

1. Create a new Python file in the `modules` directory, such as `my_module.py`.
2. Implement the necessary functions to handle user commands in the new module.
3. Import the new module in `virtual_assistant.py` and add it to the list of available modules.
4. Update the NLP logic in `virtual_assistant.py` to recognize and execute commands for the new module.

## Contributions

Contributions to this virtual assistant project are welcome! If you find any issues or have ideas for improvements, please open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as per the terms of the license.
