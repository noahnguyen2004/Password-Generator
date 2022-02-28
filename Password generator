# Password Generator
import random
letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']
numbers = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9']
symbols = ['!', '#', '$', '%', '&', '(', ')', '*', '+']


nr_letters = int(input("Desired number of letters\n"))
nr_symbols = int(input(f"Desired number of symbols\n"))
nr_numbers = int(input(f"Desired number of numbers\n"))

randomletters = ""
for letterloop in range(0, nr_letters):
    rand_int_letters = random.randint(0, letterloop)    # loop through the letterloop each time
    rand_int_letters = random.randint(0, 50)            # random inside random (random one more time)
    randomletters += letters[rand_int_letters]          # to get the string of all random letters inside letter list

randomsymbols = ""
for symboloop in range(0, nr_symbols):
    rand_int_symbol = random.randint(0, symboloop)      # loop through the symboloop each time
    rand_int_symbol = random.randint(0, 8)             # random inside random (random one more time)
    randomsymbols += symbols[rand_int_symbol]           # to get the string of all random symbols inside symbol list

randomnumbers = ""
for numberloop in range(0, nr_numbers):
    rand_int_numbers = random.randint(0, numberloop)
    rand_int_numbers = random.randint(0, 9)
    randomnumbers += numbers[rand_int_numbers]

password = randomletters + randomsymbols + randomnumbers
shuffle_password = ''.join(random.sample(password, len(password)))

print(shuffle_password)







