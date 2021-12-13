# iNeuron-FSDS-Assignment6

1. What are escape characters, and how do you use them?

Ans: In Python strings, the backslash “ ” is a special character, also called the “escape” character. It is used in representing certain whitespace characters: “\t” is a tab, “\n” is a new line, and “\r” is a carriage return. Finally, “ ” can be used to escape itself: “\” is the literal backslash character.

2. What do the escape characters n and t stand for?

Ans: “\t” is a tab, “\n” is a new line.

3. What is the way to include backslash characters in a string?

Ans: To insert characters that are illegal in a string, use an escape character. An escape character is a backslash \ followed by the character you want to insert.

4. The string "Howl's Moving Castle" is a correct value. Why isn't the single quote character in the word Howl's not escaped a problem?

Ans: The single quote in Howl's is fine because you've used double quotes to mark the beginning and end of the string.

5. How do you write a string of newlines if you don't want to use the n character?

Ans: With triple-quoted string literals, you can use actual newlines instead of \n

6. What are the values of the given expressions?

'Hello, world!'[1]      Ans: 'e'

'Hello, world!'[0:5]    Ans: 'Hello'

'Hello, world!'[:5]     Ans: 'Hello'

'Hello, world!'[3:]     Ans: 'lo, world!'

7. What are the values of the following expressions?

'Hello'.upper()           Ans: 'HELLO'

'Hello'.upper().isupper()                   Ans: True

'Hello'.upper().lower()   Ans: 'hello'

8. What are the values of the following expressions?

'Remember, remember, the fifth of July.'.split()  

Ans: ['Remember,', 'remember,', 'the', 'fifth', 'of', 'July.']

'-'.join('There can only one.'.split())       

Ans: 'There-can-only-one.'

9. What are the methods for right-justifying, left-justifying, and centering a string?

Ans: rjust(), ljust(), Center()

10. What is the best way to remove whitespace characters from the start or end?

Ans: trimStart() or trimEnd()
