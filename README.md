# Ruby Instance Variable Immutability without Setter Methods

This example demonstrates an uncommon error in Ruby where attempting to modify an instance variable from outside the class does not work as expected due to the lack of a setter method.

The `bug.rb` file contains code that creates an object and tries to modify an instance variable directly, which will not work without an explicitly defined setter.

The `bugSolution.rb` file shows the correct way to handle this by adding a setter method to allow modification of the instance variable.