# Instructions
```
Write a function ForEach that, for an int slice, applies a function on each element of that slice.
```

# Expected function
```
func ForEach(f func(int), a []int) {

}
```
# Usage
```
Here is a possible program to test your function :

package main

import "piscine"

func main() {
	a := []int{1, 2, 3, 4, 5, 6}
	piscine.ForEach(piscine.PrintNbr, a)
}
```
# And its output :
```
$ go run .
123456
$
```
# Notions
```
Function literals
Function declaration
Function types
```
