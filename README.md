# Rust fetch

This app reads data from https://jsonplaceholder.typicode.com/todos and creates a CSV file (called `foo.csv`) from that data

## Dependencies:

- [serde](https://crates.io/crates/serde). To serialize `JSON → Rust object` and deserialize `Rust object → CSV row`.
- [reqwest](https://crates.io/crates/reqwest). To perform the requests to the API. Note that we are using the "blocking" (synchronous version) of the package.
- [csv](https://crates.io/crates/csv). To write the CSV file.


## Run it! (in development mode)

Clone the repo, go to the directory and `cargo run`

```
git clone git@github.com:exacs/rust_fetch.git
cd rust_fetch
cargo run
```
