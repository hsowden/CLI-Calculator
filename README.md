
# Command Line Calculator

A simple Python-based command-line calculator that performs basic arithmetic operations.

## Features

- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)
- Error handling for division by zero
- Invalid operator detection

## Usage

```bash
python calc.py <number1> <operator> <number2>
```

## Arguments

- `<number1>` - First number (integer or decimal)
- `<operator>` - One of: `+`, `-`, `*`, `/`
- `<number2>` - Second number (integer or decimal)

## Examples

### Addition
```bash
python calc.py 5 + 3
# Output: Result: 8.0
```

### Subtraction
```bash
python calc.py 10 - 4
# Output: Result: 6.0
```

### Multiplication
```bash
python calc.py 6 * 7
# Output: Result: 42.0
```

### Division
```bash
python calc.py 20 / 4
# Output: Result: 5.0
```

### Decimal Numbers
```bash
python calc.py 3.5 * 2
# Output: Result: 7.0
```

## Error Handling

The calculator includes error checking for:
- **Missing arguments**: Displays usage message
- **Division by zero**: Displays error message and exits
- **Unknown operator**: Displays error message with the invalid operator

### Example Errors

```bash
python calc.py 5 / 0
# Output: Error: Division by zero

python calc.py 5 % 3
# Output: Error: Unknown operator '%'

python calc.py 5
# Output: Usage: calc.py <number1> <operator> <number2>
```

## Requirements

- Python 3.x

## Exit Codes

- `0` - Successful calculation
- `1` - Error (missing arguments, division by zero, or unknown operator)
