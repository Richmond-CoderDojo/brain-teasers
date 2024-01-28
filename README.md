# brain-teasers
Ideas and code for coding brain teasers

## Number based challenges

### Palindrome Checker
Palindromes are words that read the same forwards and backwards. For example, "mom" or "mum" is a palindrome, and so is "radar"  
Your challenge is to create a program that takes one word and can check if the word you give it, is a palindrome or not!  
For example  
- If you give it "mum" it should say "It's a palindrome!"
- If you give it "radar" it should say "It's a palindrome!"
- If you give it "school" is should say "Sorry! Not a palindrome"

### Prime Number Generator
Prime numbers are positive numbers that can only be divided by the number itself, or by 1.  
You challenge, is to create a program that can generate a list of prime numbers! You program will take a number, and will generate all the prime numbers less or equal to that number  
For example
- If you give it 5, it should say "2 3 5"
- If you give it 10, it should say "2 3 5 7"
  
*Hint*: Sieve of Eratosthenes is an algorithm that might be helpful :)

### Fibbonacci Sequence Generator
Fibbonacci sequence is a famous number sequence, in which the next number in the sequence, is the sum of the last two numbers.  
The sequence always starts with 1 and 1, so "1 1"  is the starting sequence, with 2 digits.
Then the next number will be "[1 + 1]" = 2. So the sequence is now "1 1 2", with 3 digits.  
Then the next number will be "1 [1 + 2]" = 3. So the sequence is now "1 1 2 3" with 4 digits.  
Then the next number will be "1 1 [2 + 3]" = 5. So the sequence is now "1 1 2 3 5" with 5 digits.  
Then the next number will be "1 1 2 [3 + 5]" = 8. So the sequence is now "1 1 2 3 5 8" with 6 digits.    
  
Your challenge is to create a program, that takes the number of digits in your sequence, and generates the full sequence with as many digits!  
For example
- If you give it 2 it should say "1 1"
- If you give it 3 it should say "1 1 2"
- If you give it 6 it should say "1 1 2 3 5 8"

*Hint* Recursion is your friend here! Read up online for more info  

### Money Coin Change Generator
When buying something from a shop, often times the shopkeeper will return some "change" when you pay more than the price of the item.  
One problem they face, is how to give back the change with as few coins or notes as possible! You wouldn't want twenty one-pound coins instead of a single 20 pound note!
    
The available bank notes and coins to shopkeepers are
- 20 pound note
- 10 pound note
- 5 pound coin
- 2 pound coin
- 1 pound coin
  
Your challenge, is to create a program that takes a single number (the amount of change) and tells you which types of bank notes / coins (and how many) the shopkeeper should give back.  
For example  
- If you give it 10 pound change, it should say "(1) 10 pound note"
- If you give it 12 pound change, it should say "(1) 10 pound note, (1) 2 pound coin"
- If you give it 7 pound change, it should say "(1) 5 pound coin, (1) 2 pound coin"
- If you give it 9 pound change, it should say "(1) 5 pound coin, (2) 2 pound coin"
- If you give it 19 pound change, it should say "(1) 10 pound note,  (1) 5 pound coin, (2) 2 pound coin"


## Game based challenges

### Guess the Number!
In this game, your program will generate a random number between 1 and 100 and then ask the player to guess the number!  
If the player guesses it correctly, your program should say "Well done! you guessed correctly!"
If the player was incorrect, it should give hints like "too high" or "too low" or "a bit high" or "a bit low" etc.  

Your program should give the player 5 attempts, and if they can't guess correct in 5 attempts, your program should say "Oops! No more chances! Better luck next time!"

*Note* For an extra challenge, let the player choose the smallest and biggest number instead of just using 1 and 100

### Mad Libs Generator
In this game, your program will have a few simple sentences, consisting of a noun, object, verb, adjective etc. However you will let the user choose the noun, the object, the verb etc.  
Your program should ask for each type of word at a time for example "Enter the noun" or "Enter the adjective" or "Enter the verb"  
Once you have all the words you need, pick any sentence at random from your list, and fill in the blanks with the words the player entered to create a funny sentence or story!
Remember to print your sentence for the user to read in the end!  

For example
Sentence: "(noun) likes to (verb) the (adjective) (object)"
User enters: (noun) = King Henry, (verb) = eat, (adjective) = smelly, (object) = pizza  

Your program should print "King Henry likes to eat the smelly pizza"! 
