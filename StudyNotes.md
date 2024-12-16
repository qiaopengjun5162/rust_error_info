# Error Info

## 实操

```bash
~/Code via 🅒 base
➜
cd rust/

~/Code/rust via 🅒 base
➜
cargo generate --git git@github.com:tyr-rust-bootcamp/template.git
🤷   Project Name: error-info
🔧   Destination: /Users/qiaopengjun/Code/rust/error-info ...
🔧   project-name: error-info ...
🔧   Generating template ...
🔧   Moving generated files into: `/Users/qiaopengjun/Code/rust/error-info`...
🔧   Initializing a fresh Git repository
✨   Done! New project created /Users/qiaopengjun/Code/rust/error-info

~/Code/rust via 🅒 base took 1m 36.8s
➜
cd error-info/

error-info on  master [?] is 📦 template@0.1.0 via 🦀 1.83.0 via 🅒 base
➜
ls
CHANGELOG.md Cargo.lock   Cargo.toml   README.md    _typos.toml  assets       cliff.toml   deny.toml    src

error-info on  master [?] is 📦 template@0.1.0 via 🦀 1.83.0 via 🅒 base
➜
c

error-info on  master [?] is 📦 template@0.1.0 via 🦀 1.83.0 via 🅒 base
➜
error-info on  master [?] is 📦 template@0.1.0 via 🦀 1.83.0 via 🅒 base
➜ cargo new error-code
    Creating binary (application) `error-code` package
note: see more `Cargo.toml` keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html

error-info on  master [?] is 📦 template@0.1.0 via 🦀 1.83.0 via 🅒 base
➜ touch StudyNotes.md

error-info on  master [?] is 📦 template@0.1.0 via 🦀 1.83.0 via 🅒 base
➜ cargo new error-code-macros
    Creating binary (application) `error-code-macros` package
note: see more `Cargo.toml` keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html

error-info on  master [?] is 📦 template@0.1.0 via 🦀 1.83.0 via 🅒 base
➜ rm -rf src

error-info on  master [?] via 🦀 1.83.0 via 🅒 base
➜ rm -rf error-code-macros

error-info on  master [?] via 🦀 1.83.0 via 🅒 base
➜ cargo new error-code-derive
    Creating binary (application) `error-code-derive` package
      Adding `error-code-derive` as member of workspace at `/Users/qiaopengjun/Code/rust/error-info`
warning: compiling this new package may not work due to invalid workspace configuration

failed to load manifest for workspace member `/Users/qiaopengjun/Code/rust/error-info/error-code-macros`
referenced by workspace at `/Users/qiaopengjun/Code/rust/error-info/Cargo.toml`

Caused by:
  failed to read `/Users/qiaopengjun/Code/rust/error-info/error-code-macros/Cargo.toml`

Caused by:
  No such file or directory (os error 2)
note: see more `Cargo.toml` keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html

error-info on  master [?] via 🦀 1.83.0 via 🅒 base
➜ cargo build
warning: virtual workspace defaulting to `resolver = "1"` despite one or more workspace members being on edition 2021 which implies `resolver = "2"`
note: to keep the current resolver, specify `workspace.resolver = "1"` in the workspace root's manifest
note: to use the edition 2021 resolver, specify `workspace.resolver = "2"` in the workspace root's manifest
note: for more details see https://doc.rust-lang.org/cargo/reference/resolver.html#resolver-versions
   Compiling error-code v0.1.0 (/Users/qiaopengjun/Code/rust/error-info/error-code)
   Compiling error-code-derive v0.1.0 (/Users/qiaopengjun/Code/rust/error-info/error-code-derive)
    Finished `dev` profile [unoptimized + debuginfo] target(s) in 0.39s


➜ pre-commit install
➜ cargo add darling --package error-code-derive
➜ cargo expand --example error
➜ RUST_LOG=info cargo run --example web
➜ cargo add backtrace --dev -p error-code
```

## 参考
