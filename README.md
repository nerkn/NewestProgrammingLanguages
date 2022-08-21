# Newest Programming Languages
What will become next c or c++, type safety, memory allocation, garbage collection, whose backing

| Language | [Carbon](https://github.com/carbon-language/carbon-lang) | [V lang](https://github.com/vlang/v) | [Zig](https://github.com/ziglang/zig) | [Rust](https://github.com/rust-lang/rust) | 
| -- | -- | -- | -- | -- | 
| Maintainers| 92 |570 | 540| 4000 |
| Open Issues |  | 630 | 2200 | 5000 | 

# v Lang
Includes webserver, db connectors, so small binary, superfast.
I had problem with capturing surrounding variables with higher order functions, 

## Hello.v
```
fn main() {
	println('Hello World')
}
````

# Carbon

# Zig
## Hello.zig
```
const std = @import("std");

pub fn main() !void {
    const stdout = std.io.getStdOut().writer();
    try stdout.writeAll("Hello World\n");
}

```
