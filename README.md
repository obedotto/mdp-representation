# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

Text representation
Graphical representation
Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description

In this case consider a frog as a agent.that frog jump the next and next leaf to reach the goal - (insects)

### State Space

{B,A,C,D,E,F,G} -> {0,1,2,4,3,5,6}

These are state to the frog to reach the goal

### Sample State

2

### Action Space

{0} -> LEFT
{1} -> UP
{2} -> RIGHT

### Sample Action

{1} -> UP

### Reward Function

To reach goal ->+1(Reward)
Otherwise ->0

### Graphical Representation

![image](https://github.com/obedotto/mdp-representation/assets/119389971/b99ca38e-b36a-41d6-97cb-abce2bf3db54)


## PYTHON REPRESENTATION:

```

P = {

    0 : {
        0 : [(0.8 , 0 , 0.0 , False)],
        1 : [(0.6 , 0 , 0.0 , False)],
        2 : [(1.0 , 1 , 0.0 , False)]
    },

    1 : {
        0 : [(1.0 , 0 , 0.0 , False)],
        1 : [(1.0 , 4 , 0.0 , False)],
        2 : [(1.0 , 2 , 0.0 , False)]
    },

    2 : {
        0 : [(1.0 , 1 , 0.0 , False)],
        1 : [(0.8 , 2 , 0.0 , False)],
        2 : [(0.8 , 2 , 0.0 , False)]
    },

    3 : {
        0 : [(0.8 , 3 , 0.0 , False)],
        1 : [(0.8 , 3 , 0.0 , False)],
        2 : [(1.0 , 4 , 0.0 , False)]
    },
    4 : {
        0 : [(1.0 , 3 , 0.0 , False)],
        1 : [(1.0 , 6 , 1.0 , True)],
        2 : [(1.0 , 5 , 0.0 , False)]
    },
    5 : {
        0 : [(1.0 , 4 , 0.0 , False)],
        1 : [(0.8 , 5 , 0.0 , False)],
        2 : [(0.8 , 5 , 0.0 , False)]
    },
    6 : {
        0 : [(1.0 , 6 , 1.0 , True)],
        1 : [(1.0 , 6 , 1.0 , True)],
        2 : [(1.0 , 6 , 1.0 , True)]
    },
}

P
```

## OUTPUT:

![image](https://github.com/obedotto/mdp-representation/assets/119389971/1342d7b1-be10-44f2-b420-ded7f8eb7dd6)


## RESULT:
Thus a real world problem is represented as Markov Decision Problem in the following ways successfully:

