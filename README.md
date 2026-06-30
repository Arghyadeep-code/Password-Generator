# Password-Generator

A tiny Python script that generates a random password of a user-specified length.

Description

This repository contains a simple command-line utility (`code.py`) that builds a random password using letters, digits, and punctuation.

Requirements

- Python 3.6+

Usage

1. Clone the repository or download the `code.py` file.
2. Run the script with Python:

   ```bash
   python code.py
   ```

3. Enter the desired password length when prompted (an integer). The generated password will be printed to the terminal.

Example

```
$ python code.py
Kindly mention the length of your password: 16
f3$K)9nBq!tA0z@1
```

Notes & Suggestions

- The script prints the password to standard output; avoid running it in an environment where the terminal history is insecure.
- `string.punctuation` may include characters that some services do not accept. If you plan to use generated passwords for specific services, consider filtering the punctuation set.
- Consider improving the script by adding argument parsing (so length can be passed as a CLI argument), input validation, and an option to copy the password to the clipboard.

License

No license specified. If you'd like, I can add an MIT license file for you.

Contributing

Feel free to open issues or pull requests to add features or fixes.

---

