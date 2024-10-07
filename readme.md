# minigrep

A command line tool that searches for a string in a file!

## Installation

Install Rust
  ```
  curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
  ```
Clone the repository
  ```
  git clone https://github.com/theAnuragMishra/minigrep.git
  ```
Run
```
cargo run -- to poem.txt
```

## Usage

To search for a string {query} in a file located at {file_path.txt}
```
cargo run -- {query} {file_path}
```


To do a case insensitive search
```
IGNORE_CASE=1 cargo run -- {query} {file_path}
```


To write the output result lines to the file located at {output_path}
```
cargo run -- {query} {file_path} > {output_path}
```
