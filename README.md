# Go Append to Uninitialized Integer Variable

This repository demonstrates a common error in Go: attempting to append to an integer variable that has not been initialized as a slice.

## Bug Description
The `append` function in Go is used to add elements to a slice.  However, in this example, we try to append to an integer variable `i` which has not been initialized as a slice, resulting in a compile-time error.

## Bug Solution
To fix this, we must first initialize `i` as a slice.  This is done using the `make` function or a slice literal.

## How to run
1. Clone the repo.
2. Navigate to the directory
3. Run `go run bug.go` to see the compile error. 
4. Run `go run bugSolution.go` to see the correct code.