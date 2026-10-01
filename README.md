# even-odd-bdd

A minimal BDD example with Cucumber and Java: the behaviour is written in plain English first, then wired to code.

Companion code for my article [BDD: Behaviour Driven Development with Java and Cucumber](https://medium.com/@kumarprabhashanand/bdd-behaviour-driven-development-with-java-and-cucumber-42a9fc0c1112).

- `src/test/resources/EvenOddBdd.feature` - the scenarios (Given / When / Then)
- `src/test/java/.../EvenOddStepdef.java` - step definitions that connect them to code
- `src/main/java/.../EvenOddBddExample.java` - the code under test

Run the feature file from your IDE with the Cucumber plugin. TDD version of the same idea: [primefactor-tdd](https://github.com/kumarprabhashanand/primefactor-tdd).
