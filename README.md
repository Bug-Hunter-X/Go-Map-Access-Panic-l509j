# Go Map Access Panic

This repository demonstrates a common error in Go programs: panics caused by accessing a nil map.  The `bug.go` file shows the problematic code, while `bugSolution.go` offers a solution.

## Problem

Accessing a map in Go without checking for `nil` will result in a runtime panic if the map is uninitialized. This can lead to crashes in production environments.

## Solution

The correct approach is to always check if the map is `nil` before accessing its elements.  This can be done using a simple `if` statement.

## Usage

1. Clone this repository.
2. Run `bug.go` to observe the panic.
3. Run `bugSolution.go` to see the corrected code and its safe execution.