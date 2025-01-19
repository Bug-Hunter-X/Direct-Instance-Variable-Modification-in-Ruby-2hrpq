# Direct Instance Variable Modification in Ruby

This repository showcases a potential issue in Ruby when directly manipulating instance variables outside of defined methods. While functional, this practice can lead to unexpected behavior and difficulties in code maintenance.

The `bug.rb` file demonstrates the problematic approach, while `bugSolution.rb` provides a more robust solution.

## Issue
Directly changing instance variables using `instance_variable_set` bypasses any internal logic or validation within the class. This can make debugging and maintaining the code more challenging.