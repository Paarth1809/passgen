# Password Generator

A simple Python script to generate secure random passwords using letters, digits, and punctuation.

## Features

- Generates passwords of customizable length
- Uses uppercase, lowercase, digits, and special characters
- Easy to use from the command line

## Usage

1. Make sure you have Python installed.
2. Run the script:

   ```sh
   python passgen.py
   ```

3. The script will print a randomly generated password.

## Customization

To generate a password of a specific length, modify the `length` parameter in the `generate_password` function in [`passgen.py`](passgen.py):

```python
password = generate_password(16)  # Generates a 16-character password
```

## Requirements

- Python 3.x

## License

This project is licensed under the MIT
