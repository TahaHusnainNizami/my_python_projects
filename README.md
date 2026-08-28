import random

def game():
    lucky_no = random.randint(1, 50)

    while True:
        user_no = int(input("Enter number: "))

        if user_no == lucky_no:
            print("You won the game!!!")
            break
        elif user_no > lucky_no:
            print("Too high")
        else:
            print("Too low")

game()
