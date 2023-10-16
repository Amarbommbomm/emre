characters = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
password_length = int(input("Parola uzunluğunu girin: "))
password = ""
import random

for _ in range(password_length):
    random_character = random.choice(characters)
    password += random_character
print("Oluşturulan Parola:", password)
