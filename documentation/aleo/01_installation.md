---
id: installation
title: Installation
sidebar_label: Installation
---
## 1. Install the Prerequisites

### 1.1 Install Git:

**[bit.ly/start-git](https://bit.ly/start-git)**

### 1.2 Install Rust:

**[bit.ly/start-rust](https://bit.ly/start-rust)**

### 1.3 Check the Prerequisites

```bash
git --version
cargo --version
```

### 2. Build Source Code

You can install SnarkVM by building from the source code as follows:

```bash
# Download the source code
git clone https://github.com/AleoHQ/snarkVM
cd snarkvm

# Build in release mode
$ cargo install --path .
```

This will generate the executable `~/.cargo/bin/snarkvm`.

Now to use the SnarkVM CLI, in your terminal, run:
```bash
snarkvm
```

:::info

Dive into some code with [**Hello Aleo**](02_hello.md).

:::


