# Napi-rs Template

Napi-rs is a framework to build Node.js libraries in Rust.

# Features

- No `ava`, test your library in `.ts` file using `tsx`
- Default using `async` feature in `napi`
- Quick clean debug build files by `pnpm run clean`

# Dev

Install Deps:

```shell
cargo check
pnpm i
```

# Publish

Napi-rs will release multiple packages for different OS, 
so it's better to name your package using `npm scope.`