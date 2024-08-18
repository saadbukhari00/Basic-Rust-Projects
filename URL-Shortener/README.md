# Project 2: URL Shortener

## Introduction:
This Rust project is a simple URL shortener that converts long URLs into short URLs and stores the mapping in a file.

## Features:
- Converts long URLs into short ones.
- Stores URL mappings in a file.
- Redirects short URLs to the original long URLs.

## Usage:
```bash
cargo run <url>
```
The mappings are stored in the `src/mapping.txt` file.

## How it works:
- If the input URL starts with "http", the program generates a random 8-character string as the short URL.
- The mapping between the long URL and short URL is stored in the `mapping.txt` file.
- If the input URL is not in the long format, the program assumes it’s a short URL and attempts to redirect it by looking it up in the `mapping.txt` file.

## Potential Improvements:
- Add a web interface for easier usage.
- Implement error handling for invalid URLs.
- Add the ability to customize the length of the short URL.

## Contributing:
If you want to contribute to this project, feel free to fork the repository and submit a pull request.

## Contact:
For any questions or contributions, reach out to me via [GitHub](https://github.com/saadbukhari00) or email: syed4000saad@gmail.com.

