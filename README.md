# Benchmarks

[Rust](https://www.rust-lang.org) is all about performance. Benchmarks are built in and can test the performance of your code.

## Usage

````
cargo bench
    Finished bench [optimized] target(s) in 0.00s
     Running target/release/deps/benchmarks-b7945757a6ff7172

running 2 tests
test tests::bench_add_two       ... bench:           0 ns/iter (+/- 0)
test tests::bench_xor_1000_ints ... bench:          54 ns/iter (+/- 4)

test result: ok. 0 passed; 0 failed; 0 ignored; 2 measured; 0 filtered out
o```
````
