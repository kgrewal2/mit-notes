# 1. Getting Started

## Declarative Knowledge

It consists of facts.
Example: Square Root of a number $x$ is $y$ such that $y*y=x$. This doesn't tell how to find the square root of the number.

## Imperative Knowledge

It gives the "how to" recipe for deducing information.
Example: Heron of Alexandria's Method of finding square root.

1. Start with a guess, $g$.
2. If $g*g$ is close enough to $x$, then the answer is $g$.
3. Otherwise, change the value of $g$ to the average of $g$ and $x/g$
   $g \rarr \frac{(g+x/g)}{2}$
4. Use the new guess and go to step 2.

## Algorithm

A sequence of simple steps, together with the flow of control that specifies when each step is to be executed.

This method of finding square root was an example of *guess and check* algorithm.

Formal Definition: Finite list of instructions that describes a computation that when executed on a provided set of inputs will proceed through a set of well defined states and eventually produce an output.

Finite list of instructions executed $\rarr$ Set of inputs $\rarr$ Set of well defined states $\rarr$ Output.

## Programming Language

1. Primitive Constructs
   Words of English
   Python: Literals (number 3.2 or string 'hello') and infix operators (+, -, *)
2. Syntax
   String of words
   Python: $2+2$ is syntactically correct but $2$ 'hello' is not. 
3. Static Semantics
   Meaningful Sentences
   Python: $2/\text{hello}$ is syntactically correct (literal-operator-literal) but it has static semantic error as it doesn't mean anything to divide number by a string.
4. Semantics
   Meaning of Sentences
   Unintended Meaning
   - Program may crash.
   - Program may never stop.
   - The output may or may not be correct.
     This is the worst case as the program may seem to be running well but bad things can follow.

# 2. Introduction to Python