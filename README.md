# cs4395-assignment-3-word-guess-game-solved
**TO GET THIS SOLUTION VISIT:** [CS4395 Assignment 3-Word Guess Game Solved](https://www.ankitcodinghub.com/product/cs4395-assignment-3-word-guess-game-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98785&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4395 Assignment 3-Word Guess Game Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Word Guess Game

</div>
</div>
<div class="layoutArea">
<div class="column">
Use Python and NLTK features to explore a text file and create a word guessing game

Turn in:

<ul>
<li>Upload your .py code to eLearning for grading</li>
<li>Upload your .py code to your portfolio, and create a link to on your index page</li>
<li>This program should be written with an IDE so that it can be run interactively
Instructions:
</li>
</ul>
<ol>
<li>Download the anat19.txt file from the GitHub and save it in the same folder as your Python program. The file is the text from one chapter of an anatomy textbook. Send the filename to the main program in a system argument. If no system arg is present, print an error message and exit the program.</li>
<li>Read the input file as raw text. Calculate the lexical diversity of the tokenized text and output it, formatted to 2 decimal places. Lexical diversity is the number of unique tokens divided by the total number of tokens. Lexical diversity indicates the richness of vocabulary in a text. For example, a lexical diversity of 0.05 means that 5% of the words in a text are unique. See this notebook in the GitHub for an example: https://github.com/kjmazidi/NLP/blob/master/Part_2- Words/Chapter_05_words/5.1_Words1.ipynb</li>
<li>Write a function to preprocess the raw text:

a. tokenize the lower-case raw text, reduce the tokens to only those that are alpha, not in

the NLTK stopword list, and have length &gt; 5

b. lemmatize the tokens and use set() to make a list of unique lemmas

c. do pos tagging on the unique lemmas and print the first 20 tagged items (see the

pos_NLTK notebook in Part 2 Chapter 6 of the GitHub)

d. create a list of only those lemmas that are nouns

e. print the number of tokens (from step a) and the number of nouns (step d) f. return tokens (not unique tokens) from step a, and nouns from the function
</li>
<li>Make a dictionary of {noun:count of noun in tokens} items from the nouns and tokens lists; sort the dict by count and print the 50 most common words and their counts. Save these words to a list because they will be used in the guessing game.</li>
<li>Make a guessing game function:

a. give the user 5 points to start with; the game ends when their total score is negative, or</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Caution:
students’
</pre>
</div>
<div class="column">
they guess ‘!’ as a letter

b. randomly choose one of the 50 words in the top 50 list (See the random numbers

notebook in the Xtras folder of the GitHub)

c. output to console an “underscore space” for each letter in the word d. ask the user for a letter

All course work is run through plagiarism detection software comparing work as well as work from previous semesters and other sources.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
CS 4395 Intro to NLP Dr. Karen Mazidi

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="5">
<li>if the letter is in the word, print ‘Right!’, fill in all matching letter _ with the letter and add 1 point to their score</li>
<li>if the letter is not in the word, subtract 1 from their score, print ‘Sorry, guess again’</li>
<li>guessing for a word ends if the user guesses the word or has a negative score</li>
<li>keep a cumulative total score and end the game if it is negative (or the user entered ‘!’)
for a guess
</li>
<li>right or wrong, give user feedback on their score for this word after each guess</li>
</ol>
6. Create a link to this document on your index page

Note: Feel free to make tweaks to the game to customize it, as long as it has the basic functionality. In other words, you can make a better version of this game if you want.

Sample run of the game:

Let’s play a word guessing game! ______

Guess a letter:e

Right! Score is 6

_e__e_

Guess a letter:a

Sorry, guess again. Score is 5 _e__e_

Guess a letter:i

Sorry, guess again. Score is 4 _e__e_

Guess a letter:u

Sorry, guess again. Score is 3 _e__e_

Guess a letter:o

Sorry, guess again. Score is 2 _e__e_

Guess a letter:t

Sorry, guess again. Score is 1 _e__e_

Guess a letter:s

Right! Score is 2

_esse_

Guess a letter:m

Sorry, guess again. Score is 1 _esse_

Guess a letter:l

Right! Score is 2

_essel

Guess a letter:v

Right! Score is 3

vessel

You solved it!

Current score: 3

Caution: All course work is run through plagiarism detection software comparing students’ work as well as work from previous semesters and other sources.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
CS 4395 Intro to NLP

</div>
<div class="column">
Dr. Karen Mazidi

</div>
</div>
<div class="layoutArea">
<div class="column">
Guess another word

________ Guess a letter:

</div>
</div>
</div>
