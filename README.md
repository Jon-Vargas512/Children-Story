# Children-s-Story


def story():
    print("Once upon a time, there was a little bunny named Hoppity.")
    print("Hoppity loved to explore the forest, but he wasn't always careful to stay on the correct path.")
    print("One day, as he was hopping along through the woods, he came across three different paths.")
    print("The first path led to a dark and eerie cave, the second path led to a beautiful and bright field, and the third path to a tree with a beehive")
    choice = input("Which path will Teddy take? Type 1 for the eerie cave, 2 for the beautiful field, or 3 for the beehive: ")
    if choice == "1":
        print("Hoppity decided to explore the eerie cave.")
        print("As he explore and hopped deeper into the cave, bats flew by his face and rats scurried across is feet.") 
        print("He got deeper and deeper into the cave and as he did, the cave got darker and darker.")
        print("Then, all of a sudden he saw a sparkle in the distance...")
        print("'What could this be?' he said to himself.")
        print("It was a treasure chest filled with gold and jewels!")
        print("Teddy was overjoyed at his discovery and returned home with his treasure.")
    elif choice == "2":
        print("Teddy decided to explore the meadow.")
        print("As he walked, he saw a butterfly fluttering nearby.")
        print("He followed it and it led him to a beautiful flower garden.")
        print("Teddy picked some flowers and returned home, feeling happy and content.")
    elif choice == "3":
        print("Teddy decided to explore the beehive.")
        print("As he walked to the beehive, he saw it was full of honey.")
        print("Teddy took some honey and went home, feeling sweet.")
    else:
        print("Invalid choice. Teddy went home and cried.")

story()
