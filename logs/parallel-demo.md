# CircleCI Parallelisation Demo

## Why do we want to parallelise?

What's most important to us as developers? 

One of the answers is probably : Short feedback loops

Reducing the time between making a change, and realising that either that change is 🥳 or 😢

In some of our repositories (BILLING, WE'RE LOOKING AT YOU)

The whole test suite can take a looooong time to run.

Luckily, CircleCI (and any other CI provider worthy of consideration) provides a way to split our tests across 
multiple test runners.


### No parallelisation:

0 : |--------------------------------------------------------------------------------------------------------->


### Parallelisation:

0 : |----------------------------------------->|
1 : |----------------------------------------->|
2 : |----------------------------------------->|
3 : |----------------------------------------->|
4 : |----------------------------------------->|

### 
