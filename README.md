# Unexpected Behavior When Directly Modifying Instance Variables in Ruby

This example demonstrates a potential issue in Ruby when directly modifying instance variables using `instance_variable_set`. While functional, this approach bypasses the encapsulation provided by methods and can lead to unexpected behavior and make code harder to debug and maintain.

The `bug.rb` file contains the problematic code. The `bugSolution.rb` offers a better way to handle this by using a setter method.