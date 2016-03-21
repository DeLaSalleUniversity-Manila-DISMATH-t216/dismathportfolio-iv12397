# dismathportfolio-iv12397
dismathportfolio-iv12397 created by Classroom for GitHub

## **Week 1:** 
- I learned what was Discrete Mathematics all about, and the first lesson is all about logic and proofs.
 * In logic and proofs, proposition is a statement that is either true or false.
 * Logical deduction is a process of reasoning from one or more statements which reach to a conclusion.
 * Axiom of Equality - a statement that is already accepted. | ex: a+c = b+c |
 * There are also different types of truth which depends to its beholder
    * Legal truth - decided by a judge
    * Authorative truth - specified by a trusted person
    * Scientific truth - confirmed by an experiment
    * Probable truth - established by statistical analysis
    * Philosophical proof - careful exposition and persuasion
    * **Mathematical truth - what we use in DISMATH**
         * Proposition is a declarative statement.
            * Example (which was given in our class): "Shun will be successful." ← we can declare this.
* Logical connectives 
 
| Operator | Symbol | Usage |
| :---: | :---: | :---: |
| Negation | ¬ | not |
| Conjunction | ∧ | and |
| Disjunction | v | or |
| Exclusive Or | ⊕ | x or |
| Conditional | → | if, then. |
| Biconditional | ↔ | iff |

* Propositional Variables 
	* Ex: p and q
* Truth Table lists all the possible combination of the input with their corresponding output.

| Input (q) | Output (¬q) |
| :-----: | :---: |
| T | F |
| F | T |

* Conjunction (p ∧ q) - True iff p and q are true.

| p | q | p ∧ q |
| :---: | :---: | :---: |
| F | F | F |
| F | T | F |
| T | F | F |
| T | T | T |

* Disjunction (p v q) - False iff p and q are false.

| p | q | p v q |
| :---: | :---: | :---: |
| F | F | F |
| F | T | T |
| T | F | T |
| T | T | T |

* Exlusive Or (p ⊕ q) - p or q but not both.

| p | q | p ⊕ q |
| :---: | :---: | :---: |
| F | F | F |
| F | T | T |
| T | F | T |
| T | T | F |

* Conditional Statement (p → q) - if p, then q.

| p | q | p → q |
| :---: | :---: | :---: |
| F | F | T |
| F | T | T |
| T | F | F |
| T | T | T |

* Biconditional (p ↔ q) - p iff q.

| p | q | p ↔ q |
| :---: | :---: | :---: |
| F | F | T |
| F | T | F |
| T | F | F |
| T | T | T |

## **Week 2:** 

- This week, we learned about proof using logical equivalences
 * Logical Equivalences are compound propositions that have the same truth values in all possible cases.

| Equivalences | Name |
| :---: | :---: |
| p ∧ T ≡ p | Identity Laws|
| p v F ≡ p |  |
| p v T ≡ T | Domination Laws |
| p ∧ F ≡ F | |
| p v p ≡ p | Idempotent Laws |
| p ∧ p ≡ p | |
| ¬(¬p) ≡ p | Double Negation Law |
| p v q ≡ q v p | Commutative Laws |
| p ∧ q ≡ q ∧ p  |  |
| (p v q) v r ≡ p v (q v r) | Associative Laws |
| (p ∧ q) ∧ r ≡  p ∧  (q  ∧  r) |  |
| p v (q ∧ r) ≡ (p v q) ∧ (p v r)  | Distributive Laws |
| p ∧ (q v r) ≡ (p ∧ q) v (p ∧  r) |  |
| ¬(p v q) ≡ ¬p ∧ ¬q | De Morgan's Laws |
| ¬(p ∧ q) ≡ ¬p v ¬q | |
| p ∧  (q v p) ≡ p | Absorption Laws |
|  p v  (q  ∧  p) ≡ p | |
| p v ¬p ≡ T | Negation Laws |
| p ∧ ¬p ≡ F | |

 * I also learned about the superman problem by proving he does not exist.

- Also, this week, we were taught about the quantifiers
 * Existential Quantifier (∃x) - "there exist"
 * Universal Quantifier (∀x) - "for all"

| | When True? | When False? |
| :---: | :---: | :---: |
| ∀x P(x) | P(x) is true for every x. | There is an x for which P(x) is false. |
| ∃x P(x) | The is an x for which P(x) is true. | P(x) is false for every x. |
 
