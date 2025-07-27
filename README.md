# UA
import random

responses = {
    "hi": "Hello! Kamusta ka?",
    "kamusta": "Okay lang ako, ikaw?",
    "anong pangalan mo": "Ako si AI Assistant mo!",
    "bye": "Paalam! Ingat ka!",
}

def chatbot():
    print("AI Chatbot: Kumusta! Pwede kang magtanong.")
    while True:
        user_input = input("Ikaw: ").lower()
        if user_input in responses:
            print("AI:", responses[user_input])
        elif user_input == "exit":
            print("AI: Sige, bye!")
            break
        else:
            print("AI: Pasensya na, di ko maintindihan.")

chatbot()
