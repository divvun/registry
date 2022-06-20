# Divvun Repository Registry

An overview of most repositories in [Divvun](https://github.com/divvun).

All repos are listed with core info like:
- license
- short description, programming language and target platforsm (non-linguistic repos)
- a four-grade maturity cliassification (linguistic resources)
- open issues and build status

## Content

- [Product Software](#product-software)
- [Support Software](#support-software)
- [Linguistic resources](#linguistic-resources)
- [Giella Core](#giella-core)
- [Templates](#templates)

## Product Software

| Repository | Description | Programming Language(s) | Platform | License | Open&nbsp;Issues | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CI&nbsp;Report&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| ---------- | ----------- | ----------------------- | -------- | ------- | --------- | --------- |
| [divvun-manager-macos](https://github.com/divvun/divvun-manager-macos) | macOS UI client for Páhkat package manager | Swift | macOS | GPL-3.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-manager-macos)](https://github.com/divvun/divvun-manager-macos/issues)  | [![Build Status](https://divvun-tc.thetc.se/api/github/v1/repository/divvun/divvun-manager-macos/main/badge.svg)](https://github.com/divvun/divvun-manager-macos/actions) |
| [divvun-manager-windows](https://github.com/divvun/divvun-manager-windows) | Windows UI client for Páhkat package manager | C# | Windows 8.1+ | GPL-3.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-manager-windows)](https://github.com/divvun/divvun-manager-windows/issues)  | [![Build Status](https://divvun-tc.thetc.se/api/github/v1/repository/divvun/divvun-manager-windows/main/badge.svg)](https://github.com/divvun/divvun-manager-windows/actions) |
| [divvun-keyboard](https://github.com/divvun/divvun-keyboard) | Mobile phone and tablet keyboard app (meta repo) | - | Android, iOS | - | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-keyboard)](https://github.com/divvun/divvun-keyboard/issues)  | [![Build Status](https://divvun-tc.thetc.se/api/github/v1/repository/divvun/divvun-keyboard/main/badge.svg)](https://github.com/divvun/divvun-keyboard/actions) |
| [divvun-dev-keyboard](https://github.com/divvun/divvun-dev-keyboard) | Mobile phone keyboard app for testing (meta) | - | Android, iOS | - | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-dev-keyboard)](https://github.com/divvun/divvun-dev-keyboard/issues)  | [![Build Status](https://divvun-tc.thetc.se/api/github/v1/repository/divvun/divvun-dev-keyboard/main/badge.svg)](https://github.com/divvun/divvun-dev-keyboard/actions) |
| [divvun-gramcheck-web](https://github.com/divvun/divvun-gramcheck-web) | Grammar checker plugin for MS&nbsp;Office & GoogleDocs | TypeScript | MS&nbsp;Office, GoogleDocs | GPL-3.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-gramcheck-web)](https://github.com/divvun/divvun-gramcheck-web/issues) | |

## Support Software

| Repository | Description | Programming Language(s) | Platform | License | Open&nbsp;Issues | &nbsp;&nbsp;CI&nbsp;Report&nbsp;&nbsp; |
| ---------- | ----------- | ----------------------- | -------- | ------- | --------- | --------- |
| [divvun-api             ](https://github.com/divvun/divvun-api)             | API server                                                        | Rust                  | Any             | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-api)](https://github.com/divvun/divvun-api/issues)         | |
| [divvun-bundler         ](https://github.com/divvun/divvun-bundler)         | Tool for creating installers and bundlers for various bits and bobs | Rust                | Any             | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-bundler)](https://github.com/divvun/divvun-bundler/issues) | |
|  divvun-bundler-mso                                                         | Necessary proprietary fork for bundling MS Office spellers, ask Børre for access | Rust   | Windows         | Proprietary       |                                                                                                                                     | |
| [divvunspell            ](https://github.com/divvun/divvunspell)            | Spell checking engine and library                         | Rust (FFI to other languages) | Any             | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvunspell)](https://github.com/divvun/divvunspell/issues) | [![Actions Status](https://github.com/divvun/divvunspell/workflows/CI/badge.svg)](https://github.com/divvun/divvunspell/actions) |
| [ci-divvunspell-mso     ](https://github.com/divvun/ci-divvunspell-mso)     | CI & CD support for Microsoft Office integration                  | Rust                  | Windows (macOS) | Proprietary       | | [![Build Status](https://github.com/divvun/ci-divvunspell-mso/workflows/Generate%20new%20patches/badge.svg)](https://github.com/divvun/ci-divvunspell-mso/actions) |
| [divvunspell-nodejs     ](https://github.com/divvun/divvunspell-nodejs)     | Node.js bindings to DivvunSpell                                   | JavaScript (node.js)  | Any             | - | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvunspell-nodejs)](https://github.com/divvun/divvunspell-nodejs/issues) | |
| [divvunspell-sdk-java   ](https://github.com/divvun/divvunspell-sdk-java)   |    Java bindings to DivvunSpell                                   | Java                  | JVM, Android    | - | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvunspell-sdk-java)  ](https://github.com/divvun/divvunspell-sdk-java/issues)   | |
| [divvunspell-sdk-python ](https://github.com/divvun/divvunspell-sdk-python) |  Python bindings to DivvunSpell                                   | Python                | Any             | - | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvunspell-sdk-python)](https://github.com/divvun/divvunspell-sdk-python/issues) | |
| [divvunspell-sdk-swift  ](https://github.com/divvun/divvunspell-sdk-swift)  |   Swift bindings to DivvunSpell                                   | Swift                 | macOS, iOS      | MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvunspell-sdk-swift) ](https://github.com/divvun/divvunspell-sdk-swift/issues)  | |
| [giellakbd-android      ](https://github.com/divvun/giellakbd-android)      | Open source keyboard implementation for Android (used in kbdgen)  | Java, Kotlin          | Android         | Apache-2.0        | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/giellakbd-android)](https://github.com/divvun/giellakbd-android/issues) | [![Build Status](https://travis-ci.org/divvun/giellakbd-android.svg?branch=master)](https://travis-ci.org/divvun/giellakbd-android) |
| [giellakbd-ios          ](https://github.com/divvun/giellakbd-ios)          | Open source keyboard implementation for iOS (used in kbdgen)      | Swift                 | iOS             | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/giellakbd-ios)](https://github.com/divvun/giellakbd-ios/issues) | |
| [gut                    ](https://github.com/divvun/gut)                    | A Git(Hub) multirepo maintenance tool                             | Rust                  | Any             | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/gut)](https://github.com/divvun/gut/issues) | [![Build Status](https://divvun-tc.thetc.se/api/github/v1/repository/divvun/gut/main/badge.svg)](https://github.com/divvun/gut/actions) |
| [kbdi                   ](https://github.com/divvun/kbdi)                   | Small utility packaged with Windows keyboards to configure the registry and enable custom locales | Rust | Windows | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/kbdi)](https://github.com/divvun/kbdi/issues) | [![Build Status](https://github.com/divvun/kbdi/workflows/CI/badge.svg)](https://github.com/divvun/kbdi/actions) |
| [kbdgen                 ](https://github.com/divvun/kbdgen)                 | The keyboard layout generator, outputting Android, iOS, Windows, macOS and Linux keyboard layouts | Rust/Python | macOS / Linux / Windows | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/kbdgen)](https://github.com/divvun/kbdgen/issues) | [![Build Status](https://github.com/divvun/kbdgen/workflows/CI/badge.svg)](https://github.com/divvun/kbdgen/actions) |
| [macdivvun-service      ](https://github.com/divvun/macdivvun-service)      | Spell checking service for macOS                                  | Swift                 | macOS | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/macdivvun-service)](https://github.com/divvun/macdivvun-service/issues) | [![Actions Status](https://github.com/divvun/macdivvun-service/workflows/CI/badge.svg)](https://github.com/divvun/macdivvun-service/actions) |
| [pahkat                 ](https://github.com/divvun/pahkat)                 | Server generator + web backend (under development) for Páhkat package management standard | Rust | Any      | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/pahkat)](https://github.com/divvun/pahkat/issues) | [![Actions Status](https://github.com/divvun/pahkat/workflows/pahkat-prefix-cli/badge.svg)](https://github.com/divvun/pahkat/actions?query=workflow%3Apahkat-prefix-cli)<br>[![Actions Status](https://github.com/divvun/pahkat/workflows/pahkat-windows-cli/badge.svg)](https://github.com/divvun/pahkat/actions?query=workflow%3Apahkat-windows-cli)<br>[![Actions Status](https://github.com/divvun/pahkat/workflows/pahkat-repomgr/badge.svg)](https://github.com/divvun/pahkat/actions?query=workflow%3Apahkat-repomgr)<br>[![Actions Status](https://github.com/divvun/pahkat/workflows/pahkat-service%20(Windows)/badge.svg)](https://github.com/divvun/pahkat/actions?query=workflow%3A%22pahkat-service+%28Windows%29%22)<br>[![Actions Status](https://github.com/divvun/pahkat/workflows/pahkat-uploader/badge.svg)](https://github.com/divvun/pahkat/actions?query=workflow%3Apahkat-uploader) |
| [pahkat-client-cli      ](https://github.com/divvun/pahkat-client-cli)      | Command line client for Pahkat                                    | Rust                  | Any             | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/pahkat-client-cli)](https://github.com/divvun/pahkat-client-cli/issues) | |
| [pahkat-client-sdk-swift](https://github.com/divvun/pahkat-client-sdk-swift)| Pahkat Core SDK for Swift                                         | Swift                 | macOS / iOS     | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/pahkat-client-sdk-swift)](https://github.com/divvun/pahkat-client-sdk-swift/issues) | |
| [pahkat-client-sdk-java ](https://github.com/divvun/pahkat-client-sdk-java) | Pahkat Core SDK for Java/Kotlin                                   | Java/Kotlin           | JVM / Android   | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/pahkat-client-sdk-java)](https://github.com/divvun/pahkat-client-sdk-java/issues) | [![Build Status](https://github.com/divvun/pahkat-client-sdk-java/workflows/Gradle%20Package/badge.svg)](https://github.com/divvun/pahkat-client-sdk-java/actions) |
| [windivvun-service      ](https://github.com/divvun/windivvun-service)      | Spell checking service for Windows 8.1+                           | Rust                  | Windows         | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/windivvun-service)](https://github.com/divvun/windivvun-service/issues) | [![Build Status](https://github.com/divvun/windivvun-service/workflows/CI/badge.svg)](https://github.com/divvun/windivvun-service/actions) |
| [xkb-parser             ](https://github.com/divvun/xkb-parser)             | A parser for X11 `.xkb` keyboard layout files                     | Rust                  | Any             | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/xkb-parser)](https://github.com/divvun/xkb-parser/issues) | [![Build Status](https://dev.azure.com/divvun/xkb-parser/_apis/build/status/divvun.xkb-parser?branchName=master)](https://dev.azure.com/divvun/xkb-parser/_build/latest?definitionId=2&branchName=master) |


## Linguistic Resources

- [Keyboard layouts](https://giellalt.github.io/KeyboardLayouts.html)
- [Language models](https://giellalt.github.io/LanguageModels.html)
- Private repos are  listed on [this page](https://github.com/divvun/private-registry) (restricted access).

## Giella Core

| Repository | Description        | License | Open&nbsp;Issues | CI&nbsp;Report |
| ---------- | ------------------ | ------- | ---------------- | -------------- |
| [giella-core  ](https://github.com/giellalt/giella-core)   | Core build rules and tools  | [![License: GPL v3](https://img.shields.io/badge/Lic-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) | [![GitHub issues](https://img.shields.io/github/issues/giellalt/giella-core)](https://github.com/giellalt/giella-core/issues) | [![Build Status](https://github.com/giellalt/giella-core/workflows/CI/badge.svg)](https://github.com/giellalt/giella-core/actions) |

## Templates

| Repository | Description        | License | Open&nbsp;Issues |
| ---------- | ------------------ | ------- | ---------------- |
| [template-lang-und    ](https://github.com/giellalt/template-lang-und)     | Language resources and update template | [![License: LGPL v3](https://img.shields.io/badge/Lic-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0) | [![GitHub issues](https://img.shields.io/github/issues/giellalt/template-lang-und)](https://github.com/giellalt/template-lang-und/issues)         | 
| [template-keyboard-und](https://github.com/giellalt/template-keyboard-und) | Keyboard resources and update template | [![License: LGPL v3](https://img.shields.io/badge/Lic-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0) | [![GitHub issues](https://img.shields.io/github/issues/giellalt/template-keyboard-und)](https://github.com/giellalt/template-keyboard-und/issues) | 
