#simple madlib game
def madlib_game():
    print("Welcome to the Mad Libs Game!")
    # Collect words from the user
    adjective = input("Enter an adjective: ")
    noun = input("Enter a noun: ")
    verb = input("Enter a verb: ")
    adverb = input("Enter an adverb: ")
    number = input("Enter a number: ")
    animal = input("Enter an animal: ")
    adjective_2 = input("Enter another adjective: ")
    plural_noun = input("Enter a plural noun: ")
    verb_past_tense = input("Enter a verb in past tense: ")
    adjective_3 = input("Enter one more adjective: ")
    event = input("Enter an event: ")
    code_word = input("Enter a code word: ")

    # Display the mad libs story with a secret code
    print("\nMad Libs Story:")
    print(f"Once upon a time, there was a(n) {adjective} {noun} who loved to {verb} {adverb}.")
    print(f"One day, {number} {animal}s appeared and stole all the {adjective_2} {plural_noun}.")
    print(f"The {noun} {verb_past_tense} {adjective_3} to save the day and restore peace to the {event}.")
    print(f"To communicate, they used the secret code word: {code_word}.")
madlib_game()
