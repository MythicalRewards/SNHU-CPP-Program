# SNHU-CPP-Program
For the journal submission for module eight, I chose the final project as the project to upload.  Essentially in this project, I was tasked with creating a program that will accepts four user inputs and a file containing full words.  Each line in the file contained only one word.  If the user chose option one, the program ask the user to input a word they wished to see how frequently it was in the file.  The program would then read through the file and foutput the word along with the number of times it appeared in the file.  If the user chose two, the program would go through the file and output every word in the file and how many times it appeared.  If they user chose three, the program would do the same thing as option two, but instead of printing the numbers of times a word appeared right next to the word, it would print out a number of atricks that match to the number of times said word appeared.  If the user chose option four, the program would exit out.

## What did you do particularly well?
I did not do anything specifically well in this project, besides challenging myself on using different techniques I was used to, such as using switch statements, how a parsed through the file for the frequencies of words, etc.

## Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
In terms of security, the code is pretty secure.  As for efficient code, the code could be optmized more.  Each time there are nested for-loops, the runtime is in quadratic time.  There is probably a different way to parse through the file that's better and faster, but I am not sure at the top of my head. At the very least, I know my code is certainly not the fastest, however, I did try not to bog down the program with loading the whole file into a vector.

## Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?
Honestly, the hardest part to write was the fine tuning of the algorithm that found the word to word frequency.  There were times that the code would repeat the word twice.  The counts were right, I just needed to find the right condiational expressions to correct this.


## What skills from this project will be particularly transferable to other projects or course work?
As I stated above, I tried to write this project using a different logic thinking style.  This was not a difficult problem.  But I wamted to stretch my thinking muscles a bit and see if I could make an alternative way work, because a person who only programs in one way, will never understand the thinking of another.


## How did you make this program maintainable, readable, and adaptable?
THis program is adatable and programmable, because the memory useage is safe.  If the file is a terabyte in size, the program would still contain the same amount of memory because the file is not being stored in a vector or anything.  And The program has condtional expressions that handle unexpected user input.  The only thing that is not completely dynamic is the file structure.  If the user uses a file with two words on a single line, it will not parse correctly using the cin statements I used.  But this could be easily fixed with using the getline method and parsing through the entire line in the file.  It is readable because I used in line comments to explain what was happening in the file.
