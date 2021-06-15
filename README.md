# Deterministic-Finite-Automaton-Builder

A deterministic finite autimaton M is a 5 tuples consisting of 
- a finite set of state 
- a finite set of input symbol called the alphabet
- a transition fucntion 
- an initial or start state
- a set of accept states

Let w = a1, a2…an be a string over the alphabet Σ. The automaton M accepts the string w if a sequence of states, r0, r1, …, rn, exists in Q with the following conditions:

    r0 = q0
    ri+1 = δ(ri, ai+1), for i = 0, …, n − 1
    r n ∈ F {\displaystyle r_{n}\in F} {\displaystyle r_{n}\in F}.

In words, the first condition says that the machine starts in the start state q0. The second condition says that given each character of string w, the machine will transition from state to state according to the transition function δ. The last condition says that the machine accepts w if the last input of w causes the machine to halt in one of the accepting states. Otherwise, it is said that the automaton rejects the string. The set of strings that M accepts is the language recognized by M and this language is denoted by L(M).

A deterministic finite automaton without accept states and without a starting state is known as a transition system or semiautomaton. 

## About this project:

- Implement a DFA engine using JavaScript and Nodejs. Use your prefer IDE and run the program, once the program is running go to your browser and use localhost:3000/dfa-engine.html. It will render a page with instruction on how to use it. There are also 4 set of automatic dfa generate strings for testing. 
- If the string not accept by the the dfa condition it will display rejected otherwise accepted. 
