# Installing Rust

Visit [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install) for the install instructions for Rust.

## Linux && macOS

On Linux, run this command:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

## Windows

On Windows, download and install the `rustup-init.exe` file.

# Installing `probe-rs`

`probe-rs` is used to flash Rust code to the STM microcontrollers. Visit [https://probe.rs/docs/getting-started/installation/](https://probe.rs/docs/getting-started/installation/) for the install instructions for `probe-rs`.

## Linux & macOS

```bash
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/probe-rs/probe-rs/releases/latest/download/probe-rs-tools-installer.sh | sh
```

## Windows

Run the following in PowerShell:

```powershell
irm https://github.com/probe-rs/probe-rs/releases/latest/download/probe-rs-tools-installer.ps1 | iex
```

You may also need to install [Zadig](https://zadig.akeo.ie/), which is used to select "WinUSB" as the driver for your STM board if you face issues with the board not being detected. (See [here](https://probe.rs/docs/getting-started/probe-setup/#windows%3A-winusb-drivers).)
