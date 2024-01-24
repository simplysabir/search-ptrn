# Pattern Search CLI Tool

## Overview

This is a simple command-line interface (CLI) tool written in Rust that allows you to search for a specified pattern within a file. The tool takes a pattern and a file path as inputs, reads the content of the file, and prints the lines containing the specified pattern.

## Features

- **Pattern Search**: Quickly find lines in a file that contain a specific pattern.
- **Easy to Use**: Straightforward command-line interface with minimal setup.

## Installation

Ensure you have Rust installed on your system. You can install the tool by cloning the repository and building the binary using the following commands:

```
git clone https://github.com/simplysabir/search-ptrn.git
cd search-ptrn
cargo build --release
```
The compiled binary will be available in the target/release/ directory.

or simply install it from [crates.io](https://crates.io/crates/search-ptrn)

## Usage

```
search-ptrn -- word_to_search_for specify_file_path
```

## Error Handling

The tool provides informative error messages in case of file reading or other execution issues, making it easier to identify and troubleshoot problems.

## Contributions
Contributions to this project are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

For more information about my other projects and contributions, visit [GitHub](https://github.com/simplysabir) or [Portfolio](https://simplysabir.live/).