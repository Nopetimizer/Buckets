# Buckets: Data Structures Implementation Library for Go

Buckets is a Go package that provides implementations of various data structures commonly used in computer science and software development. From linked lists to trees, Buckets aims to offer efficient and easy-to-use data structures to Go developers. Inspired by the data structures available in Java, Buckets aims to gradually add all these structures to the Go ecosystem.

## Features

- **Modular Design**: Each data structure is implemented as a separate module, allowing developers to import only the structures they need.
- **Efficient Implementations**: Buckets prioritizes efficient memory usage and performance, providing implementations optimized for various use cases.
- **Java-inspired API**: The API design is inspired by the data structures available in Java, making it familiar to developers with experience in Java programming.
- **Comprehensive Documentation**: Buckets provides detailed documentation for each data structure, including usage examples and performance characteristics.

## Available Data Structures

- **Linked List**: Implements both singly and doubly linked lists.
- **Stack**: Provides a basic stack implementation with push, pop, and peek operations.
- **Queue**: Offers a queue implementation with enqueue and dequeue operations.
- **Tree**: Implements various tree data structures such as binary search tree, AVL tree, and red-black tree.
- **HashMap**: Provides a hash map implementation with support for key-value pairs.

## Installation

To install Buckets, use `go get`:

```bash
go get github.com/nopetimizer/buckets
```

## Usage

Here's an example of how to use the linked list data structure from Buckets:

```go
package main

import (
    "fmt"
    "github.com/nopetimizer/buckets/linkedlist"
)

func main() {
    // Create a new linked list
    list := linkedlist.New()

    // Add elements to the linked list
    list.Add(1)
    list.Add(2)
    list.Add(3)

    // Print the elements of the linked list
    fmt.Println("Linked List:", list.Elements())

    // Remove an element from the linked list
    list.Remove(2)

    // Print the elements of the linked list after removal
    fmt.Println("Linked List after removal:", list.Elements())
}
```

## Contributing

Contributions are welcome! If you have ideas for new data structures, improvements, or find any bugs, please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
