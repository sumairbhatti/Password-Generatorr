# Password-Generatorr
Password Generator
import random
import string

length = int(input("Password length: "))
password = ""

for i in range(length):
    password += random.choice(string.ascii_letters + string.digits)

print("Generated Password:", password)
