# MiniGrep Project

This project is based on the project described in the book of Rust ch-12 -> https://doc.rust-lang.org/book/ch12-01-accepting-command-line-arguments.html

## Commands

### Test

`$ cargo test`

### Run

`$ cargo run body poem.txt`

This is an example and where 'body' is the query to search and poem.txt the file where we want to search.

Another example to search without case sensitive:

`$ CASE_INSENSITIVE=1 cargo run are poem.txt`

## Author
Dany Diaz - 2020