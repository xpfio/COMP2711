# 1)a) "x is even only if y is odd"

This one was supposed to be an easy one, but it's actually tricky. If English is not your mother tongue like me, some clarifications might help. As p → q is a key concept in logic, please take the time to read the whole document to be sure that you get familiar with the concept.

## Correct answer

**If x is even, then y is odd.**

## Common mistakes

 _"If y is odd, then x is even"_

## Explanation

### Explanation A: From slides and examples

See slides 16 from L01 - Prepositional Logic, "Other Ways to Express conditional statements in English" lecture. 

(ie) for information:

Equivalent ways of expressing p → q:  

- if p, then q- q if p- q when p
- p implies q
- q follows from p
- p is a sufficient condition for q
- q is a necessary condition for p
- **p only if q** (falsity of q implies falsity of p )
	- “The company can succeed only if it has sufficient funding.”

### Explanation B: "if", "only if" and "if and only if"

You can think of it like that:

x is even **if (←)** y is odd.   
x is even **only if (→)** y is odd.  
x is even **if and only if (↔)** y is odd.

### Explanation C: Using contrapositive

- If y is not odd then x is not even. This works!
- If x is not even then ___________ ? Well, we can't say anything here.

### Explanation D: Other formulations:

- **y is odd if x is even**.
- x is even is a sufficient condition for y to be odd.
- y is odd is a necessary condition for x to be even.

### Exaplanation E: Truth Table

You can always build a truth table if needed to clarify your mind.

# 1)b) "To get a good grade it is necessary that you study"

Here again, if English isn't your first language, translation might be hard. Have a deep look at the correction as many got the answer wrong. 

## Correct answer

**If you got a good grade then it means that you studied.**

## Common mistakes

- If you study you get a good grade. It's not automatic, you can easily study a lot and still get a very bad grade. However, given this input, you can't get a good grade if you didn't study.
- Using the word **can**, well we loose all the information: If p then maybe b, doesn't give us any information.

## Explanation

### Explanation A: From the slides

See slides 16 from L01 - Prepositional Logic, "Other Ways to Express conditional statements in English" lecture. 

(ie) for information:

Equivalent ways of expressing p → q:  

- if p, then q- q if p- q when p
- p implies q
- q follows from p
- p is a sufficient condition for q
- q is a necessary condition for p
- **p only if q** (falsity of q implies falsity of p )
	- “The company can succeed only if it has sufficient funding.”

	
### Explanation B, using negatives

If you get a **bad** grade, then ________________ ? We can't tell anything.  
If you didn't study, then you got a bad grade for sure.

# 1)c) "Studying is sufficient for passing"

## Correct answer

If you study then you pass.

## Mistakes

- If you study then you **can** pass. It's correct, but really ambiguous. 


# 2) "You sleep late if it is Saturday"

Okay, let's make it straight forward:

- p: "It is Saturday"
- q: "You sleep late"

We have p → q, 

## Correct answers

- Contrapositive: If you don't sleep late then it is not Saturday.
- Converse: If you sleep late then it is Saturday
- Inverse: If it is not Saturday, then you don't sleep late. 

## Mistakes

- Inverting p and q.
- Wrong order in the answers.
- It's better to write if... then... for the reader!


## Explanation

See slide 17 from L01 "Converse, Contrapositive" ie
Definition
- The converse of p → q is q → p.- The contrapositive of p → q is ¬q → ¬p. 
- The inverse of p→q is ¬p → ¬q.  

p → q and it contrapositive are equivalent.


# 3) Truth Table

## Correct answer 

From the slides, it's easy.
Steps:

- 2 variables, p and q, so build a table with 2² = 4 rows.
- First columns, **p**, filled with T T F F.
- Second coloumn, **q**, filled with T F T F.
- Third column, **p → q** filled with T F T T.
- Fourth column, **not p**, filled with F F T T.
- Fifth coloumn, **not p or q**, with T F T T.

Conclusion: "**p → q**" and "**not p or q**" are logically equivallent from columns 3 and 5.

## Mistakes

No errors on this question, sometimes adding an extra step (ie column 4 helps the reader to understand your thought process).


# Conclusion

Very well understood first in-class exercice. If you didn't get full bonus, read the slides again and try the use cases with simple examples.

