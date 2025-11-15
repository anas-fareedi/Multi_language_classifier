# Project Title

A simple character-level RNN classifier that predicts whether an input word or name belongs to French, German, or another custom category.
The model is trained from scratch using PyTorch and learns language patterns based on character sequences.

## Overview

This project implements a lightweight multilingual classifier using a vanilla RNN trained on text files for each language category.
It converts every word into a one-hot encoded tensor of characters and feeds it through an RNN to predict the most likely language.
The notebook includes data loading, preprocessing, model training, predictions, and accuracy evaluation — all built with minimal external dependencies.

## Features

- Classifies text into French, German, and other custom categories
- Character-level one-hot encoding
- Simple and interpretable PyTorch RNN architecture
- Real-time predictions on custom inputs
- Training logs with loss and model guesses
- Evaluation script with random sampling accuracy
- Easy to extend with more languages or datasets
- Fully self-contained Jupyter notebook — no external APIs or transformers needed

## Quick Start

Prerequisites:
- Python 3.10+ 

Install and run:
```bash
# Clone the repo
git clone https://github.com/OWNER/REPO.git
cd REPO

# Install dependencies (example)
npm install

# Run locally (example)
npm start
```

Replace the commands above with the actual install/run steps for this project.

## Usage

Short example showing the simplest useful command or code snippet.

```bash
# Example CLI usage
./bin/your-tool --help
```

Or, for a code example:

```js
// Example: import and call
const lib = require('your-lib');
lib.doThing();
```

## Configuration

Note any important environment variables or config files and give examples:

- `ENV_VAR_NAME` — description (default: `value`)

## Tests

How to run tests:

```bash
npm test
```

Adjust to reflect the project's test command.

## Contributing

Contributions are welcome. Please open an issue first to discuss major changes. For small fixes:
1. Fork the repo
2. Create a feature branch
3. Submit a pull request with a clear description

## License

Specify license, e.g. MIT — see LICENSE file.

## Support / Contact

Raise an issue on GitHub or contact the maintainers at: anasfareedi786786@gmail.com
