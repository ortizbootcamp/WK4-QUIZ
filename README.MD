This application is a quiz that challenges your javaScript knowledge! The application is timed, prompts you to start, and will reduce the time if a question is answered incorrectly. 
The quiz is 5 to 10 questions long and includes will include multiple choice - but I would like to try to experiment to see if I can include:
>Drop down (Fill in the blank)
>Open ended
>Matching

Pseudo Code:

App begins with a blurb about the 'CODE QUIZ-A-TRON' and a start button displayed.
When the user presses start, the quiz begins. The timer starts counting down as the first question is displayed.

First question will be multiple choice. The user answers, IF they get it wrong, the timer subtracts 3 seconds. IF they answer correctly, points are added to their score and the quiz moves to the next question.

Next question may be a drop down. Again, IF they get it wrong, the timer subtracts 3 seconds. IF they answer correctly, points are added to their score and the quiz moves to the next question.

Next question goes back to multiple choice. Again, IF they get it wrong, the timer subtracts 3 seconds. IF they answer correctly, points are added to their score and the quiz moves to the next question.

Next question is still multiple choice. Again, IF they get it wrong, the timer subtracts 3 seconds. IF they answer correctly, points are added to their score and the quiz moves to the next question.

Last question is a matching question or an open ended question.
User will either:
a) Match then submit - and depending on answers this will effect score after quiz is submitted
b) Match, and as they go if the wrong answer is matched, time is reduced as before
c) Answer a question with one word/string answer then submit - again this will effect score after quiz is submitted. May be case sensitive depending on the question

When all questions are answered or the timer reaches 0, the game is over, and the user will be asked to input their initials and their score will be saved.

----

COMMENTED PSEUDOCODE:

App begins with a blurb about the 'CODE QUIZ-A-TRON' and a start button displayed.
When the user presses start, the quiz begins. The timer starts counting down as the first question is displayed.
>CONSIDER:
>BUTTON FUNCTION
>TIMER FUNCTION
>QUIZ HIDDEN, THEN DISPLAYS, FADES THE BG (there is a word for this...i just forgot MODAL, IT'S A MODAL)

First question will be multiple choice. The user answers, IF they get it wrong, the timer subtracts 3 seconds. IF they answer correctly, points are added to their score and the quiz moves to the next question.
>CONSIDER:
>CORRECT VS. WRONG ANSWER
>IF WRONG, TIMER SUBTRACTS 3 SECONDS, IF RIGHT, ADD TO SCORE
>KEEPING TRACK/STORING THE SCORE
>NEXT QUESTION DISPLAY

Next question may be a drop down. Again, IF they get it wrong, the timer subtracts 3 seconds. IF they answer correctly, points are added to their score and the quiz moves to the next question.
>CONSIDER:
>DROP DOWN FUNCTIONALITY
--DROP DOWN OPTIONS
>QUESTION MAY NEED TO BE SUBMITTED, THEN CHECKED? (VS. MULTIPLE CHOICE WHICH IS CLICK AND CHECK)
>IF WRONG, TIMER SUBTRACTS 3 SECONDS, IF RIGHT, ADD TO SCORE
>KEEPING TRACK/STORING THE SCORE
>NEXT QUESTION DISPLAY

Next question goes back to multiple choice. Again, IF they get it wrong, the timer subtracts 3 seconds. IF they answer correctly, points are added to their score and the quiz moves to the next question.
>CONSIDER:
>CORRECT VS. WRONG ANSWER
>IF WRONG, TIMER SUBTRACTS 3 SECONDS, IF RIGHT, ADD TO SCORE
>KEEPING TRACK/STORING THE SCORE
>NEXT QUESTION DISPLAY

Next question is still multiple choice. Again, IF they get it wrong, the timer subtracts 3 seconds. IF they answer correctly, points are added to their score and the quiz moves to the next question.
>CONSIDER:
>CORRECT VS. WRONG ANSWER
>IF WRONG, TIMER SUBTRACTS 3 SECONDS, IF RIGHT, ADD TO SCORE
>KEEPING TRACK/STORING THE SCORE
>NEXT QUESTION DISPLAY

Last question is a matching question or an open ended question.
User will either:
a) Match then submit - and depending on answers this will effect score after quiz is submitted
b) Match, and as they go if the wrong anyswer is matched, time is reduced as before
c) Answer a question with one word/string answer then submit - again this will effect score after quiz is submitted. May be case sensitive depending on the question
>CONSIDER:
>CORRECT VS. WRONG ANSWER (FOR THIS ONE, IT MAY NOT EFFECT TIMER)
-OP1: SUBMIT FIRST THEN SCORE CALCULATED
-OP2: GRADES AS USER ANSWERS
-OP3: CHECKS STRING ANSWER (MAY BE CASE SENSITIVE, MAY HAVE VARIOUS ANSWERS), IF MATCHED IT'S CORRECT! IF NOT, WRONG

When all questions are answered or the timer reaches 0, the game is over, and the user will be asked to input their initials and their score will be saved.
>CONSIDER:
>GAME ENDS
>DISPLAY SCORE, TIME LEFT
>ASK FOR INPUT OF INITIALS
>WHEN INITIALS SUBMITTED, SCORE AND INITIALS SAVED

REFLECTION:
>Did not get much work time this week, also still struggling with some understanding of javaScript. Will work to refresh myself on everything tomorrow.

Got modal sort-of working, but want it to display one question at a time and preferably when answer is clicked, goes to next question while staying on modal if possible.

Submitting as is, though it is far from complete.