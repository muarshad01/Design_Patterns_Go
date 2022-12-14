## Strategy Behavioral Pattern

[Strategy in Go](https://refactoring.guru/design-patterns/strategy/go/example#example-0)
![]()

Strategy is a behavioral design pattern that turns a set of behaviors into objects and makes them interchangeable inside original context object.

The original object, called context, holds a reference to a strategy object. The context delegates executing the behavior to the linked strategy object. In order to change the way the context performs its work, other objects may replace the currently linked strategy object with another one.


***

![Navigation](https://github.com/muarshad01/Design_Patterns_Go/blob/master/behavioral_design_patterns/bdp_images/strategy.png)
