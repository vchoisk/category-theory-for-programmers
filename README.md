# category-theory-for-programmers
personal note on CTFP

## Links
Chapter 1

## Chapter 1
### Intro
- category consist of objects and arrows that go between them
- the essence if a category is composition
  - arrows compose: if there is an arrow from A to B and an arrow from B to C, there must be an arrow(their composition) that goes from A to C

### 1.1 Arrows as functions
"g circle f" can be read as "g after f", g(f(a))

### 1.2 Properties of Composition
1. associative: when given three mophisms(arrows, functions), the order of composition does not matter
2. for every object A, there is the unit arrow called identity on A. this arrow goes from A to A

### 1.3 Composition is the Essence of Programming
given a problem, start with 'what is...'
then break it into smaller problems, then put the smaller problems together(compose them)
The benefit of decomposing bigger problem and composing smaller solutions is that it takes much less information to compose chunks than to implement them.Once the smaller solution is implemented, we can forget the implementation detail and focus of how it interacts with other chunks. 
  - in OOP,  it uses abstract interface
  - in functional programming, it declares functions(what job needs done)
`The moment you have to dig into the implementation of the object in order to understand how to compose it with other objects, you’ve lost the ad- vantages of your programming paradigm.`
