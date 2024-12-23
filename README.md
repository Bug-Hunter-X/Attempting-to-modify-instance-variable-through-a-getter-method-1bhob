# Ruby Instance Variable Modification

This repository demonstrates a subtle bug in Ruby related to modifying instance variables through getter methods.  The `bug.rb` file shows code that attempts (incorrectly) to modify an instance variable via a getter. The `bugSolution.rb` shows the corrected implementation.

The bug arises because a simple getter method only provides read-only access to the instance variable, not write access. To modify the instance variable, a setter method must be explicitly defined.

This example highlights the importance of understanding how instance variables and accessor methods work in Ruby for preventing unintended behavior.