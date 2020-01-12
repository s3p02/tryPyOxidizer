# Install Rust

```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh```

Confirm installation

```rustc --version```

# Install PyOxidizer

```cargo install pyoxidizer```

Confirm installation

```pyoxidizer```

# Try Sample App

```pyoxidizer init pyapp```

Edit pyoxidizer.toml file, un-comment lines 69-72 and fill appropriately.
Comment out line 90 and finally un-comment lines 93 & 94 and fill accordingly.

Build:

```pyoxidizer build```

I'm compiling an executable on my mac, so the binary will ben in:

```~pyapp/build/target/x86_64-apple-darwin/debug/pyapp```

Hello PyOxidizer!