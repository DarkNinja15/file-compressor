## File Compressor (Written in Rust)

This is a simple file compressor that uses the flate2 crate to compress files. It is a simple command line tool that takes a file as input and compresses it. The compressed file is saved in the same directory as the input file.

### Usage

### Step 1 - Clone the repository

```bash
git clone https://github.com/DarkNinja15/file-compressor.git
```

### Step 2 - Build and run the project

```bash
cd file-compressor
cargo run <notes.pdf> <notes_compress>
```

Note: The first argument is the input file and the second argument is the output file.