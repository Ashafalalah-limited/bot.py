# 🤖 AI Learning Bot

This is a simple Python chatbot that asks students quiz questions and responds with feedback.

## 🧠 Features
- Greets the user
- Asks a learning question
- Checks user input
- Gives feedback

## 🔧 Technologies
- Python

## 🏁 Getting Started
To run the bot:
```bash
while True:
    print("Welcome to AI Learning Bot!")
    name = input("What's your name? ")
    print(f"Hello, {name}! Let's learn something new today.")

    question = "What is the capital of Nigeria?"
    answer = input(f"{question}\nYour answer: ")

    if answer.lower() == "abuja":
        print("✅ Correct! You're smart!")
    else:
        print("❌ Oops, the correct answer is Abuja.")
