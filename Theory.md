# Finite Automata
finite automaton is an abstact machines that has states and transitions between these states. It is always in one of its states and while it reads input it switches from state to state. It is composed by a start state and an end state.

# DFA (deterministic finite automata)
![fig. 1](https://deniskyashif.com/images/posts/2019-02-20-regex/dfa.png)

in the above example we have what we call DFA, which has 4 states; where q0 is the start state and q3 is the end state.
all the string that start with ab follwed by an arbitrary numbers of bs ending with an "a" will be recognizes;

for ex. abba will go first to q1 then to to q2 again in q2 and then finally in q3. that's what the matchine, the dfa does.

For the strings "aba", "abbba" or "abbbbba", the automation will end up in a accepting state of q3;

if as input you give the string "ab" the machine will never end into the ending state; 
"abca" will not be accepted because "c" will not be recognize by the machine.

# NFA (Non deterministic Finite Automata)

