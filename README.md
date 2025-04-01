# NSFW Password Generator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0-blue.svg)](https://github.com/yourusername/nsfw-password-generator)

A single-page static web application that generates secure, memorable, and NSFW passphrases using a mad lib–style, grammar-based approach.

---

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Technical Details](#technical-details)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## Features

- **Mad Lib–Style Generation:**  
  Generate passphrases using natural language templates for a coherent yet random output.
  
- **Custom & Prebuilt Word Lists:**  
  - Enter your own custom words (via text input or file upload)
  - Opt-in/out of prebuilt lists: Animals, Actions, Adjectives, and NSFW/Curse Words (fetched dynamically)
  
- **Dynamic NSFW Data:**  
  Fetches an external JSON list of NSFW/curse words, ensuring your generator stays up to date.
  
- **Special Characters Exclusion:**  
  Optionally exclude specific special characters for added customization.
  
- **Responsive UI:**  
  Built with Tailwind CSS to support light/dark mode and provide a modern look.
  
- **One-Click Clipboard Copy:**  
  Easily copy your generated passphrase(s) with a single button click.

- ++Usage++
1.	Custom Word List:
	•	Type or paste your custom word list into the provided textarea.
	•	Alternatively, upload a CSV or TXT file to auto-populate the list.
2.	Select Prebuilt Word Lists:
	•	Use the checkboxes to include prebuilt lists for Animals, Actions, Adjectives, and NSFW/Curse Words.
3.	Configure Options:
	•	Optionally specify special characters to exclude.
	•	Set the number of passphrases to generate.
4.	Generate & Copy:
	•	Click “Generate Passphrase(s)” to create your passphrases.
	•	Use the “Copy to Clipboard” button to quickly copy them.
