---
title: "hello world"
date: 0
draft: false
---

the `use` keyword imports a dependency into scope

```rust {.codebox}

use debug::PrintTrait;

fn main() {
    "Hello, world!".print();
}

```

now, run the tests with `cairo-run hello_world.cairo`

```bash
[DEBUG]	Hello, world!                  	(raw: 0x48656c6c6f2c20776f726c6421

Run completed successfully, returning []
```
