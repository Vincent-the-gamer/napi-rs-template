# Napi-rs Template

Napi-rs is a framework to build Node.js libraries in Rust.

# Features

- No `ava`, test your library in `.ts` file using `tsx`
- Default using `async` feature in `napi`
- Quick clean debug build files by `yarn clean`
- Simplified CI.

# Dev

## Install Deps:

```shell
cargo check
yarn install
```

## Debug

```shell
yarn dev
```

# Publish

> [!NOTE]
> Napi-rs will release multiple packages for different OS,
> so it's better to name your package using `npm scope`.

`Napi-rs` is using `GitHub Actions` to cross build multiple `.node` binaries.

Only:

- `x86_64-apple-darwin`
- `x86_64-pc-windows-msvc`
- `x86_64-unknown-linux-gnu`
- `aarch64-apple-darwin`
- `aarch64-pc-windows-msvc`
