# File Compression Utility (Rust)

This is a simple command-line utility written in Rust that compresses a file using Gzip format. It reads the source file, compresses it, and writes the compressed data to the target file. The program also displays the original file size, the compressed file size, and the time taken to perform the compression.

## Features
- Compresses a file into `.gz` format using default Gzip compression.
- Measures the time taken to compress the file.
- Displays the original and compressed file sizes.

## Usage

### Command-line Arguments

This program expects two command-line arguments:
1. `source`: The path of the file to be compressed.
2. `target`: The path where the compressed file will be saved.

### Example

```bash
cargo run -- source.txt target.gz
