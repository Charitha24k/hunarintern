
# Simple Rule-Based Chatbot

def chatbot():
    print("Chatbot: Hi! I am a simple chatbot. Type 'exit' to end the conversation.")
    
    while True:
        user_input = input("You: ").lower()

        if user_input == "hello" or user_input == "hi":
            print("Chatbot: Hello there! How can I help you today?")
        
        elif "your name" in user_input:
            print("Chatbot: I'm RuleBot, your friendly assistant.")

        elif "how are you" in user_input:
            print("Chatbot: I'm just a bunch of code, but I'm functioning as expected!")

        elif "help" in user_input:
            print("Chatbot: I can help with basic questions like greetings, my name, and how I'm doing.")
        
        elif "bye" in user_input or "exit" in user_input:
            print("Chatbot: Goodbye! Have a nice day!")
            break
        
        else:
            print("Chatbot: Sorry, I don't understand that. Can you try something else?")

# Run the chatbot
chatbot()
