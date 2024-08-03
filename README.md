# reverse_text
def reverse_text(text):
    return text[::-1]

# Get input from the user
user_input = input("Enter text to reverse: ")
reversed_text = reverse_text(user_input)
print("Reversed text:", reversed_text)
