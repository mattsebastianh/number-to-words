# Number to Words

This project provides a Python utility for converting numbers into their English word representations. It is designed to be simple, efficient, and easy to integrate into other Python projects or use as a standalone script.

## Features
- Convert integers to English words (e.g., `123` → "one hundred twenty-three")
- Handles numbers from zero up to billions
- Simple API for integration
- No external dependencies

## Usage
1. Clone the repository:
	```bash
	git clone [repo_URL]
	```
2. Run the script:
	```bash
	python num_to_words.py
	```
3. Import and use in your own Python code:
	```python
	from num_to_words import number_to_words
	print(number_to_words(123))  # Output: 'one hundred twenty-three'
	```

## Project Scope
- Focused on converting whole numbers to English words
- Does not handle decimals, negative numbers, or other languages
- Designed for educational, utility, and integration purposes

## License
This project is licensed under the MIT License. See the LICENSE file for details.
