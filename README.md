# Children-s-Story


def story():
    print("Once upon a time, there was a little bunny named Hoppity.")
    print("Hoppity loved to explore the forest, but he wasn't always careful to stay on the correct path.")
    print("One day, as he was hopping along through the woods, he came across three different paths.")
    print("The first path led to a dark and eerie cave, the second path led to a beautiful and bright field, and the third path to a tree with a honey-comb")
    choice = input("Which path will Hoppity take? Type 1 for the eerie cave, 2 for the beautiful field, or 3 for the honey-comb: ")
    if choice == "1":
        print("Hoppity decided to explore the eerie cave.")
        print("As he explore and hopped deeper into the cave, bats flew by his face and rats scurried across his feet.") 
        print("He got deeper and deeper into the cave and as he did, the cave got darker and darker.")
        print("Then, all of a sudden, he saw a sparkle in the distance...")
        print("'What could this be?' he said to himself.")
        print("It was a treasure chest filled with gold and jewels!")
        print("Hoppity was overjoyed at his discovery and returned home with his treasure.")
    elif choice == "2":
        print("Hoppity decided to explore the meadow.")
        print("As he walked, he saw a butterfly fluttering nearby.")
        print("He followed it and it led him to a beautiful flower garden.")
        print("Hoppity picked some flowers and returned home, feeling happy and content.")
    elif choice == "3":
        print("Hoppity decided to explore the honey-comb.")
        print("As he walked to the beehive, he saw it was full of honey.")
        print("Hoppity took some honey and went home, feeling sweet.")
    else:
        print("Invalid choice. Hoppity went home and cried.")

story()
