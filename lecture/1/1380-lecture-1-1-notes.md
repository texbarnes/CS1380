Programmability

What's the difference between a computer and a calculator?

Programmable machine



Computational thinking - put yourself in the place of the robot (computer)

^ what we need to do to get the computer to accomplish tasks for us

Could we have not just said, "go to D"?


^ robot (computer) is limited in what it can do

Computational thinking involves phrasing our instructions within the bounds of what a computer can do

- but we can build on the instructions we've made (few slides down)


What's so hard about computational thinking? Not necessarily correspond to how we humans think


Communicate instructions to the computer: write a program, programming


Characteristics of progams

**Arbitrary**

When we issued the instruction "move-up", what end state did we expect the robot to be in after completing the instruction?

Does the robot have an innate understanding of "up"?

When we told the robot to "move-up", how do you think the robot interpreted that? 

What actions would the robot have taken? Which actions correspond to the instruction "move-up"?

**Arbitrary**

Programming languages have a limited set of keywords that mean a particular thing to a computer: meaning does not necessarily correspond to what it means in English

Need to learn the vocabulary of that language, phrase our instructions using those set of words

Words that have meaning to us humans might not have meaning to computers


**Unambiguous**

Let's say we positioned our robot in the lower-left corner, and said move-left, what happens?

Any number of things: fall off the board, error, explode, do nothing

What it's not going to do, move right

**Unambiguous**

Hard for us humans because we're used to ambiguity in language, used to dealing with that

We can take ambiguous instructions and infer meaning based on context

Siri: "remind me to take out the trash later"

We'll be tempted to give ambiguous instructions and expect the computer to infer what we mean

It will only do what we say, no more, no less

When it does something unexpected, it's programmer's fault, not computer's


**Sequence**

What's the difference between answers? The two programs? 

What's the big question in our mind: What's the order of operations? What's the sequence?

**Abstraction**

What robot actions correspond to move-up? Rotation of the wheels for a fixed number of revolutions, 

write an alternative program:

all-together:
	left-front-wheel-rotate-cw
	right-front-wheel-rotate-cw
	left-front-wheel-rotate-cw
	right-front-wheel-rotate-cw


not so fun

Abstraction: very powerful - group a series of instructions and name it

Next time we need it we can just use that name

Program using the bigger pieces

Lazy - more efficient, gets work done faster

Gets more complex work done