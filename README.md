import random
target=random.randint(1,100)
while True:
    userchoice=int(input("guess the target:"))
    if(userchoice==target):
        print("success:corret guess!!")
        break
    elif(userchoice<target):
        print("your number was to small.take a biger guess...")
    else:
        print("your number was to biger.take a small guess...")

print("_________GAME OVER_________")        
