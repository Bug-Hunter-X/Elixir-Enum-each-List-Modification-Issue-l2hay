# Elixir List Modification within Enum.each

This example demonstrates a common misconception in Elixir when working with immutable lists and the `Enum.each` function.  Attempting to modify a list inside `Enum.each` does not affect the original list; instead, a new list is created.

The `bug.exs` file contains code that illustrates this issue. The solution, provided in `bugSolution.exs`, shows how to correctly achieve the desired list modification.