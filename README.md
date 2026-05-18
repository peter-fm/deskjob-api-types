# @deskjob/api-types

Generated TypeScript declarations and JSON Schema for the deskjob API bridge.

This package is generated from Rust types in the deskjob workspace. Regenerate it with:

```sh
cargo run -p deskjob-api-types --bin gen-api-types --release
```

Check for drift without writing files:

```sh
cargo run -p deskjob-api-types --bin gen-api-types -- --check
```

The package is intended for git dependency consumption in the first canvas integration phase.
