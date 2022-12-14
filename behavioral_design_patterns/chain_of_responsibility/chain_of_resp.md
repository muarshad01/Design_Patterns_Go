## Chain of Reponsibility

[Chain of Responsibility in Go](https://refactoring.guru/design-patterns/chain-of-responsibility/go/example#example-0)

Chain of Responsibility is behavioral design pattern that allows passing request along the chain of potential handlers until one of them handles request.

The pattern allows multiple objects to handle the request without coupling sender class to the concrete classes of the receivers. The chain can be composed dynamically at runtime with any handler that follows a standard handler interface.

***

![Conceptual Example](https://github.com/muarshad01/Design_Patterns_Go/blob/master/behavioral_design_patterns/bdp_images/chain_of_responsibility.png)
