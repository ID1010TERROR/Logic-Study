Below are my self-study notes in the realm of logic.

#Overview
Logic is the study of **Correct Reasoning** in that it attempts to use a set of principles governing the validity of a given argument or set of arguments. This includes the use of **Truth Tables**, **Binary Operators**, **Syllogisms**, etc to determine the validity of a given argument.

#Terms

###Statements
Sentences (AKA **Premises**) that are either True or False but not both. For example: 

> 1 is an odd number 

> 3 is an even number

The first statement is True, while the second statement is False

###Logical Operations
Statements can be combined or modified using Logical Operations via Logical Operators such as NOT, AND, OR, XOR, etc.

###Deductive Reasoning
The process of reasoning from one or more premises(statements) to reach a logically certain conclusion.

###Valid
An argument is said to be "Valid" if it is impossible for its premises to be true while it's conclusion is false, meaning the conclusion must be true, if the premises are true.

###Sound
An argument is said to be "Sound" if it is valid AND the premises are true. An argument can be Valid without being sound for example:

1. Everyone who eats bannanas is a monkey
2. Jane eats bannanas
3. Therefore Jane is a Monkey

This is an example of a logically valid argument that is unsound.

###Rules of Inference or Syllogisms
In logic a rule of inference (AKA **Syllogism**) is a logical form consisting of a function which takes premises, analyzes their syntax and returns a conclusion or conclusions using deductive reasoning.

#Logical Operator Truth Tables

## ~ or ! = NOT

| A | ~A |
|---|----|
| T | F  |
| F | T  |

The operation "Not" is the simplest logical operation, its sole purpose is to "flip" the Truth of a given statement. Converting True statements to False statements and False statements to True statements.

The statement 'NOT P' is said to be the **Negation** of P. 

## ^ = and

| A | B | A ^ B |
|---|---|:-----:|
| T | T |   T	|
| T | F |   F   |
| F | T |   F	|
| F | F |   F	|

If given two statements A AND B, the argument is said to be True when A AND B are both true, and false otherwise. 


## v = or

| A | B | A v B |
|---|---|:-----:|
| T | T |   T	|
| T | F |   T   |
| F | T |   T	|
| F | F |   F	|

When given the logical form 'A OR B', it is said to be true when A is True or B is True or when A AND B are True, and it is said to be false when both A AND B are False.

## | = NAND

| A | B | A \| B |
|---|---|:-----:|
| T | T |   F	|
| T | F |   T   |
| F | T |   T	|
| F | F |   T	|


##--> = If then/Implies

Implies means "if A is True then B is also True"

| A | B | A --> B |
|---|---|:-------:|
| T | T |    T    |
| T | F |    F    |
| F | T |    T	  |
| F | F |    T    |

When given the argument 'If P then Q', the argument is said to be true when A and B are both True or A is False. It is said to be false when A is True and B is False.

##<--> = If and only if

If and only if means "if A is True (and ONLY True) then B is also True"

| A | B | A <--> B |
|---|---|:--------:|
| T | T |     T    |
| T | F |     F    |
| F | T |     F	   |
| F | F |     T    |

When given the argument 'A if and only if B', the argument is said to be True when A and B are both True or both False; and they are said to be false if one is true and the other is false

When A <--> B is true, we say that A and B are **Equivalent**.

## ∴ = Therefore

##Standard form of an Inference
1. antecedent 1 
2. antecedent 2 
3. ∴ consequent

> P --> Q

> P

>  ∴Q



#Logical Forms

###Modus Ponendo Ponens
The **Law of detachment** (AKA **affirming the actecedent** and **modus ponens**) is the first form of deductive reasoning. It states that if a conditional statement is made, and a hypothesis is stated, then the conclusion is deduced from the statement and the hypothesis.

1. P --> Q (Conditional statement)
2. P (Hypothesis stated)
3. ∴ Q (Conclusion Deduced)

> All men are mortal

> Socrates is a man

> Therefore Socrates is mortal

####Common associated fallacy - Affirming the consequent 
Affirming the consequent (AKA **Converse Error**) is a formal fallacy of inferring the converse from the original statement.

1. P --> Q (Conditional statement) 2. Q 3.  ∴ P 
> If everyone was against me I'd have a bad day 

> I had a bad day 

> Therefore everyone is against me. 




###Modus Tollens
The law of **contrapositive** (AKA **Modus Tollens**) states that, in a conditional, if the conclusion is false, then the hypothesis must also be false.

1. P --> Q (Conditional statement) 
2. ~ Q (Not Q) 
3. ∴ ~ P (Not P)

> If it has a vagina then it is a woman

> Johns does not have a vagina

>  Therefore John is not a woman (Regardless of what he puts on his DEERS)

####Common associated fallacy - Denying the antecedent
AKA **Inverse Error** or **Fallacy of the inverse** is a formal fallacy of inferring the inverse from the original statement.

1. P --> Q
2. ~P 
3. ∴ ~Q

> If you run, you'll get sweaty 

> You didn't run

> Therefore you're not sweaty (What if I went biking?)



###Hypothetical Syllogism
The law of syllogism (AKA **The Chain Rule** ) takes two conditional statements and forms a conclusion by combining the hypothesis of one statement with the conclusion of another.

1. P --> Q
2. Q --> R
3. ∴ P --> R

>  If Jay doesn't study, he'll get bad grades

>  If Jay gets bad grades, he won't get to do his job

>  If Jay doesn't study, he won't get to do his job


###Disjunctive Syllogism
This valid argument form (AKA Modus Tollendo Ponens, AKA process of elimination) is a syllogism having a disjunctive statement (using an OR(or XOR) operator) for one of its premises.

1. P v Q
2. ~P
3. ∴ Q

> Either your an asshole or you're just hungry.

> You're not hungry

> Therefore you're just an asshole (It is also possible that you're both)


###Conjunctive Addition
Conjunctive Addition is a rule of inference pertaining to the AND Operator. Conjunctive Addition means that any two true statements can be joined to form a conjunction. 

1. P
2. Q
3. ∴ P ^ Q

> The sky is blue

> The sun is out

> Therefore the sky is blue and the sun is out. 


###Demorgan's Law
Demorgan's law of inference is use to convert a negative to a conjunction or disjunction.

1. ~(P ^ Q)

> It is not true that I have a dog and a cat.

Demorgans law states that I can convert the above negative conjunction to the below:

2. ~P v ~Q

> I do not have a cat or I do not have a dog.

The above is an example of converting a negative conjunction into a disjuction alternatively we could use the same method to turn  a negative disjunction into a conjunction:

1. ~(P v Q)

> It is not true that Will Ferral is funny or step brothers was a great movie.

2. ~P ^ ~Q

> Will Ferral is not funny and step brothers was not a great movie.


###Disjunctive Addition
Disjunctive Addition is of inference which uses the OR operator. It adds any statement, whether true or false, to a true statement.
For example given the true statement:

1. P
2. P v Q

> Carbs are delicious

> Carbs are delicious or cocaine is a hell of a drug.

The above statement is true regardless of what Q is because P is True and we are using the OR operator.



##References

[Introduction to mathematical arguments](https://math.berkeley.edu/~hutching/teach/proofs.pdf)
http://mathworld.wolfram.com/Logic.html
http://philosophy.hku.hk/think/logic/whatislogic.php
[Table of Mathematical Symbols from Wikipedia](https://en.wikipedia.org/wiki/Table_of_mathematical_symbols)
