import random
import string

#the yesno is a function to ask, yes or no <3

def generate_password(length: int = 25):
    alphabet = string.ascii_letters + string.digits + string.punctuation
    password = ''.join(random.choice(alphabet) for i in range(length))
    return password

#here I learned about .strip() removing spaces from the beggining or end 
yesno = input("Hello, would you like a password? Please type Yes or No: ").strip()
if yesno.lower() == "yes":
    password = generate_password()
    print(f"Here is your big ol password!: {password}")
    exit()
if yesno.lower() == "no":
    print("No password for you")
    exit()
else:
    print("That wasnt a good input and you know it, try again")
