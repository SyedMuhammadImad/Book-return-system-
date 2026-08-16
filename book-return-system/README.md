# Book Return System

A console-based C++ application that simulates how a library processes returned books.
Returned books are stored in a **stack**, so the most recently returned book is the first
one shelved (LIFO order) — mirroring how a physical return-cart is often handled.

## Features

- Add a returned book (title, author, year)
- Remove the most recently returned book (pop)
- View the total number of books returned
- Print a full receipt of all books currently in the stack
- Basic error handling for full/empty stack conditions

## Data Structure

- **Stack** implemented from scratch using a fixed-size array of `Book` structs
- Core operations: `push`, `pop`, `peek`, `isEmpty`, `size`

## How to Run

```bash
g++ main.cpp -o book_return_system
./book_return_system
```

## Menu Options

```
1. Add Returned Book
2. Remove Top Book
3. Total books returned
4. Print Receipt of Books
5. Exit
```

## Tech

- C++
- Standard Template Library (`<iostream>`, `<string>`)
