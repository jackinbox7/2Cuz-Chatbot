import random

print("Hello! We’re 2Cuz. Type 'bye' to exit.\n")

# Responses grouped by intent, with different responses
greeting_responses = [
    "Hibatron: Hola Amigo ",
    "Rosh2D2: Hello! Im 2nd generation Rosheenbotic Droid series-2 and I like cheese",
]

greet_responses = [
    " Rosh2D2: I'm doing great!.",
    " Hibatron: I'm fine, thank you."
]

fallback_responses = [
    " Hibatron: Sorry, I cant respond to that yet.",
    " Rosh2D2: Request denied.",
    " Rosh2D2: Idk bro, I’m just a 5‑mark project ."
    " Rosh2D2: Go ask Chatgpt that lol.",
]

joke_responses = [
    " Rosh2D2: Why don't scientists trust atoms? Because they make up everything! ",
    " Rosh2D2: What do you call fake spaghetti? An impasta! ",
    " Rosh2D2: Why did the scarecrow win an award? Because he was outstanding in his field! ",
    " Hibatron: Why did the math book look sad? Because it had too many problems.",
    " Hibatron: What do you get when you cross a snowman and a vampire? Frostbite!",
    " Hibatron: Why don’t skeletons fight each other? They don’t have the guts."
    " Hibatron: Why was 6 scared of 7? Because 7 8(ATE) 9."

]


while True:
    user_input = input("You: ").lower()

    if user_input in ["hi", "hello", "hey"]:
        print(random.choice(greeting_responses))
elif "joke" in user_input:
        print(random.choice(joke_responses))
elif "how are you" in user_input:
        print(random.choice(greet_responses))
elif "weight" in user_input:
        print("Rosh2D2: Stop eating fatty 🙄")
elif "strongest robot" in user_input:
        print("Hibatron: Meg, short for Megatron, Peter Griffin's daughter")
elif "vector" in user_input:
        print("HIbatron: I have no clue bro, I'm an arts student for a reason.")
    elif "bye" in user_input:
        print("2Cuz: Goodbye from the both of us. ")
        break
    else:
        print(random.choice(fallback_responses))
