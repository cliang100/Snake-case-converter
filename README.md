---

# Snake Case Converter

## Overview

The Snake Case Converter is a Python script that converts PascalCase or camelCase strings into snake_case format. It takes a PascalCase or camelCase string as input and returns the equivalent string in snake_case format.

## How It Works

1. **Input String**: Provide a PascalCase or camelCase string as input to the `convert_to_snake_case` function.

2. **Conversion Process**: The script iterates through each character in the input string and checks if it's an uppercase letter. If it is, it adds an underscore ('_') followed by the lowercase version of the letter to a list. If it's not an uppercase letter, it adds the character to the list as is.

3. **Joining**: After iterating through all characters, the script joins the characters in the list to form the snake_case string.

4. **Output**: The snake_case string is returned as the output of the `convert_to_snake_case` function.

## Usage

To use the Snake Case Converter:

1. Run the `main()` function.

2. Provide a PascalCase or camelCase string as input to the `convert_to_snake_case` function.

3. The script will output the equivalent string in snake_case format.

## Example

```python
from snake_case_converter import convert_to_snake_case

print(convert_to_snake_case('IAmAPascalCasedString'))
```

This will output:

```
i_am_a_pascal_cased_string
```

## Note

- This script provides a simple and efficient way to convert PascalCase or camelCase strings into snake_case format.
- You can easily integrate this script into your Python projects to handle string conversions as needed.

---
