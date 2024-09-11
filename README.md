# Simple_Toss
//Head and Tail Toss 
import random

user_input =input("Choose between Head or Tail :").lower()

print(f'Your choice is : {user_input}')

random_side = random.randint(0, 1)

if random_side == 1 and user_input == "head":
    print("Landed Head")
    print("You won the Coin Toss")

elif random_side == 1 and user_input == "tail":
    print("Landed Head")
    print("Sorry ypu lost the coin Toss")

elif random_side == 0 and user_input == "head":
    print("Landed Tail")
    print("Sorry ypu lost the coin Toss")
elif random_side == 0 and user_input == "tail":
    print("Landed Tail")
    print("You won the coin Toss")
