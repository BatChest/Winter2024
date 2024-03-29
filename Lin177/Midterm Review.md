1) Explain the difference between a natural language and a formal language
```ad-note
Natural language is the languages that humans speak natively(English, Spanish, Mandarin) are ambiguous, context-dependent

whereas Formal language is one with an explicit criteria for whether something is in or out of the langauge(programming languages), having strict syntax and semantics are unambiguous 
```
2) how we can use formal languages to study natural languages
```ad-note
Formal languages provide a framework that we can use to model and study the structure of natural languages. 

Use formal grammars, such as context-free grammars, to describe the syntax of a natural language.
```

3) Identify whether a formal language is finite or infinite
```ad-note
A formal language can either be finite or infinite:
Finite Formal langauge: is one where there is a finite number of valid strings or sentences

Infinite Formal Language: one where there is an infinite number of valid strings or sentences.
Usually have the Kleene Star operator
```

4) Define formal languages using Finite State Automata
	1) e.g. given a description of a language, write a FSA to recognize it

5) Use a FSA (deterministic and non-deterministic) to calculate whether a given string is accepted/rejected
- Review HW1 question 1

6) Identify whether a FSA is deterministic or non-deterministic
```ad-note
Non-deterministic:

Allow multiple exiting transition arrows with the same letter

Allow blank transition

Not every step of the calculation is unique


Deterministic:

Every state has one exiting transition arrow for each letter in the alphabet

Doesn't allow epsilon transitions

Every state has at most one exiting transition arrow for each letter in the alphabet 

Every step of the calculation is unique(for recognition)
```
- Non-deterministic FSA

![Pasted image 20240213203936](https://github.com/BatChest/Winter2024/assets/90287766/d9cac134-d249-40d0-98f2-4111b9a37188)

![image](https://github.com/BatChest/Winter2024/assets/90287766/35c2ea2a-a34a-4063-9471-c87edd240dfc)


- Deterministic FSA

![Pasted image 20240213204923](https://github.com/BatChest/Winter2024/assets/90287766/fc9f20e6-547f-4119-9024-d3af2b0cf75d)

![image](https://github.com/BatChest/Winter2024/assets/90287766/9912c405-cfa1-479e-9771-fd5868907662)



7) Define formal language using regular expressions
	1) e.g. given a description of a language, write a regular expression to generate it
```ad-note
Regular operations:

Let A and B be languages

Union: A U B = {x | x ∊ A or x ∊ b}

Concatentaion: A ∘ B = {xy | x ∊ A and y ∊ B}

Kleene Star: A* = {$x_1$ $x_2$ $x_3$... $x_k$ | k ≥ 0 and all $x_i$ ∊ A}
```

8) Define regular relations using Finite State Transducers
