# Feuled_An_interactive_story
# Developer -- Antonio
# Date: 4-7-19
# Exact Time Of Start: 2:53 Am
# Game Name | Fueled

Warning = input("Warning: This Game is best played with Caps lock Off. . . " + "\n\nThank You! (Press Enter) ")

Name_Your = input("What is your name? ")

input("Okay " + Name_Your + "Your Cell phone is ringing. (Press Enter to Answer it) ")

answer = input("Your friend hit you up and asked you if you wanna come over for a smoke session. " + "Ready to go? (Yes / No) ")

if answer.lower().strip() == "yes":
    print("You decide that maybe a good little smoke session and some friends couldn't be so bad today.")

    answer_two = input("You grab your things and head out the door into the Ford Focus. " + "\"What an amazing day it is today,\" " + "You say to yourself silently in thought. " + "\n\nWhile driving, you notice the yellow gas light going off in your car. \"Shit I need some gas.\" You think out loud. " + "\n\n\"Can I hold out for now? \" (Yes / No)")

    if answer_two.lower().strip() == "yes":
        print("You decide to tough it out. I mean this isn't the first time this has happened before. " + "\n\nYou eventually run out of gas before getting to your friend. " + "(CTRL + F5) Try Again. . .")

    elif answer_two == "no" or "No":
        print("You decide that you have put your gas tank off for too long. " + "Luckily for you, you see two gas stations just up ahead! ")

        answer = input("Would you like to go to Gasanova Or Legasies? ")

        if answer.lower().strip() == "gasanova":

            print("You pull into the Gasanova. " + "You just noticed how full the gas station is and it frustrates you. " + "\"Okay I am the worst at picking options.\"")

            answer = input(
                "Would you like to: Circle the pumps to find an available spot or Park next to the nearest car? " + "\n\nType: (Park / Pump) ")

            if answer.lower().strip() == "pump":
                print(
                    "You circle the pumps in a slow, creepy but, understandable fashion. " + "\n\nSearching. . ." + "\n\nBut to no avail. \nYou decide to go Home, " + "leaving your friend in the dust for the 4th time in a row. \n\nHe killed himself but, you avoided the gas station situation. " + "You got the Secret win!")

            elif answer == "park":
                print(
                    "You decide to park the car instead. " + "You see a white 2016 Chevy Impala " "sitting at pump two on the far left side of the Gasanova gas station. " + "\n\nIt isn't the closest pump by far but, the owner of the white vehicle seems to be moving like there is a fire on her ass. So you pick that pump. " + "\n\nYou slowly pull up behind her and put your car in park.")

            else:
                print(
                    "You accidentally Hit a car because you're a dumb ass! " + "\n\nThe owner shot you in the temple. . . ")

        elif answer == "legasies":
            print("Path Not Available yet. . .Sorry. " + "(Press Ctrl + F5)")

        else:
            print("I guess you can't read. You lose buddy. Try again. All because you can't spell / Read. . . ")

    else:
        print("You Swerved off the road and died. ")


elif answer == "no":
    print("You tell him that you aren't really in the mood for smoking. . ." + "\n\nYou let your friend down for the 4th time this week. ")

else:
    print("I'm guessing you don't know how to fucking spell. . .Try again mother fucker. ")

    answer = input("Circle the pumps to find an available spot / Park next to the nearest car? ")

    if answer.lower().strip() == "circle the pumps" or "Circle the pumps" or "CIRCLE THE PUMPS" or "Circle The Pumps" or "Circle the Pumps":
        print("You circle the pumps in a slow, creepy but, understandable fashion. " + "\n\nSearching. . ." + "\n\nBut to no avail. You decide to go Home. . . " + "You left your friend in the dust. . .for the 4th time in a row. He killed himself but, you avoided the gas station situation. " + "You got the Secret win! ")

    elif answer == "Park" or "Park next to the nearest car" or "park next to the nearest car" or "park the car" or "Park the car":
        print("You decide to park the car instead. " + "You see a white 2016 Chevy Impala sitting at pump two on the far left side of the Gasanova gas station. " + "\n\nIt isn't the closest pump by far but, the owner of the white vehicle seems to be moving like there is a fire on her ass. So you pick that pump." + "\n\nYou slowly pull up behind her and put your car in park. ")

    else:
        print("You accidentally Hit a car because you're a dumb ass! " + "\n\nThe owner shot you in the temple. . . ")





