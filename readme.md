# minigrep
### A command line tool that searches for a string in a file!

## Installation
- Install Rust
  `$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh`
- Clone the repository
  `git clone https://github.com/theAnuragMishra/minigrep.git`
- `cargo run -- to poem.txt`

## Usage
- `cargo run -- {query} {file_path}` to search for a string {query} in a file located at {file_path.txt}
- `IGNORE_CASE=1 cargo run -- {query} {file_path}` to do a case insensitive search
- `cargo run -- {query} {file_path} > {output_path}` writes the output result lines to the file located at {output_path}, creates one if it doesn't exit