- Rules of Inference is also introduced to us, and these are some terminologies:
  * Argument - sequence of statements which end with a conclusion.
  * Valid - conclusion must follow the truth of the preceding statements.
  * Fallacy - incorrect reasonings which lead to invalid statements.
  * Tautology - statement that is always true.
  * These are some rules of interference:

| Tautology | Name |
| :---: | :---: |
|  [(p→q)∧ p] → q | Modus Ponens |
|  [(p→q)∧ ¬q] → ¬p | Modus Tollens |
| [(p→q)∧ (q→r)] → (p→r) | Hypothetical Syllogism |

## **Week 3:** 
- We were taught about methods of proof.
 * Direct Proof
 * Proof by Contrapositive
 * Vacuous and Trivial Proof
 * Proof by Contradiction
 * Proof by Equivalences

1. Direct Proof 
  1. Assume p is true
  2. Show that q is also true
2. Proof by Contrapositive
  1. Assume ¬q is true
  2. Show that ¬p is true
3. Vacuous Proof
  1. Show that p is false since p→q is true
4. Trivial Proof
  1. Show that q is true then p→q must be true

- We were given some examples for us to understand on how to use the different methods of proving.

## **Week 4:** 
- We continued doing examples for us to be practiced.
- After practicing the methods, we were taught about disproving a given statement by giving a counter example.
- We were introduced to Mathematical Induction.
  * In Mathematical Induction, 
	 * First step: the basis
	 * Second step: use direct proof
- We were introduced to summation.
 * In summation,
	 * First, we were given a solution and we are to look for the correct equation. 
	 * Next, we are to assume and show that it is true.
 * Warning: Remember to always use the first step in Mathematical Induction.
- Lastly, we were introduced to Recursive/Inductive Definition and Recursive Algorithm.
  * If in the basis step, we are to specify the value of function at zero, in recursive, we are to give a definition for finding its value at an integer.
  * In Recursive Algorithm,
    * It is only called recursive if it solves a problem by reducing it to an instance of the same problem with smaller input such as "n!"
   
## **Week 5:**
- We continued the class discussion on recursive algorithm.
 	* Recursive Algorithms
  		* Algorithm is a finite set of precise instructions for performing a computation or solving a problem.
			 - In short, it is used to solve a problem.
	* Example writing a program of a recursive algorithm of n!
	
			factorial (k: non-negative integer)

			{ if (k==0)
	
			return 1;
	
			else
	
			return k*factorial (k-1); }

	* If we entered the factorial (4), the program can't read "factorial" so it will go back to the definition which meant it will call itself until it reaches the basis. In this case, it will call itself until it reaches 0 to get an answer of 1. Next, 1 will collapse to the processes it went through until it goes back to the caller. 
	* In conclusion, the bigger the number, the slower the program will be because it will call itself until the basis then it will go back to the processes to go back to the caller.
- The next discussion were _Program Correctness, Partial Correctness and Hoare Triple_ .
	* Program Correctness 
		* Program Verification - put input and see if it gives the correct output.
			1. Show the correct answer is obtained. (if the program terminates, it is partial correctness)
			2. Show that the program always terminates.
	* Partial Correctness
		* Initial Assertion, p, gives the properties that the input values must have.
		* Final Assertion, q, the output.
	* Hoare Triple: p{S}q where S is the program segment.
		1. Assume p ≡ T
		2. Substitute p to S, then show q ≡ T
- How can we prove a compound program?
	* Use the rules of inference (Composition Rule)
	
			p{S1}q

			q{S2}r
		
			∴ p{S1:S2}r

- How to prove if the conditional statement is correct?
	1. Conditional Statements
		
			(p∧condition){S}q

			(p∧¬condition)→q
			
			∴p{if condition then S} → q
			
	2. If else Statements

			(p∧condition){S1}q
			
			(p∧¬condition){S2}q
			
			∴p{if condition then S1 else S2}q
			
- Next, we discussed about the _representation of functions as Power Series_ .
	* Infinite Series: Zeno's Paradox
		* For example, 
			
			First, cover the half distance

			Then cover the half of the half distance
			
			Then cover the half of the half of the half distance
			
			And so on.....
			
	* The Power Series is:
		
			1/2 + 1/4 + 1/8 +....
		
		* For algebra, this is a geometric series
				
				where: 

				|r|>1 (converge)
	
				|r|<1 (diverge)
				
	* The power series is symbolized:
	
				∞
				∑ Anx^n = 1 + x + x^2 + x^3 +... 
				n=0
			
			* Think of it as a function of x that is defined convergence.

