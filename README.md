# Rust Plugin Engine

## What is this?

This project is an all-in-one plugin engine for Rust projects allowing anyone to easily open their project to third-party addons and extensions.

## Plugin Structure
All plugins in this engine go in the /plugins/src fileder, each one has it's very own `metadata.toml` and `mod.rs` files.

## Usage
To try this example out for yourself:

- Enter the main folder:
```sh
cd ./main
```

- Compile and run the main program:
```sh
cargo run
```

### -- OR --

- Compile and run the main program:
```sh
cargo build --release
```

## Making Custom plugin
### Coming soon!

## Making Custom plugin API
### Coming soon!

## Why is this repo here?

The Horizon team wanted a simple and effective plugin framework for Horizon Game Server [https://github.com/Far-Beyond-Dev/Horizon-Community-Edition](https://github.com/Far-Beyond-Dev/Horizon-Community-Edition) in our research we came accross one such system from nearly 7 years before and with a small amount of tweaking we got it to compile successfully.

## Where do we go from here?

From here we will maintain this plugin system while integrating it into Horizon Community Edition to allow for simplified modification of built-in systems via external code.