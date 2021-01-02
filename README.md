# Building Hum

Hum requires a `rustup` target with no underlying operating system.
To build, I'm generally using the `thumbv7em-none-eabihf` target, which can be added using `rustup target add thumbv7em-none-eabihf` and built with `cargo build --target thumbv7em-none-eabihf`. 