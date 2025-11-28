# 2Cuz Chatbot

## Overview
**2Cuz Chatbot** is a beginner‑friendly Python project that simulates a simple conversational agent with multiple personalities. The chatbot responds to user inputs with randomized answers from two fictional characters — *Hibatron* and *Rosh2D2*. It demonstrates basic concepts of rule‑based AI, randomness in responses, and interactive text‑based communication.

This project was designed as a first‑semester AI/ML assignment worth 5 marks, focusing on clarity, simplicity, and creativity rather than complex algorithms.

---

## Features
- Responds to greetings (`hi`, `hello`, `hey`) with randomized character replies.
- Provides jokes on request (`joke` keyword).
- Answers simple queries like *"how are you"* or *"strongest robot"*.
- Random fallback responses when input doesn’t match any rule.
- Multiple personas (Hibatron and Rosh2D2) to make conversations more engaging.
- Easy to extend by adding new rules and responses.

---

## Technologies / Tools Used
- **Python 3.x** – Core programming language.
- **Random module** – For selecting randomized responses.
- **Command Line / Terminal** – For user interaction.

---

## Steps to Install & Run
1. **Install Python**  
   - Ensure Python 3.x is installed on your system.  
   - You can check by running:  
     ```bash
     python --version
     ```

2. **Download the project file**  
   - Save the chatbot code in a file named `chatbot.py`.

3. **Run the chatbot**  
   - Open your terminal/command prompt.  
   - Navigate to the folder containing `chatbot.py`.  
   - Run the program:  
     ```bash
     python chatbot.py
     ```

---

## Instructions for Testing
- After running the program, type your inputs at the `You:` prompt.
- Try the following test cases:
  - **Greeting:**  
    ```
    You: hi
    ```
    → Random greeting from Hibatron or Rosh2D2.
  - **Joke:**  
    ```
    You: tell me a joke
    ```
    → Random joke response.
  - **How are you:**  
    ```
    You: how are you
    ```
    → Random response about well‑being.
  - **Fallback:**  
    ```
    You: what is ai
    ```
    → Random fallback response (e.g., "Idk bro, I’m just a 5‑mark project").
  - **Exit:**  
    ```
    You: bye
    ```
    → Program ends with a goodbye message.

---

## Notes
- This chatbot is rule‑based and does not use machine learning.  
- It is intended as a simple demonstration project for beginners in AI/ML.  
- You can expand it by adding more intents, responses, or even integrating audio playback for recorded voices.
