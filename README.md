# INST126-Hangman-Game

**START

1. **Python picks a random word from the list of words

    from the selected word, it will tell users the length of the word picked
    user have 10 wrong turns before they loose
    right guesses will be stored in the "right" list
    wrong guesses will be stored in the "wrong" list
    
2. **For the right guess:

it will create space for the user and add paranthesis to the letter. And for each guess, it will create a line to space out the outputs

3. **If the guessed letter by the user is in the picked word:

      it will tell users the letter is correct
      it will add letter to the "right" list and on the dashes in the order of the picked word
      
4. **If the guess from the user is wrong:

        turns will be subtracted by 1
        guessed letter will be added to the "wrong" list
        it will tell users the remaining amount of turns left
  
5. **If user guesses the same wrong letter again:

        tells user they have already guessed that
        will print the "wrong" list so far of all inputs from user
       
6. **If user uses all of his turns:

        It will tell the user they lost and the word that was picked
        break

7. **If user guesses all correct letters in picked word:
      It will tell the user they won
      it will tell the user that the picked word was encrypted
      it will tell the user the decryption of the picked word
      break
      
**END
user can choose to play again 
