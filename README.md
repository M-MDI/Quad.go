# Go Quad Problems

## Overview

This repository contains Go solutions for the Quad problems. Each problem focuses on printing a valid rectangle with given dimensions using ASCII characters. These exercises are designed to improve your understanding of loops, conditionals, and string manipulation in Go.

## Problems Included

1. **QuadA**: Print a rectangle with width x and height y using 'o' for corners and '-' and '|' for edges.
2. **QuadB**: Print a rectangle with width x and height y using '*' for corners and '/' and '\' for edges.
3. **QuadC**: Print a rectangle with width x and height y using 'A', 'B', and 'C' characters for corners and edges.
4. **QuadD**: Print a rectangle with width x and height y using 'A', 'B', and 'C' characters for corners and edges, with an additional 'B' character filling the inner space.
5. **QuadE**: Print a rectangle with width x and height y using 'A', 'B', 'C' characters for corners and edges, with an additional 'B' character filling the inner space and 'C' character for the last row.

## Requirements

- Go 1.x or higher (replace x with the minimum version required)

## Project Structure

```
go-quad-problems/
├── quadA.go
├── quadB.go
├── quadC.go
├── quadD.go
├── quadE.go
├── README.md
└── LICENSE
```

## Usage

Each problem is implemented in a separate Go file. To test the solutions, simply execute the corresponding Go file using the `go run` command.

For example, to run QuadA:

```
go run quadA.go 5 3
```

This will print a rectangle with width 5 and height 3 using the QuadA pattern.

### Example Output

For QuadA with width 5 and height 3:

```
o---o
|   |
o---o
```

## Implementation Details

Each quad function follows this general structure:

1. Take width (x) and height (y) as input parameters.
2. Validate input parameters (ensure they are positive integers).
3. Print the top row of the rectangle.
4. Print the middle rows (if any).
5. Print the bottom row (if height > 1).

The specific characters used and their placement vary between the different quad problems.

## Contributing

Contributions and improvements are welcome! Here's how you can contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/NewQuadProblem`)
3. Implement your changes
4. Commit your changes (`git commit -m 'Add a new Quad problem'`)
5. Push to the branch (`git push origin feature/NewQuadProblem`)
6. Open a Pull Request

Please ensure your code follows Go best practices and includes appropriate comments.

## Testing

To ensure the correctness of your solutions, consider adding test cases for each quad problem. You can use Go's built-in testing framework to create and run tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
ig :=Mehdim_dev
Mehdi/Morningstar/Zangief

Project Link: [https://github.com/yourusername/go-quad-problems](https://github.com/yourusername/go-quad-problems)
