# futures-spsc

Single-producer, single-consumer message queues that are futures-aware.

[![Build Status](https://travis-ci.org/alexcrichton/futures-spsc.svg?branch=master)](https://travis-ci.org/alexcrichton/futures-spsc)

[Documentation](http://alexcrichton.com/futures-spsc)

## Usage

First, add this to your `Cargo.toml`:

```toml
[dependencies]
futures-spsc = { git = "https://github.com/alexcrichton/futures-spsc" }
```

Next, add this to your crate:

```rust
extern crate futures_spsc;
```

# License

`futures-spsc` is primarily distributed under the terms of both the MIT license
and the Apache License (Version 2.0), with portions covered by various BSD-like
licenses.

See LICENSE-APACHE, and LICENSE-MIT for details.
