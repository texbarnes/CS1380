
# OVERVIEW of 1380 - Software Engineering

Informal recipe:
1. Set a goal.
2. Ask Questions.
3. Get Resources.
3B. Set up your environment.
4. Plan your journey.
5. Go forth!

Pursuing a goal: i.e. 200 x 200 pixel couture image
Qs: How do I fix problems when they happen? ("Debugging")
Resources: "How to Program" | Dr. Racket | Dr. Barnes | Peers ...
Environment: IDE = Dr. Racket
Plan your journey: HW # 1
Go forth: Nulla dia sine linea = No day without a line... of code!

# Going Deeper - Expressions vs. Functions

Dr. B - Class Example



; Classwork
; Dr. B

; 1. "Design Recipe"
; 2. Expressions vs. Functions (academic language)
; 3. Can we - create a function? (goal)
; 3a. Create a function that creates multiple circles;
; based on each classmate's preferences?
; 3b. Make change, given a purchase price and cash amout.
; 3c. Tip calculator.

(require 2htdp/image)

; the thing above this line can be called a "library"
; it contains the definition of the function: circle.

(circle 58 "solid" "purple") ;this is an expression!

; "circle" is an example of a function!
; Functions apparently have to be defined!
; For the expression above, "58" and "solid" are arguments!

(circle 55 "outline" "blue") ; expression example 2
(circle 58 "solid" "pink")   ; expression example 3

; How can we create a function to avoid writing
; 40 expressions for circles?

(define (stupid_y x) (* x x))
(stupid_y 1)

(* 1 1)
(* 2 2)

(stupid_y 2)
(stupid_y 3)

; the above function is for learning, and kind of dumb.

; the function below will be a world-class tip calc.
; What does our tip calc. need to know: % tip, bill

(define (tipper p b) (* (/ p 100) b))

; to test our tipper app

"To test tipper, we will pass it 20% of $8.62"

(tipper 20 8.62)

; to get the total for our tip

(define (totaltip p b) (+ (tipper p b) b))

; always create a test!

(totaltip 20 8.62)

# Sample Student Functions v1.0

; EXAMPLE 1

"Calculates a profit amount from $20 dollars after expenses of $14, $9, $6 :"
;This function will calculate the amount of profit you will have after the
; fixed amounts of expenses are taken away from the total revenue which is 20 bucks.

(define (expense x ) (- 20 x ))

(expense 14)
(expense 9)
(expense 6)       

"Expense function shows how much money will be left after the 'x' amount of expenses"
;which will give you the different amounts of profits  

; EXAMPLE 2

; homework 2 
; create your own function!
; define how much 401 k is being saved for retirement weekly->anually 

(define (401k p s)  (* (/ p 100) s))
(define (CompleteCheck p s) (- (401k p s) s))

;test

(*(CompleteCheck 1300 10.0) 54)

; EXAMPLE 3

; MY FUNCTION !!!

; Calculate the average of quiz scores

(define (Quiz a b c d) (/ (+ a b c d) 4))

; TEST - Quiz
"Average of quizzes"
(Quiz 80 99 60 85)

; EXAMPLE 4

;Budget Calculator
; t = beginning total
; s = spent
; i = any new income you may inquire

(define (Budget t s i) (+ (- t s) i))

;beginning budget of $350, spent $12 on lunch, haven't gained any more money
(Budget 350 12 0)

; EXAMPLE 5

; created 9.17.18, last modified 9.18.18

; Create a function. Purpose is to convert from centimeters to inches.
; Things needed to know:
; --Length in cm,
; --Convertion factor of cm to in (2.54 cm = 1 in).
; argument "x" defined as length in cm.

(define (cm_to_inches x) (/ x 2.54))

; The following is to test cm_to_inches

"cm_to_inches will change a length of unit cm to a length of unit inches"

(cm_to_inches 2.54)
; (cm_to_inches 500)

; EXAMPLE 6

; Finishing a book
; A book with 295 pages has to be read in a week

"Qs: how many pages should I read per day?"

(define (Pages p d) (/ p d))

(Pages 295 7)

"And if I skip a day?"

(Pages 295 6)

"I got another week to read it actually"

(Pages 295 14)

"But I need to do a report afterwards"
; I type 63 WPM and the report should be 2 pages long.
; Assuming I don´t procrastinate at all and I start my report the moment I finish the book non-stop.
"How much time will it take me to do the report"
; Assuming a page can fit 700 words.

(define (Time w s) (* (/ w s) 2)) 

(Time 700 63)

;If it really was that fast..."

"So how much time will it take me to finish reading and writing"

;The book has an average of 350 words per page.
;I read 240 words per minute.

(define (WPM t v) (* (/ t v) 295))

(WPM 350 240)
(+ 430.2083 22.2)

"That seems confusing, how about in hours"

(/ 452.4083 60)

"So basically if I were a robot I could finish in 7 hours and a half"

;In the end I wanted to make everything in just one big expression like: (/(+(* (/ t v

# Input and Output

https://docs.racket-lang.org/drracket/interactions-window.html?q=input#%28part._.Input_and_.Output%29

https://docs.racket-lang.org/drracket/interface-essentials.html?q=input#%28tech._interactions._window%29

# Sample with Input / Output

#lang racket

; (define cool (read))

"I will make a test"
"."
"."
"."
"Here is what you entered:"

; (display cool)(newline)

"This is time passing..."
"."
"."
"Information is being stored..."
"."
"."
"I'll reveal it again when I feel like it:"

;(display cool)(newline)

; How can we apply this new power?
; Maybe at the movies?

"How many people do you have in your group?"

; (define people (read))

"How many are under the age of 7.5?"

; (define kids (read))

"Adult tickets - anyone over 7.5 - are $10."
"Kids tickets - anyone under 7.5 - are $3."

; (display (+(* 10 (- people kids)) (* 3 (kids))))

"Confirm you have this many people:" ; (display people)

"."

"."


; This function learns your name, then unjinxes you if you ever get jinxed.

"Please tell me your name, so I can unjinx you."

(define yourname (read))

"Hello:" (display yourname)

" "

"Okay here goes:"
(newline)
"Silly-" (display yourname)
(newline)
"Funny-" (display yourname)
(newline)
"Happy-" (display yourname)

"Am I there yet? Y/N"
