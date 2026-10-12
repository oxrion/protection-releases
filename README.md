<p align="center">
  <a href="https://oxrion.com"><img src="https://oxrion.com/brand/oxrion-logo-light.svg" alt="Oxrion" height="40"></a>
</p>

<p align="center"><strong>Oxrion lets you use and distribute your software while keeping its source code private.</strong></p>

# Oxrion Desktop — releases

This repository publishes the downloads of **Oxrion Desktop**, the free app for **PHP source code protection**, and of the **Oxrion command-line tools**. The source of the apps is not published here.

With Oxrion Desktop you:

- **Protect** PHP files, folders or ZIP archives with your Encoder Key (from the [Oxrion Console](https://console.oxrion.com)). One protected file runs on every supported PHP version (8.1–8.5).
- **License** your code to each customer: sign per-host licenses offline, keep a License History, email licenses and send webhooks.
- **Recover** your original source offline with your own recovery key.
- **Keep your keys** in the Vault, one encrypted file on your computer.

Protected code runs on any server with the free [Oxrion loader](https://github.com/oxrion/loader-releases).

## Download

The easiest way is [oxrion.com/download](https://oxrion.com/download). Direct links to the latest release:

| Platform | File |
| --- | --- |
| Windows (x64) | [oxrion-protection-windows-x64.exe](https://github.com/oxrion/protection-releases/releases/latest/download/oxrion-protection-windows-x64.exe) |
| macOS (Universal) | [oxrion-protection-macos-universal.zip](https://github.com/oxrion/protection-releases/releases/latest/download/oxrion-protection-macos-universal.zip) |
| Linux (x64) | [oxrion-protection-linux-x64](https://github.com/oxrion/protection-releases/releases/latest/download/oxrion-protection-linux-x64) |

The command-line tools (`oxrion`, Recovery and Licenser) install with one command — see [oxrion.com/install](https://oxrion.com/install). Raw builds for offline machines are attached to each [release](https://github.com/oxrion/protection-releases/releases/latest).

## Verify a download

Every release includes a `SHA256SUMS` file. On Linux or macOS, in the folder with your download:

```sh
sha256sum --ignore-missing -c SHA256SUMS
```

On Windows (PowerShell), compare the output of `Get-FileHash .\oxrion-protection-windows-x64.exe` with the line for that file in `SHA256SUMS`.

## Learn more

- [How Oxrion works](https://oxrion.com/how-it-works)
- [Documentation](https://docs.oxrion.com) — start with the [Quick start](https://docs.oxrion.com/getting-started/quick-start/)
- [Pricing](https://oxrion.com/pricing) — free plan available
- Questions or problems: [oxrion.com/contact](https://oxrion.com/contact)
