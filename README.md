# push_swap

A project challenging the implementation of an efficient sorting algorithm using two stacks and a limited set of operations.

## Overview

**push_swap** teaches:
- Algorithm optimization
- Stack data structure usage
- Computational complexity analysis
- Sorting algorithm implementation

## The Problem

Sort a list of random integers using two stacks (a and b) and a defined set of operations, minimizing the number of instructions.

## Available Operations

### Stack a operations
- `sa`: swap a (swap first 2 elements)
- `pa`: push a (move top element from b to a)
- `ra`: rotate a (move first to last)
- `rra`: reverse rotate a (move last to first)

### Stack b operations
- `sb`: swap b
- `pb`: push b
- `rb`: rotate b
- `rrb`: reverse rotate b

### Both stacks
- `ss`: sa + sb simultaneously
- `rr`: ra + rb simultaneously
- `rrr`: rra + rrb simultaneously

## Goal

Minimize the number of operations to sort the stack in ascending order.

## Complexity Requirements
- 3 numbers: max 2 operations
- 5 numbers: max 12 operations
- 100 numbers: max 700 operations
- 500 numbers: max 5500 operations

## Implementation Strategy
- Quicksort approach
- Radix sort approach
- Custom optimization algorithms

