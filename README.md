# Interactive Number System & 2's Complement Visualizer

A beginner-friendly, single-file web app that shows how computers store numbers. It was built as an MCA Computer Aptitude mini-project.

## Features

### Mode A: Multi-Base Converter
- Enter a decimal integer and instantly see its Binary, Octal and Hexadecimal forms.
- A step-by-step **division-by-2 table** (Dividend, Quotient, Remainder) shows how the binary result is derived.

### Mode B: 8-bit Signed Integers
- Enter any integer from **-128 to +127**.
- For negative numbers, a 3-step breakdown is shown:
  1. Magnitude in 8-bit binary
  2. 1's complement (flip all bits)
  3. 2's complement (add 1)
- Positive numbers show their direct 8-bit representation.
- The **sign bit (MSB)** is highlighted in a distinct colour.
- The result is verified using bit weights (-128, 64, 32, ... 1).

### Input validation
Warns the user about non-integer input and about values outside the 8-bit signed range.

## Example

| Input | Magnitude  | 1's complement | 2's complement |
|-------|------------|----------------|----------------|
| -13   | `00001101` | `11110010`     | `11110011`     |

## How to run

1. Download or clone this repository.
2. Double-click `index.html` to open it in any browser.

No installation, libraries or internet connection are needed.

```bash
git clone https://github.com/<your-username>/number-system-twos-complement-visualizer.git
```

## Technologies used

- **HTML5**: page structure
- **CSS3**: responsive card-based layout
- **JavaScript (vanilla)**: conversion logic and validation

## Concepts demonstrated

- Repeated division method for base conversion
- 1's complement (bit flipping)
- 2's complement (1's complement + 1)
- Sign bit and the 8-bit signed range (-128 to +127)

## Project structure

```
index.html   # HTML, CSS and JavaScript in one file
README.md    # Project description
```

## Author

Your Name, MCA, Your University