- Next, we were introduced to set theory.
	* Set 
		* Not in ordered collection of distinct objects
		* (set is organized in '{ }')
	* Empty Set 
	
			{ } = ∅ 
		
		* The first one contains no element.
		* The ∅  means empty set.
		
	* Membership - shows if an object is belonged to the set.
	* Set-builder notation
	
			{ x| some property of x satisfies }
			
		* Example:
		
			{ n| n∈N and n is even }
			
	* Venn Diagrams
		* Union, A ∪ B
		* Intersection, A ∩ B
		* Difference, A - B or A \ B
		
	* Set Identtities
	
		| Identities | Name |
		| :---: | :---: |
		| A ∩ U ≡ A | Identity Laws|
		| A ∪ ∅ ≡ p |  |
		| A ∪ U ≡ U | Domination Laws |
		| A ∩ ∅ ≡ ∅ | |
		| A ∪ A ≡ A| Idempotent Laws |
		| A ∩ A ≡ A | |
	
		* It is the same as the logical equivalences but just change F to ∅, T to U, p to A, q to B, ∧to ∩ and  ∨ to ∪ .
		
	* Subsets
		
			S ⊆ T (S is a subset of T)
		
		* Example
		
			{1,2,3} ⊆ { 1, 2, 3, 4}
			
	* Power Set 

			℘(S) = {T| T ⊆ S }
		
		* read as set of subset
	
	* Superset
	
			A ⊇ B
		
- Lastly, we discussed the _Cardinality_ .
	* It is the number of elements in a set.
	* If S is a set, we denote |S|.
		* | {a,b,c,d,e} | = 5
		* | {a, b}, {c,d,e}, {f,g,h} | = 3
	* Cardinality of N
		* infinitely many natural numbers
		* alephnought of N = |N| = infinitely large
		
## **Week 6:**
- During this week, we reviewed and prepared for the first quiz on Friday, Feb 19, 2016.
	* Nested Quantifiers were reviewed to us:
		* The choices of x, some y, P(x,y) is true.
		
				∀x∃yP(x,y)
		
		* Some x, choices of y, P(x,y) is true.
		
				∃x∀yP(x,y)
		
	* Nagating Statements
		* Example: Negate the statement: Everyone loves someone.
		
				∀x∃yPoves(x,y)  into  ∃x∀y¬Loves(x,y)
	
	* Proof by cases
	* Proof by exhaustion
	* Existence Proofs
	* Uniqueness Proof
	
- After reviewing, we were introduced to DISMATH Application.
	* First, we discussed about the functions.
	* f(a) = b means b is is the image of a. 
	
				f: A => B
	
	* One to one function (Injective) 
		
				{a,b,c,d} to {1,2,3,4,5}
				f(a)=5 , f(b)=3 , f(c)=4 , f(d)=1
				**∀x∀y(f(x)=f(y) → x=y)**

	* Onto function (Surjective) - functions have equal range and codomain. (all set of numbers should be assigned)

				{a,b,c,d} to {1,2,3}
				f(a)=3 , f(b)=2 , f(c)=1 , f(d)=3
				**f: A => B = {(a,3),(b,2),(c,1),(d,3)}**
				
	* Bijective is one to one function and onto function
	* Not a function
		* one to many

## **Week 7:**
* Although there is no DISMATH for this week due to a Friday exam last week, so we were given time for **PROJECT 0-0**.
	* This project was entitled: **HelloWorldApp**
	* The minimum requirements are:
		* A button I am (First name, surname) of DISMATH (section).
		* A space in between the next button.
		* The next button is the talk button about the text from the above.
	* The **deadline** will be on **March 1**.
	* Lastly, this is an **individual** work.
	
