# What is Scope?

Scope defines the area of a program in which a variable is visible. In terms of global vs. local...

## Local

Variables which are confined to their own block, i.e. a function. The lifetime of this variable
ends when said function is finished executing.

## Global

Variable which exists in the scope of the entire program. It's lifetime is the entire length of
the program.

# Explain JS 'strict' mode

Javascript's strict mode is used to prevent unsafe actions and disables JavaScript features which
are confusing, and poorly thought out.

### Strict

    var x;

    x = 10; 

### Not Strict - "pollutes global namespace"

    x = 10;

# What are 'side effects' and what is a 'pure function'?

Side effects are changes to the application state which occur outside of the scope of a called function.
A pure function, has no side effects, and is deterministic.
