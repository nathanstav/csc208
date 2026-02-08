# Chapter 0 Notes

## What is Discrete Math?

**discrete** - Individually separate and distinct

**mathematics** - A collection of tools that allow you to solve numerical problems

**discrete mathematics** - Discrete math is still math, but it only focuses on elements that are separate. This means that an interval, like $(0, \infty)$, is NOT discrete, but something like, $\{0, 1, 2, 3, 4\}$, is. The elements of this are separate, and not continuous.



## 4 Main Topics Presented in the Book

1. **Combinatorics** (the theory of ways things combine)
2. **Sequences**
3. **Symbolic logic**
4. **Graph theory**

## What are Discrete Structures?

**Discrete structures** are the mathematical objects that we use to represent the problems that we are solving.

Most commonly, out of the structures that exist, we will be using **sets**, **functions**, **sequences**, **relations**, and **graphs**.

### Sets
A **set** is an unordered collection of elements. We can think of all of mathematics as just sets, including numbers themselves. 
<br> &emsp; Instead of doing this, though, we will talk about collections of numbers and other objects as part of a set. The order of the set does not matter.

### Functions
A **function** is a rule that assigns each input exactly one output. The output is known as the **image** of the input, and the set of inputs is called the **domain**. The **codomain** is the set of all *possible* outputs, and the **range** is the set of all *actual* outputs from the function.
<br> &emsp; If we wanted to talk about the function $f(x) = 2x$, for example, we would draw the points (1, 2), (2, 4), and (3, 6), but we would NOT connect the dots (as then it would no longer be discrete). 
<br> &emsp; You could define these in a similar way to how a sequence is defined when taught in a continuous math class, like Algebra.
>  i.e. using a **closed formula** like $f(n) = 3n+1$,
> 
>  or using a **recursive formula**, $f(0) = 3$ AND $f(n) = 2 \cdot f(n-1)$

### Sequences
A **sequence** is similar in concept to a **set**, except the order *does* matter, unlike in a set. Sequences can be finite or infinite. A finite sequence may be something as simple as $(1, 2, 3)$, which we can also call an **ordered triple** (whereas something like $(7, 3)$ is an **ordered pair**). We can refer to sequences as $n$-**tuples**, where the sequence has $n$ elements. We can refer to terms of a sequence as:
<br> &emsp; &emsp; $a_0$, $a_1$, $a_2$,...
<br> &emsp; This is very similar to what you should have learned in an Algebra or Pre-Calculus class. 


| $n$ | 1 | 2 | 3 | 4 | ...
|----------|----------|----------|--|--|--|
| $a_n$ | 1| 3 | 6 | 10 | ...


### Relations
A **relation** in mathematics is the way that 2 numbers are related.
> i.e. $2 < 6$, 6 is a multiple of 2, and 2 and 6 are both even.

When exactly 2 numbers are being related, it is called a **binary relation**. You can relate more than 2 numbers, though. One example of this is the *"Pythagorean Triple"*, which holds any 3 numbers that can be the 3 side lengths of a right triangle (i.e. $(3, 4, 5)$, but not $(4, 5, 6)$).

Relations can have properties, too. For example, a less-than relationship is **irreflexive**, meaning an element cannot be related to itself using this type of relation. A less-than relationship is also **antisymmetric**, as there are no numbers where flipping it around would keep a true statement 
> i.e. if $a < b$, then $b < a$ cannot also be true

&emsp; Some groups of properties happen together often, and we can prove general results about the relations that satisfy them. For example, if a relation is **reflexive**, **symmetric**, and **transitive**, then we know that the relation is an **equivalence relation**, which tells us more properties that it is guaranteed to have.