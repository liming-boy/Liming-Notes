

### Overview of C Literals

- A literal is a direct textual representation of a value assigned to a variable within source code.
    
- Literals represent specific data types directly but do not function as standalone structural programming elements.
    

#### Integer Literals

- **Decimal:** Positive or negative whole numbers (digits 0-9) with no fractional part (e.g., `10`, `-50`).
    
- **Octal:** Base-8 numbers prefixed with a zero `0` (e.g., `025`).
    
- **Hexadecimal:** Base-16 numbers prefixed with `0x` or `0X` (e.g., `0xa1`).
    
- **Binary:** Base-2 numbers prefixed with `0b` (supported by modern C compilers).
    
- **Suffixes:** `U` (unsigned) and `L` (long) can be appended to integers in any order or case (e.g., `89U`, `99998L`).
    

#### Floating-Point Literals

- **Decimal Notation:** Real numbers utilizing a decimal point to separate integer and fractional parts (e.g., `10.55`).
    
- **Scientific Notation:** High-precision values represented using an `e` or `E` for exponentiation (e.g., `100E+4`).
    

#### Character and String Literals

- **Character Literals:** A single character enclosed in straight single quotes (e.g., `'I'`). They typically occupy one byte and can be evaluated for their ASCII integer value.
    
- **Escape Sequences:** Combinations starting with a backslash `\` enclosed in single quotes, used to represent non-printable characters (e.g., `'\n'` for a newline).
    
- **Unicode Literals:** Character representations starting with a `\u` prefix.
    
- **String Literals:** Sequences of characters enclosed in double quotation marks (e.g., `"Hello World"`). Because C lacks a dedicated string variable, these are stored using an array of `char`.
    

#### Array and Structure Initialization

- **Grouped Literals:** Array elements and structure members can be represented and initialized directly using comma-separated values enclosed in curly brackets `{}` (e.g., `{10, 20, 30}`).