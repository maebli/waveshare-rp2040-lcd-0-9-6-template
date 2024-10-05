# Waveshare-rp2040-lcd-0.96 Template

This template aims to help you get going fast with the lcd and raspberry pi pico.
See details about the board under the link:

[Waveshare RP2040-LCD-0.96 Resources](https://www.waveshare.com/wiki/Template:RP2040-LCD-0.96_Resources)

The template is derived from the repository [rp-hal-boards](https://github.com/rp-rs/rp-hal-boards).

``` shell 
cargo install cargo-generate
cargo generate maebli/waveshare-rp2040-lcd-0-9-6-template --name my-project
cd waveshare-rp2040-lcd-0-9-6-template
```

# Pre-Requisites
## Tool chain setup 
### Windows 

``` powershell
PS> winget install Rustlang.Rustup
PS> irm https://github.com/probe-rs/probe-rs/releases/latest/download/probe-rs-tools-installer.ps1 | iex
PS> rustup target add thumbv6m-none-eabi
PS> cargo install elf2uf2-rs
PS> cargo run --release  
```
