### Functional interfaces with lambda expressions Pre-work

Expected time required: 15 min

In this scenario, you are modifying an application that adds random numbers to a `List`. You must complete the scenario
by writing a lambda expression that implements the `Supplier` interface to help populate an array of `Integers`. 
`NumberGenerator` has two TODO comments inside the method `generateNumbers`.

1. In the `generateNumbers` method, write an inline lambda expression that implements
   the `Supplier` functional interface, passing it in to the call to `populateNumbers()`.
2. Inside `populateNumbers()`'s `for` loop, call `numberGenerator`'s `Supplier`
   interface method to populate the `List`. The line `numbers.add(-1);` should
   be replaced to supply a random number by calling `numberGenerator`.
