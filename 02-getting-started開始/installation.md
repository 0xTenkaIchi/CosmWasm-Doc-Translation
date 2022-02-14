---
sidebar_position: 2
---
# 安裝

這個部分我們會為開發，部署，憧憬和享受Cosmos SDK 鏈的智能合約設置好你的機器。

# Go
你可以根據以下的官方文檔來配置golang。 最新的<code>wasmd</code>版本要求go <code>v1.17+</code>以上的版本。

# Rust
假設你以前從沒有使用過rust，你首先需要安裝一些工具。標準的辦法是使用<code>rustup</code>來維護一些依賴以及處理<code>cargo</code>和<code>rustc</code>多版本的更新。

# 在Linux和Mac安裝Rust
首先，[安裝rustup](https://rustup.rs/)。當你完成安裝後，確保你有wasm32 target：
```bash
rustup default stable
cargo version
# If this is lower than 1.55.0+, update
rustup update stable

rustup target list --installed
rustup target add wasm32-unknown-unknown
```