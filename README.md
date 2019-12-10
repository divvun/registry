# Divvun Repository Registry

## Overview

[![Overview](overview.svg)](https://raw.githack.com/divvun/registry/master/overview.svg)

## Software

| Repository | Description | Programming Language(s) | Platform | License | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CI&nbsp;Report&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| ---------- | ----------- | ----------------------- | -------- | ------- | --------- |
| [divvun-api](https://github.com/divvun/divvun-api) | API server | Rust | Any | Apache 2.0 OR MIT | |
| [divvun-bundler](https://github.com/divvun/divvun-bundler) | Tool for creating installers and bundlers for various bits and bobs | Rust | Any | Apache 2.0 OR MIT | |
| divvun-bundler-mso | Necessary proprietary fork for bundling MS Office spellers, ask Børre for access | Rust | Windows | Proprietary |
| [divvunspell](https://github.com/divvun/divvunspell) | Spell checking engine and library | Rust (FFI to other languages) | Any | Apache 2.0 OR MIT | [![Actions Status](https://github.com/divvun/divvunspell/workflows/Continuous%20Integration/badge.svg)](https://github.com/divvun/divvunspell/actions) |
| divvunspell-mso | Necessary proprietary fork for Microsoft Office support, ask Børre for access | Rust | Windows | Proprietary | [![Build Status](https://dev.azure.com/divvun/msoffice/_apis/build/status/divvun.ci-divvunspell-mso?branchName=master)](https://dev.azure.com/divvun/msoffice/_build/latest?definitionId=3&branchName=master) | 
| [divvunspell-nodejs](https://github.com/divvun/divvunspell-nodejs) | Node.js bindings to DivvunSpell | JavaScript (node.js) | Any | Apache 2.0 OR MIT | |
| [giellakbd-android](https://github.com/divvun/giellakbd-android) | Open source keyboard implementation for Android (used in kbdgen) | Java, Kotlin | Android | Apache 2.0 | [![Build Status](https://travis-ci.org/divvun/giellakbd-android.svg?branch=master)](https://travis-ci.org/divvun/giellakbd-android) |
| [giellakbd-ios](https://github.com/divvun/giellakbd-ios) | Open source keyboard implementation for iOS (used in kbdgen) | Swift | iOS | Apache 2.0 OR MIT | |
| [kbdi](https://github.com/divvun/kbdi) | Small utility packaged with Windows keyboards to configure the registry and enable custom locales. | Rust | Windows | ISC | |
| [kbdgen](https://github.com/divvun/kbdgen) | The keyboard layout generator, outputting Android, iOS, Windows, macOS and Linux keyboard layouts. | Python 3 | Target-dependent  | Apache 2.0 OR MIT | [![Build Status](https://travis-ci.org/divvun/kbdgen.svg?branch=master)](https://travis-ci.org/divvun/kbdgen) |
| [kbdgen-rs](https://github.com/divvun/kbdgen-rs) | Support library and binaries for kbdgen | Rust | Target-dependent | Apache 2.0 OR MIT | [![Build Status](https://dev.azure.com/divvun/kbdgen-rs/_apis/build/status/divvun.kbdgen-rs?branchName=master)](https://dev.azure.com/divvun/kbdgen-rs/_build/latest?definitionId=4&branchName=master) |
| [macdivvun-service](https://github.com/divvun/macdivvun-service) | Spell checking service for macOS | Swift | macOS | Apache 2.0 OR MIT | [![Build Status](https://dev.azure.com/divvun/divvun-service/_apis/build/status/divvun.macdivvun-service?branchName=master)](https://dev.azure.com/divvun/divvun-service/_build/latest?definitionId=4&branchName=master) |
| [pahkat](https://github.com/divvun/pahkat) | Server generator + web backend (under development) for Páhkat package management standard. | Rust | Any | Apache 2.0 OR MIT | |
| [pahkat-client-core](https://github.com/divvun/pahkat-client-core) | Core client implementation, for use in UI implementations | Rust | Any | Apache 2.0 OR MIT | [![Build Status](https://dev.azure.com/divvun/divvun-installer/_apis/build/status/divvun.pahkat-client-core?branchName=master)](https://dev.azure.com/divvun/divvun-installer/_build/latest?definitionId=6&branchName=master) |
| [pahkat-client-sdk-swift](https://github.com/divvun/pahkat-client-sdk-swift) | Pahkat Core SDK for Swift | Swift | macOS/iOS | Apache 2.0 OR MIT | |
| [pahkat-client-sdk-java](https://github.com/divvun/pahkat-client-sdk-java) | Pahkat Core SDK for Java/Kotlin | Java/Kotlin | JVM/Android | Apache 2.0 OR MIT | |
| [pahkat-client-macos](https://github.com/divvun/pahkat-client-macos) | macOS UI client for Páhkat package manager | Swift | macOS | GPL-3.0 | [![Build Status](https://dev.azure.com/divvun/divvun-installer/_apis/build/status/divvun.pahkat-client-macos?branchName=master)](https://dev.azure.com/divvun/divvun-installer/_build/latest?definitionId=8&branchName=master) |
| [pahkat-client-windows](https://github.com/divvun/pahkat-client-windows) | Windows UI client for Páhkat package manager | C# | Windows 8.1+ | GPL-3.0 | [![Build Status](https://dev.azure.com/divvun/divvun-installer/_apis/build/status/divvun.pahkat-client-windows?branchName=master)](https://dev.azure.com/divvun/divvun-installer/_build/latest?definitionId=5&branchName=master) |
| [windivvun-service](https://github.com/divvun/windivvun-service) | Spell checking service for Windows 8.1+ | Rust | Windows | Apache 2.0 OR MIT | [![Build Status](https://dev.azure.com/divvun/divvun-service/_apis/build/status/divvun.windivvun-service?branchName=master)](https://dev.azure.com/divvun/divvun-service/_build/latest?definitionId=2&branchName=master) |
| [xkb-parser](https://github.com/divvun/xkb-parser) | A parser for X11 `.xkb` keyboard layout files | Rust | Any | Apache 2.0 OR MIT | [![Build Status](https://dev.azure.com/divvun/xkb-parser/_apis/build/status/divvun.xkb-parser?branchName=master)](https://dev.azure.com/divvun/xkb-parser/_build/latest?definitionId=2&branchName=master) |


## Resources

### Keyboards

| Repository | Spoken Language(s) | License | CI Report |
| ---------- | ------------------ | ------- | --------- |
| [giellalt/keyboard-crk](https://github.com/giellalt/keyboard-crk) | Plains Cree | XXX | [![Build Status](https://dev.azure.com/giellalt/crk/_apis/build/status/giellalt.keyboard-crk?branchName=master)](https://dev.azure.com/giellalt/crk/_build/latest?definitionId=1&branchName=master) |
| [giellalt/keyboard-mns](https://github.com/giellalt/keyboard-mns) | Mansi | XXX | [![Build Status](https://dev.azure.com/giellalt/mns/_apis/build/status/giellalt.lang-mns?branchName=master)](https://dev.azure.com/giellalt/mns/_build/latest?definitionId=15&branchName=master) |
| [giellalt/keyboard-sma](https://github.com/giellalt/keyboard-sma) | Southern Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/sma/_apis/build/status/giellalt.keyboard-sma?branchName=master)](https://dev.azure.com/giellalt/sma/_build/latest?definitionId=3&branchName=master) |
| [giellalt/keyboard-sme](https://github.com/giellalt/keyboard-sme) | Northern Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/sme/_apis/build/status/giellalt.keyboard-sme?branchName=master)](https://dev.azure.com/giellalt/sme/_build/latest?definitionId=6&branchName=master) |
| [giellalt/keyboard-smj](https://github.com/giellalt/keyboard-smj) | Lule Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/smj/_apis/build/status/giellalt.keyboard-smj?branchName=master)](https://dev.azure.com/giellalt/smj/_build/latest?definitionId=5&branchName=master) |
| [giellalt/keyboard-smn](https://github.com/giellalt/keyboard-smn) | Inari Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/smn/_apis/build/status/giellalt.keyboard-smn?branchName=master)](https://dev.azure.com/giellalt/smn/_build/latest?definitionId=2&branchName=master) |
| [giellalt/keyboard-sms](https://github.com/giellalt/keyboard-sms) | Skolt Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/sms/_apis/build/status/giellalt.keyboard-sms?branchName=master)](https://dev.azure.com/giellalt/sms/_build/latest?definitionId=4&branchName=master) |

### Languages

| Repository | Spoken Language(s) | License | CI Report |
| ---------- | ------------------ | ------- | --------- |
| [giellalt/lang-crk](https://github.com/giellalt/lang-crk) | Plains Cree | XXX | [![Build Status](https://dev.azure.com/giellalt/crk/_apis/build/status/giellalt.lang-crk?branchName=master)](https://dev.azure.com/giellalt/crk/_build/latest?definitionId=12&branchName=master) |
| [giellalt/lang-mns](https://github.com/giellalt/lang-mns) | Mansi | XXX | [![Build Status](https://dev.azure.com/giellalt/mns/_apis/build/status/giellalt.keyboard-mns?branchName=master)](https://dev.azure.com/giellalt/mns/_build/latest?definitionId=14&branchName=master) |
| [giellalt/lang-sma](https://github.com/giellalt/lang-sma) | Southern Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/sma/_apis/build/status/giellalt.lang-sma?branchName=master)](https://dev.azure.com/giellalt/sma/_build/latest?definitionId=8&branchName=master) |
| [giellalt/lang-sme](https://github.com/giellalt/lang-sme) | Northern Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/sme/_apis/build/status/giellalt.lang-sme?branchName=master)](https://dev.azure.com/giellalt/sme/_build/latest?definitionId=9&branchName=master) |
| [giellalt/lang-smj](https://github.com/giellalt/lang-smj) | Lule Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/smj/_apis/build/status/giellalt.lang-smj?branchName=master)](https://dev.azure.com/giellalt/smj/_build/latest?definitionId=10&branchName=master) |
| [giellalt/lang-smn](https://github.com/giellalt/lang-smn) | Inari Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/smn/_apis/build/status/giellalt.lang-smn?branchName=master)](https://dev.azure.com/giellalt/smn/_build/latest?definitionId=7&branchName=master) |
| [giellalt/lang-sms](https://github.com/giellalt/lang-sms) | Skolt Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/sms/_apis/build/status/giellalt.lang-sms?branchName=master)](https://dev.azure.com/giellalt/sms/_build/latest?definitionId=11&branchName=master) |
