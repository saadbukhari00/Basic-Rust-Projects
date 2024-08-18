# Project 1: SHA256 Password Cracker

## Introduction:
This Rust project is a password cracker that attempts to find a password corresponding to a given SHA256 hash using a dictionary attack on the "rockyou.txt" file.

## Features:
- Reads a hash from the command line and attempts to crack it.
- Uses the SHA256 hashing algorithm to compare hashes.
- Displays the number of attempts made.

## Usage:
```bash
cargo run <sha256sum>
```
Ensure that the `rockyou.txt` file is present in the `src` directory.

## How it works:
- The program reads the password hash provided by the user.
- It then opens the `rockyou.txt` file and iterates through each password.
- For each password, it calculates the SHA256 hash and compares it with the given hash.
- If a match is found, the program outputs the password and exits.

## Potential Improvements:
- Implement multi-threading to speed up the cracking process.
- Add support for different hashing algorithms.
- Allow the user to specify a custom dictionary file.

## Contributing:
If you want to contribute to this project, feel free to fork the repository and submit a pull request.

## Contact:
For any questions or contributions, reach out to me via [GitHub](https://github.com/saadbukhari00) or email: syed4000saad@gmail.com.
