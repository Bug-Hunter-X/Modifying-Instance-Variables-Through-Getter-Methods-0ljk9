# Ruby Bug: Modifying Instance Variables Through Getter Methods

This repository demonstrates a common error in Ruby related to modifying instance variables through getter methods.  The example shows that attempting to directly modify an instance variable through its getter method does not change the instance variable's value. This is because the getter method returns a copy, not a reference.

## Solution
To correctly modify an instance variable, a setter method should be used. The `bugSolution.rb` file provides a solution using a setter method.