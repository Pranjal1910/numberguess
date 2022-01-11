import random
num = random.randint(1, 10)
guess = None

while guess != num:
    guess = input("guess a number between 1 and 10:")
    guess = int(guess)

    if guess == num:
         print("Congrats, Your Guess was right")
         break
    else:
        print("nope your guess was wrong,try again")












##Try It IN VISUAL STUDIO CODE
