# Go Nil Map Panic

This repository demonstrates a common error in Go: panicking due to accessing a nil map.  The `bug.go` file shows the erroneous code, while `bugSolution.go` provides a corrected version.

This type of error can be difficult to debug, as it doesn't always lead to clear error messages.  The solution involves checking for nil before accessing the map, or using the `make()` function to initialize it.