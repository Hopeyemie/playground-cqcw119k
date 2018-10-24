import random

chars='qwertyuioplkjhgfdsazxcvbnmQWERTYUIOPLKJHGFDSAZXCVBNM!@#$%^&*()_+}{:"|?><,./\;[]=-'
length=input('password length')
length=int(length)
amount=input('How many passwords do you want?:')
amount=int(length)
for p in range(amount):
    password=''
    for c in range(length):
        password += random.choice(chars)
    print(password)