## **Week 8:**
* We were introduced to Algorithm.
	* Algorithm 
		* a set of finite set of precise instruction for performing a computation.
	* Finding the **Maximum Element Algorithm**
		1. **Set** the temporary maximum equal to the first integer in the sequence.
		2. **Compare** the next integer in the sequence to the temporary max.
		3. **Repeat the previous set** if there are more integers in the sequence.
		4. **Stop** when there are no integers left in the sequence.
	* Example:
	
			Precondition: {2,5,8,1,10,12,3} ∈ Z, finite
			Postcondition: max= maximum(A1,A2,A3,...,An)
			using for-loop (Pseudocode)
			for i=2 to n
				if(max<Ai)
					max=Ai

	* Pseodocode
		* high level description of an algorithm that uses the structural conventions of a programming language, but intended for human reading.
		* It is a human readable code.
	* Example of Algorithms
	* Algorithm 1:
	
			Linear Search
			
			Input: S={A1,A2,...,An} A1 ∈ Z; x ∈ Z
			Output: index, loc where Aloc=x
			loc=-1
			for i; 1 to n
				if(Ai==x)
					loc=i;
			final assertion: loc is the location of element

	* Algorithm 2:

			Binary Search
			
			Input: {A1,A2,...An:distinct integers}
			i=1 (i is the left endpoint of the search interval)
			j=n (j is the right endpoint of the search interval)
			while i<j
				mid = [(i+j)/2]
				if x>A(mid) then i=mid+1
				else j=mid
			if x=Ai then location=i
			else location=-1
			return location 

## **Week 9:**
* The continuation of the lesson, Algorithm:
	* Algorithm 3:
	
			Bubble Sort
			
			Input: {A1,A2,.....,Ai,....An} ∈ all real numbers, n>=2
			Output: {X1,X2,....,Xi,...,Xn} where X1<X2<.....<Xn
			for j=1 to n-1
				for i=1 to n-j
					if(Ai>A(i+1))
					swap(Ai,A(i+1))

	* Algorithm 4:
	
			Insertion Sort
			
			Input:{A1,A2,.....,Ai,....An} ∈ n>=2
			for j=2 to n
			{
				i=1
				while Aj>Ai
					i=i+1
				m=Aj
				for k=0 to j-i-1
					A(j-k)=A(j-i-1)
				Ai=m
			}
			Output: {X1,X2,X3,....,Xn:increasing order}

		* Outer for-loop is responsible of the sorting.
		* Inner for-loop is responsible for swapping.

	* Algorithm 5:
	
			Greedy Algorithm
			- selects the best choice at each step, instead of considering all sequences of steps that may lead to an optional solution.
			- applied in optimization problems where a solution to the given problem either minimizes or maximizes the value of some parameter.
			
			Denomination 
				C={25,10,5,1}
				x=amount of memory
			for i=1 to r
				x=0
			while (x≥Ci)
				x=x-Ci
				n=n+1

## **Week 10:**
* This week, we were introduced to growth of functions.
	* Using Big-O, Big-Ω and Big-ϴ
	* In Big-O, we are looking for the upper bound size of f(x).
	* In Big-O, let f and G be functions from Real numbers to Real numbers where f(x) is O(g(x)) if there are constants C and k such that:
	
			|f(x)| ≤ C|g(x)| where x > k
			C and k are the witnesses of Big-O

		* Example:
			
				x^2 + 2x + 1 is O(x^2) 
				x^2 + 2x + 1 is O(x^3)
				x^2 + 2x + 1 is O(x^4)

	* Same as in Big-Ω, but in this function, we are looking for the lower bound of f(x).
	
		* Example:
		
				x^2 + 2x + 1 is Ω(x^2)
				x^2 + 2x + 1 is Ω(x)

	* Lastly, in Big-ϴ, we are looking for both the lower and upper bound size of f(x).
	
		* Example:
		
				x^2 + 2x + 1 is ϴ(x^2)

		* There is only one answer in Big-ϴ.

* Next, Time Complexity in Algorithm, and Division and Modulo Operator
	
	* Time Complexity
		* can be expressed in terms of the number of operations used by the algorithms.
		* number of comparisons will be used as the measure of the time complexity.
	
		| Complexity | Terminology |
		| :---: | :---: |
		| ϴ(1) | constant complexity |
		| ϴ(logn) | log complexity |
		| ϴ(n) | linear complexity |

		* Time complexity of finding max comparison: 2n-1, ϴ(n)
		* Time complexity of linear search: 2n+2, ϴ(n)
	
	* Division and Modulo
	
			* Example:
				Let a = integer, d = positive integer
				Unique integers Q and r
					with 0<=r<d such that a=dQ+r
				9 mod 2 = 1 (r)
				9 div 2 = 4 (Q)
				a=d*Q+r
				a=2*4+1
				a=9

	* Last topic for quiz 2: Ceasar Cipher
	
			* How can you make your message secret?
				Example:
				LOVE = ORYH
				(p+3) mod 26

## **Week 11:**
* # **HOLY WEEK**

## **Week 12:**

- **_"A smile can change a life."_**
		- *Irene Victoria L. Or*, **DISMATH EL**
