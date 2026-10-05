# PyBrainfuck

PyBrainfuck is a programming language inspired by Brainfuck.

It provides a simpler syntax while still using Brainfuck code internally.

## Hello World

PyBrainfuck supports:

```text
print("Hello World!")
```

Output:

```text
Hello World!
```

The Brainfuck implementation is:

```text
,[>,]<[<]>>>>>>>>[>]<[-]<[-]<[<]>>>>>>>>[.>]
```

## Example

### PyBrainfuck

```text
print("Hello World!")
```

### Output

```text
Hello World!
```

## How It Works

PyBrainfuck translates its higher-level instructions into Brainfuck operations.

For example:

```text
print("Hello World!")
```

is converted into Brainfuck code that processes the characters and prints them using the `.` instruction.

## Project Status

PyBrainfuck is currently in development.

More features are planned, including numbers, variables, arithmetic operations, and additional `print()` functionality.

## License

This project is open source.
