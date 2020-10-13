# Assignment 12

The U.S. post office has rules about mailing packages. A package cannot be mailed first class if the sum of its length and girth is greater than 100 inches, or if the package weighs more than 70 pounds. The girth is the perimeter around the height and width, where the length is defined as the longest of the three dimensions.

## Your assignment

Write a program that randomly generates a value for the weight of the package (between 0 and 140) and the three dimensions of the package (between 5 and 60). The program should determine the longest dimension of the package, calculate the girth, and consider the weight. The program should then print out **one** of the following messages about this package:

**Package is too large and too heavy.**

**Package is too large.**

**Package is too heavy.**

**Package is acceptable.**

### Sample Outputs

```
Dimensions: 10, 25, 31
Weight: 71

Package is too large and too heavy.
```

```
Dimensions: 10, 20, 29
Weight: 100

Package is too heavy.
```

```
Dimensions: 34, 12, 57
Weight: 10

Package is too large.
```

```
Dimensions: 7, 10, 19
Weight: 55

Package is acceptable.
```

### Grading

As always, your program will be graded on its functionality according to the project specifications and proper code style.

