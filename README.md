- Open main01.py. Before running it, what do you expect this program to do?
Greet the user, and then ask their favorite color.
  - Now right click on the main1.py window and select “Run Python File in Terminal”. Click in the bottom panel, and answer the question. Describe what happened.
The program said "Greetings!" and then asked my favorite color. It ended after I input "red."
  - What do you think the program did with what you typed in answer to the question?
I don't think it did anything with the response.
- Open main02.py. Before running it, describe how this is different than main01.py.
It responds with your favorite color after it asks what it is, instead of doing nothing with the response.
  - What do you think the color = input() will do?
it sets the color variable to the color you input
  - Run the program in the terminal and answer the question. Did the program do what you expected?
It did do what I expected.
- Open main03.py. Before running it, describe how this is different than main02.py.
It has a correct answer, and has multiple potential responses.
  - What is happening on lines 9–12?
It's checking to see if you put in "red." If you did, it says you're correct, if you don't, it doesn't.
  - Why are lines 10 and 12 indented?
because of the if else statement
  - Run the program and answer the question. What happens if you don’t capitalize Red?
It thought you were wrong.
  - What does this tell you about "color"?
it's a case sensitive variable
- Open main04.py. Before running it, describe how this is different than main03.py.
it accounts for red being lowercase as well as being capitalized
  - What problem is this trying to solve?
"red" being an incorrect response in the previous program
  - Run the program and answer the question. What happens if you use some other capitalization scheme (i.e., “RED” or “reD“)?
It doesn't understand you again, and thinks you're wrong.
- Open main05.py. What do you expect line 9 to do?
make your response lowercase and check it against "red"
  - What problem is it trying to solve?
responses like "rED" and "rEd" not working even though it's technically correct
  - Run the program and answer the question. What happens if you add spaces before or after the word (i.e., “ RED “ or “ red”)?
It's back to not understanding your response and thinking you're wrong.
 - Open main06.py. How is line 9 different than in main05.py?
It takes all of the spaces out of the response as well as lowercasing it.
   - What would you guess .strip() is doing?
getting rid of spaces before or after the response
   - Run the program and answer the question. Is there another way of writing “red” that will break this logic?
adding a period to the end, or any punctuation.
 - Open main07.py. Before running this program, how do you expect this to be different than main06.py?
It has more than 2 responses. If the input is pink then it says "close!" instead of saying you're wrong.
   - What is happening on line 12?
it's like a secondary if, for if the response is pink.
   - Run the program and answer the question.
red said correct, pink said close, everything else says wrong.
 - Open main08.py. What is the purpose of line 9?
The line is for while the "color" variable is NOT red, it will repeat the code underneath it until "color" IS red.
   - Why are lines 10–17 indented?
It's contingent on line 9.
   - Run the program. What would happen if line 10 were moved before line 9 (and no longer indented)?
It would break the program. It would end after the input.
   - Make that change and run the program again. (To end any Python program, you can type ctrl-c)
It died.
 - Open main09.py. What is happening on line 13?
It's keeping track of how many guesses you make via the variable "count"
   - What is the purpose of “count”?
It keeps track of your guesses
   - What is happening on line 22?
there... is no line 22?
   - Run the program.
it kept track of my guesses and told me how many i took at the end of the program.
 - *Extra credit:* open main10.py. Add a comment to each line describing what it is doing (a comment follows a pound sign [#]).
 - *Extra credit:* open main11.py. What is happening on lines 6-11?