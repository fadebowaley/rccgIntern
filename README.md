# Simple CLI Chatbot

This is a simple chatbot built with Python that interacts with users through the command line interface (CLI). It asks the user for their name and responds with a greeting.

## Features

- Prompts the user for their name.
- Greets the user by name.

## Prerequisites

- Python 3.x installed on your machine.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/simple-cli-chatbot.git

Navigate to the project directory:


cd simple-cli-chatbot

# Usage
Run the chatbot:

python chatbot.py
Interact with the chatbot:

The chatbot will ask for your name.
After entering your name, it will greet you with a personalized message.
Example

```
$ python chatbot.py
Hello! What's your name?
> Frank
Nice to meet you, Frank!
```

# Code Explanation
The chatbot is implemented in a single Python file, chatbot.py. Here's a brief overview of the code:

python
Copy code
def main():
    name = input("Hello! What's your name?\n> ")
    print(f"Nice to meet you, {name}!")

if __name__ == "__main__":
    main()
main(): This function prompts the user for their name and then prints a greeting.
The script is run directly if executed as the main module.
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.



This `README.md` file provides an overview of the project, instructions for setup, and a brief explanation of how the chatbot works.





