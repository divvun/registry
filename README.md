# Divvun Repository Registry

## Overview

[![Overview](overview.svg)](https://raw.githack.com/divvun/registry/master/overview.svg)

## Software

| Repository | Description | Programming Language(s) | Platform | License | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CI&nbsp;Report&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| ---------- | ----------- | ----------------------- | -------- | ------- | --------- |
| [divvun-api](https://github.com/divvun/divvun-api) | API server | Rust | Any | Apache 2.0 OR MIT | |
| [divvun-bundler](https://github.com/divvun/divvun-bundler) | Tool for creating installers and bundlers for various bits and bobs | Rust | Any | Apache 2.0 OR MIT | |
| divvun-bundler-mso | Necessary proprietary fork for bundling MS Office spellers, ask Børre for access | Rust | Windows | Proprietary |
| [divvunspell](https://github.com/divvun/divvunspell) | Spell checking engine and library | Rust (FFI to other languages) | Any | Apache 2.0 OR MIT | [![Build Status](https://travis-ci.org/divvun/divvunspell.svg?branch=master)](https://travis-ci.org/divvun/divvunspell) |
| divvunspell-mso | Necessary proprietary fork for Microsoft Office support, ask Børre for access | Rust | Windows | Proprietary | |
| [divvunspell-nodejs](https://github.com/divvun/divvunspell-nodejs) | Node.js bindings to DivvunSpell | JavaScript (node.js) | Any | Apache 2.0 OR MIT | |
| [giellakbd-android](https://github.com/divvun/giellakbd-android) | Open source keyboard implementation for Android (used in kbdgen) | Java, Kotlin | Android | Apache 2.0 | [![Build Status](https://travis-ci.org/divvun/giellakbd-android.svg?branch=master)](https://travis-ci.org/divvun/giellakbd-android) |
| [giellakbd-ios](https://github.com/divvun/giellakbd-ios) | Open source keyboard implementation for iOS (used in kbdgen) | Swift | iOS | BSD-3-Clause | |
| [kbdi](https://github.com/divvun/kbdi) | Small utility packaged with Windows keyboards to configure the registry and enable custom locales. | Rust | Windows | ISC | |
| [kbdgen](https://github.com/divvun/kbdgen) | The keyboard layout generator, outputting Android, iOS, Windows, macOS and Linux keyboard layouts. | Python 3 | Target-dependent  | Apache 2.0 OR MIT | [![Build Status](https://travis-ci.org/divvun/kbdgen.svg?branch=master)](https://travis-ci.org/divvun/kbdgen) |
| [macdivvun-service](https://github.com/divvun/macdivvun-service) | Spell checking service for macOS | Swift | macOS | Apache 2.0 OR MIT | [![Build Status](https://dev.azure.com/divvun/divvun-service/_apis/build/status/divvun.macdivvun-service?branchName=master)](https://dev.azure.com/divvun/divvun-service/_build/latest?definitionId=4&branchName=master) |
| [pahkat](https://github.com/divvun/pahkat) | Server generator + web backend (under development) for Páhkat package management standard. | Rust | Any | Apache 2.0 OR MIT | |
| [pahkat-client-core](https://github.com/divvun/pahkat-client-core) | Core client implementation, for use in UI implementations | Rust | Any | Apache 2.0 OR MIT | [![Build Status](https://dev.azure.com/divvun/divvun-installer/_apis/build/status/divvun.pahkat-client-core?branchName=master)](https://dev.azure.com/divvun/divvun-installer/_build/latest?definitionId=6&branchName=master) |
| [pahkat-client-macos](https://github.com/divvun/pahkat-client-macos) | macOS UI client for Páhkat package manager | Swift | macOS | GPL-3.0 | [![Build Status](https://dev.azure.com/divvun/divvun-installer/_apis/build/status/divvun.pahkat-client-macos?branchName=master)](https://dev.azure.com/divvun/divvun-installer/_build/latest?definitionId=8&branchName=master) |
| [pahkat-client-windows](https://github.com/divvun/pahkat-client-windows) | Windows UI client for Páhkat package manager | C# | Windows 8.1+ | GPL-3.0 | [![Build Status](https://dev.azure.com/divvun/divvun-installer/_apis/build/status/divvun.pahkat-client-windows?branchName=master)](https://dev.azure.com/divvun/divvun-installer/_build/latest?definitionId=5&branchName=master) |
| [windivvun-service](https://github.com/divvun/windivvun-service) | Spell checking service for Windows 8.1+ | Rust | Windows | Apache 2.0 OR MIT | [![Build Status](https://dev.azure.com/divvun/divvun-service/_apis/build/status/divvun.windivvun-service?branchName=master)](https://dev.azure.com/divvun/divvun-service/_build/latest?definitionId=2&branchName=master) |

## Resources

### Keyboards

| Repository | Spoken Language(s) | License | URL | CI Report |
| ---------- | ------------------ | ------- | --- | --------- |
| giellalt/keyboard-XXX | XXX | XXX | XXX | XXX |

### Languages

| Repository | Spoken Language(s) | License | URL | CI Report |
| ---------- | ------------------ | ------- | --- | --------- |
| giellalt/lang-XXX | XXX | XXX | XXX | XXX |