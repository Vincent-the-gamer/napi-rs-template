# Napi-rs Template

Napi-rs is a framework to build Node.js libraries in Rust.

# Features

- No `ava`, test your library in `.ts` file using `tsx`
- Default using `async` feature in `napi`
- Quick clean debug build files by `pnpm run clean`

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

Removed: 
- target: `freebsd`.
- target: `aarch64-unknown-linux-musl` because docker build failed.
- target: `aarch64-linux-android`
- job: `Lint`
- test: `aarch64-unknown-linux-gnu`