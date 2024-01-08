![example](https://raw.githubusercontent.com/biner88/text-svg-plus/main/image.svg)

Text -> SVG path in rust

[![Latest Version](https://img.shields.io/crates/v/text-svg-plus.svg)](https://crates.io/crates/text-svg-plus)
[![documentation](https://docs.rs/text-svg-plus/badge.svg)](https://docs.rs/text-svg-plus)

![LICENSE](https://img.shields.io/badge/license-MIT-blue.svg)

[Examples](https://github.com/biner88/text-svg-plus/tree/main/examples)

```rust
Text::builder()
    .size(50.0)
    .start(Point { x, y })
    .build(&font, "text-svg");
println!("{}", text.path);
println!("{}", text.data);
```
