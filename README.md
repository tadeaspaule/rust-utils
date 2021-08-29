### ct

Run `cargo test` one by one for all tests, failing as soon as a test fails (for some reason my `cargo test` runs all tests as if I'm using `--no-fail-fast` even though I'm not).

Another advantage is that it creates a `.tests` file in the project directory, where you can change the order in which tests run (so put the most critical / least expensive ones first for potentially shorter test runs)

### snippets

`nvim -p $(find -path "./src/*.rs" | tr '\n' ' ')` -> open all `.rs` files in nvim, one per tab

