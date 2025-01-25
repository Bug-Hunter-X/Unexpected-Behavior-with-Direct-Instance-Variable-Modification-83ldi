# Ruby Bug: Unexpected Behavior from Direct Instance Variable Modification

This example demonstrates a potential issue in Ruby when directly modifying instance variables using `instance_variable_set`.  While technically possible, this practice can lead to unexpected behavior, debugging challenges, and difficulties in maintaining code.

The bug is in the lack of encapsulation caused by bypassing the getter and setter methods and directly changing an instance variable.

**Recommended Solution:** Always use getter and setter methods to access and modify instance variables for better encapsulation, maintainability, and predictability.
