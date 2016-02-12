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
- **_"A smile can change a life."_**
		- *Irene Victoria L. Or*, **DISMATH EL**
