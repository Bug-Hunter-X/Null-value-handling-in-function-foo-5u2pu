# JavaScript Bug: Null Value Handling

This repository demonstrates a common JavaScript bug related to handling null values in function parameters. The `foo` function is expected to perform a certain operation, but it exhibits unexpected behavior when null values are passed as arguments.

## Bug Description

The `foo` function doesn't explicitly handle null values, leading to unexpected behavior or errors when null is provided for either `a` or `b`.  This is a common source of subtle bugs.

## Bug Solution

The solution demonstrates how to explicitly handle null values by checking them before attempting further operations within the `foo` function.
