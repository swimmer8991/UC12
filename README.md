Certainly! Below is a sample `README.md` file for the `Utils` class you provided:

---

# String Utilities

A simple utility library that provides various string operations to make string manipulations easier and more efficient.

## Table of Contents

- [Features](#features)
- [Examples](#examples)
- [Installation](#installation)
- [Contribution](#contribution)
- [License](#license)

## Features

- **Abbreviate Strings**: Truncate and append a suffix to a string between specified indices.
- **Extract Initials**: Get initials from a string based on specified delimiters.
- **Swap Case**: Convert uppercase characters to lowercase and vice-versa.
- **Wrap Text**: Wrap text at a specified length.

## Examples

Here are some quick examples for the provided utilities:

### Abbreviate

```java
String result = Utils.abbreviate("Hello World", 0, 5, "...");
System.out.println(result);  // Outputs: "Hello..."
```

### Extract Initials

```java
String initials = Utils.initials("John A. Doe", ' ', '.');
System.out.println(initials);  // Outputs: "JAD"
```

### Swap Case

```java
String swapped = Utils.swapCase("Hello WORLD");
System.out.println(swapped);  // Outputs: "hELLO world"
```

### Wrap Text

```java
String wrapped = Utils.wrap("The quick brown fox jumps", 10, "\n", true, " ");
System.out.println(wrapped);
/*
Outputs:
The quick
brown fox
jumps
*/
```

## Installation

To use the provided `Utils` class:

1. Download the `Utils.java` file.
2. Add it to your Java project.
3. Use the methods as shown in the [examples](#examples).

## Contribution

Feel free to fork the repository and submit pull requests! For major changes or feature requests, please open an issue first to discuss your idea.

## License

This project is open-source and available under the MIT License. Use it, modify it, and distribute it as you wish.

---
