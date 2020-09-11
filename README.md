# Divvun Repository Registry

## Overview

[![Overview](overview.svg)](https://raw.githack.com/divvun/registry/master/overview.svg)

## Software

| Repository | Description | Programming Language(s) | Platform | License | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CI&nbsp;Report&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| ---------- | ----------- | ----------------------- | -------- | ------- | --------- |
| [divvun-api](https://github.com/divvun/divvun-api) | API server | Rust | Any | Apache-2.0 OR MIT | |
| [divvun-bundler](https://github.com/divvun/divvun-bundler) | Tool for creating installers and bundlers for various bits and bobs | Rust | Any | Apache-2.0 OR MIT | |
| divvun-bundler-mso | Necessary proprietary fork for bundling MS Office spellers, ask Børre for access | Rust | Windows | Proprietary |
| [divvunspell](https://github.com/divvun/divvunspell) | Spell checking engine and library | Rust (FFI to other languages) | Any | Apache-2.0 OR MIT | [![Actions Status](https://github.com/divvun/divvunspell/workflows/Continuous%20Integration/badge.svg)](https://github.com/divvun/divvunspell/actions) |
| divvunspell-mso | Necessary proprietary fork for Microsoft Office support, ask Børre for access | Rust | Windows | Proprietary | [![Build Status](https://dev.azure.com/divvun/msoffice/_apis/build/status/divvun.ci-divvunspell-mso?branchName=master)](https://dev.azure.com/divvun/msoffice/_build/latest?definitionId=3&branchName=master) | 
| [divvunspell-nodejs](https://github.com/divvun/divvunspell-nodejs) | Node.js bindings to DivvunSpell | JavaScript (node.js) | Any | Apache-2.0 OR MIT | |
| [giellakbd-android](https://github.com/divvun/giellakbd-android) | Open source keyboard implementation for Android (used in kbdgen) | Java, Kotlin | Android | Apache-2.0 | [![Build Status](https://travis-ci.org/divvun/giellakbd-android.svg?branch=master)](https://travis-ci.org/divvun/giellakbd-android) |
| [giellakbd-ios](https://github.com/divvun/giellakbd-ios) | Open source keyboard implementation for iOS (used in kbdgen) | Swift | iOS | Apache-2.0 OR MIT | |
| [kbdi](https://github.com/divvun/kbdi) | Small utility packaged with Windows keyboards to configure the registry and enable custom locales. | Rust | Windows | Apache-2.0 OR MIT | |
| [kbdgen](https://github.com/divvun/kbdgen) | The keyboard layout generator, outputting Android, iOS, Windows, macOS and Linux keyboard layouts. | Rust/Python | macOS/Linux/Windows | Apache-2.0 OR MIT | [![Build Status](https://github.com/divvun/kbdgen/workflows/CI/badge.svg)](https://github.com/divvun/kbdgen/actions) |
| [macdivvun-service](https://github.com/divvun/macdivvun-service) | Spell checking service for macOS | Swift | macOS | Apache-2.0 OR MIT | [![Build Status](https://dev.azure.com/divvun/divvun-service/_apis/build/status/divvun.macdivvun-service?branchName=master)](https://dev.azure.com/divvun/divvun-service/_build/latest?definitionId=4&branchName=master) |
| [pahkat](https://github.com/divvun/pahkat) | Server generator + web backend (under development) for Páhkat package management standard. | Rust | Any | Apache-2.0 OR MIT | |
| [pahkat-client-cli](https://github.com/divvun/pahkat-client-cli) | Command line client for Pahkat | Rust | Any | Apache-2.0 OR MIT | |
| [pahkat-client-core](https://github.com/divvun/pahkat-client-core) | Core client implementation, for use in UI implementations | Rust | Any | Apache-2.0 OR MIT | [![Build Status](https://dev.azure.com/divvun/divvun-installer/_apis/build/status/divvun.pahkat-client-core?branchName=master)](https://dev.azure.com/divvun/divvun-installer/_build/latest?definitionId=6&branchName=master) |
| [pahkat-client-sdk-swift](https://github.com/divvun/pahkat-client-sdk-swift) | Pahkat Core SDK for Swift | Swift | macOS/iOS | Apache-2.0 OR MIT | |
| [pahkat-client-sdk-java](https://github.com/divvun/pahkat-client-sdk-java) | Pahkat Core SDK for Java/Kotlin | Java/Kotlin | JVM/Android | Apache-2.0 OR MIT | |
| [pahkat-client-macos](https://github.com/divvun/pahkat-client-macos) | macOS UI client for Páhkat package manager | Swift | macOS | GPL-3.0 | [![Build Status](https://dev.azure.com/divvun/divvun-installer/_apis/build/status/divvun.pahkat-client-macos?branchName=master)](https://dev.azure.com/divvun/divvun-installer/_build/latest?definitionId=8&branchName=master) |
| [pahkat-client-windows](https://github.com/divvun/pahkat-client-windows) | Windows UI client for Páhkat package manager | C# | Windows 8.1+ | GPL-3.0 | [![Build Status](https://dev.azure.com/divvun/divvun-installer/_apis/build/status/divvun.pahkat-client-windows?branchName=master)](https://dev.azure.com/divvun/divvun-installer/_build/latest?definitionId=5&branchName=master) |
| [windivvun-service](https://github.com/divvun/windivvun-service) | Spell checking service for Windows 8.1+ | Rust | Windows | Apache-2.0 OR MIT | [![Build Status](https://github.com/divvun/windivvun-service/workflows/windivvun/badge.svg)](https://github.com/divvun/windivvun-service/actions) |
| [xkb-parser](https://github.com/divvun/xkb-parser) | A parser for X11 `.xkb` keyboard layout files | Rust | Any | Apache-2.0 OR MIT | [![Build Status](https://dev.azure.com/divvun/xkb-parser/_apis/build/status/divvun.xkb-parser?branchName=master)](https://dev.azure.com/divvun/xkb-parser/_build/latest?definitionId=2&branchName=master) |


## Resources

### Keyboards

| Repository | Spoken Language(s) | License | CI Report |
| ---------- | ------------------ | ------- | --------- |
| [giellalt/keyboard-bla](https://github.com/giellalt/keyboard-bla) | Siksika						| XXX | [![Build Status](https://github.com/giellalt/keyboard-bla/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-bla/actions) |
| [giellalt/keyboard-bxr](https://github.com/giellalt/keyboard-bxr) | Russia Buriat					| XXX | [![Build Status](https://github.com/giellalt/keyboard-bxr/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-bxr/actions) |
| [giellalt/keyboard-ces](https://github.com/giellalt/keyboard-ces) | Czech							| XXX | [![Build Status](https://github.com/giellalt/keyboard-ces/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-ces/actions) |
| [giellalt/keyboard-ckt](https://github.com/giellalt/keyboard-ckt) | Chukot						| XXX | [![Build Status](https://github.com/giellalt/keyboard-ckt/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-ckt/actions) |
| [giellalt/keyboard-crk](https://github.com/giellalt/keyboard-crk) | Plains Cree					| XXX | [![Build Status](https://github.com/giellalt/keyboard-crk/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-crk/actions) |
| [giellalt/keyboard-cux](https://github.com/giellalt/keyboard-cux) | Tepeuxila Cuicatec			| XXX | [![Build Status](https://github.com/giellalt/keyboard-cux/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-cux/actions) |
| [giellalt/keyboard-grn](https://github.com/giellalt/keyboard-grn) | Guarani						| XXX | [![Build Status](https://github.com/giellalt/keyboard-grn/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-grn/actions) |
| [giellalt/keyboard-hak](https://github.com/giellalt/keyboard-hak) | Hakka Chinese					| XXX | [![Build Status](https://github.com/giellalt/keyboard-hak/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-hak/actions) |
| [giellalt/keyboard-hdn](https://github.com/giellalt/keyboard-hdn) | Northern Haida				| XXX | [![Build Status](https://github.com/giellalt/keyboard-hdn/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-hdn/actions) |
| [giellalt/keyboard-ike](https://github.com/giellalt/keyboard-ike) | Eastern Canadian Inuktitut	| XXX | [![Build Status](https://github.com/giellalt/keyboard-ike/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-ike/actions) |
| [giellalt/keyboard-ine](https://github.com/giellalt/keyboard-ine) | Indo-European					| XXX | [![Build Status](https://github.com/giellalt/keyboard-ine/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-ine/actions) |
| [giellalt/keyboard-izh](https://github.com/giellalt/keyboard-izh) | Ingrian						| XXX | [![Build Status](https://github.com/giellalt/keyboard-izh/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-izh/actions) |
| [giellalt/keyboard-kca](https://github.com/giellalt/keyboard-kca) | Khanty						| XXX | [![Build Status](https://github.com/giellalt/keyboard-kca/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-kca/actions) |
| [giellalt/keyboard-kio](https://github.com/giellalt/keyboard-kio) | Kiowa							| XXX | [![Build Status](https://github.com/giellalt/keyboard-kio/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-kio/actions) |
| [giellalt/keyboard-kon](https://github.com/giellalt/keyboard-kon) | Kongo							| XXX | [![Build Status](https://github.com/giellalt/keyboard-kon/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-kon/actions) |
| [giellalt/keyboard-kpv](https://github.com/giellalt/keyboard-kpv) | Komi-Zyrian					| XXX | [![Build Status](https://github.com/giellalt/keyboard-kpv/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-kpv/actions) |
| [giellalt/keyboard-lin](https://github.com/giellalt/keyboard-lin) | Lingala						| XXX | [![Build Status](https://github.com/giellalt/keyboard-lin/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-lin/actions) |
| [giellalt/keyboard-liv](https://github.com/giellalt/keyboard-liv) | Liv							| XXX | [![Build Status](https://github.com/giellalt/keyboard-liv/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-liv/actions) |
| [giellalt/keyboard-mdf](https://github.com/giellalt/keyboard-mdf) | Moksha						| XXX | [![Build Status](https://github.com/giellalt/keyboard-mdf/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-mdf/actions) |
| [giellalt/keyboard-mhr](https://github.com/giellalt/keyboard-mhr) | Eastern Mari					| XXX | [![Build Status](https://github.com/giellalt/keyboard-mhr/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-mhr/actions) |
| [giellalt/keyboard-mns](https://github.com/giellalt/keyboard-mns) | Mansi							| XXX | [![Build Status](https://github.com/giellalt/keyboard-mns/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-mns/actions) |
| [giellalt/keyboard-mrj](https://github.com/giellalt/keyboard-mrj) | Western Mari					| XXX | [![Build Status](https://github.com/giellalt/keyboard-mrj/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-mrj/actions) |
| [giellalt/keyboard-myv](https://github.com/giellalt/keyboard-myv) | Erzya							| XXX | [![Build Status](https://github.com/giellalt/keyboard-myv/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-myv/actions) |
| [giellalt/keyboard-nch](https://github.com/giellalt/keyboard-nch) | Central Huasteca Nahuatl		| XXX | [![Build Status](https://github.com/giellalt/keyboard-nch/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-nch/actions) |
| [giellalt/keyboard-nds](https://github.com/giellalt/keyboard-nds) | Low German					| XXX | [![Build Status](https://github.com/giellalt/keyboard-nds/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-nds/actions) |
| [giellalt/keyboard-niv](https://github.com/giellalt/keyboard-niv) | Gilyak						| XXX | [![Build Status](https://github.com/giellalt/keyboard-niv/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-niv/actions) |
| [giellalt/keyboard-nno](https://github.com/giellalt/keyboard-nno) | Norwegian Nynorsk				| XXX | [![Build Status](https://github.com/giellalt/keyboard-nno/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-nno/actions) |
| [giellalt/keyboard-rcf](https://github.com/giellalt/keyboard-rcf) | Réunion Creole French			| XXX | [![Build Status](https://github.com/giellalt/keyboard-rcf/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-rcf/actions) |
| [giellalt/keyboard-rom](https://github.com/giellalt/keyboard-rom) | Romany						| XXX | [![Build Status](https://github.com/giellalt/keyboard-rom/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-rom/actions) |
| [giellalt/keyboard-see](https://github.com/giellalt/keyboard-see) | Seneca						| XXX | [![Build Status](https://github.com/giellalt/keyboard-see/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-see/actions) |
| [giellalt/keyboard-sjd](https://github.com/giellalt/keyboard-sjd) | Kildin Sami					| XXX | [![Build Status](https://github.com/giellalt/keyboard-sjd/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-sjd/actions) |
| [giellalt/keyboard-sju](https://github.com/giellalt/keyboard-sju) | Ume Sami						| XXX | [![Build Status](https://github.com/giellalt/keyboard-sju/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-sju/actions) |
| [giellalt/keyboard-sma](https://github.com/giellalt/keyboard-sma) | Southern Sami					| XXX | [![Build Status](https://github.com/giellalt/keyboard-sma/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-sma/actions) |
| [giellalt/keyboard-sme](https://github.com/giellalt/keyboard-sme) | Northern Sami					| XXX | [![Build Status](https://github.com/giellalt/keyboard-sme/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-sme/actions) |
| [giellalt/keyboard-smj](https://github.com/giellalt/keyboard-smj) | Lule Sami						| XXX | [![Build Status](https://github.com/giellalt/keyboard-smj/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-smj/actions) |
| [giellalt/keyboard-smn](https://github.com/giellalt/keyboard-smn) | Inari Sami					| XXX | [![Build Status](https://github.com/giellalt/keyboard-smn/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-smn/actions) |
| [giellalt/keyboard-sms](https://github.com/giellalt/keyboard-sms) | Skolt Sami					| XXX | [![Build Status](https://github.com/giellalt/keyboard-sms/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-sms/actions) |
| [giellalt/keyboard-srs](https://github.com/giellalt/keyboard-srs) | Sarsi							| XXX | [![Build Status](https://github.com/giellalt/keyboard-srs/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-srs/actions) |
| [giellalt/keyboard-tau](https://github.com/giellalt/keyboard-tau) | Upper Tanana					| XXX | [![Build Status](https://github.com/giellalt/keyboard-tau/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-tau/actions) |
| [giellalt/keyboard-tyv](https://github.com/giellalt/keyboard-tyv) | Tuvinian						| XXX | [![Build Status](https://github.com/giellalt/keyboard-tyv/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-tyv/actions) |
| [giellalt/keyboard-udm](https://github.com/giellalt/keyboard-udm) | Udmurt						| XXX | [![Build Status](https://github.com/giellalt/keyboard-udm/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-udm/actions) |
| [giellalt/keyboard-urj](https://github.com/giellalt/keyboard-urj) | Uralic						| XXX | [![Build Status](https://github.com/giellalt/keyboard-urj/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-urj/actions) |
| [giellalt/keyboard-vot](https://github.com/giellalt/keyboard-vot) | Votic							| XXX | [![Build Status](https://github.com/giellalt/keyboard-vot/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-vot/actions) |
| [giellalt/keyboard-vro](https://github.com/giellalt/keyboard-vro) | Võro							| XXX | [![Build Status](https://github.com/giellalt/keyboard-vro/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-vro/actions) |
| [giellalt/keyboard-yrk](https://github.com/giellalt/keyboard-yrk) | Nenets						| XXX | [![Build Status](https://github.com/giellalt/keyboard-yrk/workflows/Build%20Keyboard/badge.svg)](https://github.com/giellalt/keyboard-yrk/actions) |

### Languages

| Repository | Spoken Language(s) | License | CI Report |
| ---------- | ------------------ | ------- | --------- |
| [giellalt/lang-crk](https://github.com/giellalt/lang-crk) | Plains Cree   | XXX | [![Build Status](https://github.com/giellalt/lang-crk/workflows/Build%20Speller%20Archives%20and%20Bundles/badge.svg)](https://github.com/giellalt/lang-crk/actions) |
| [giellalt/lang-mns](https://github.com/giellalt/lang-mns) | Mansi         | XXX | [![Build Status](https://github.com/giellalt/lang-mns/workflows/Build%20Speller%20Archives%20and%20Bundles/badge.svg)](https://github.com/giellalt/lang-mns/actions) |
| [giellalt/lang-sma](https://github.com/giellalt/lang-sma) | Southern Sami | XXX | [![Build Status](https://github.com/giellalt/lang-sma/workflows/Build%20Speller%20Archives%20and%20Bundles/badge.svg)](https://github.com/giellalt/lang-sma/actions) |
| [giellalt/lang-sme](https://github.com/giellalt/lang-sme) | Northern Sami | XXX | [![Build Status](https://github.com/giellalt/lang-sme/workflows/Build%20Speller%20Archives%20and%20Bundles/badge.svg)](https://github.com/giellalt/lang-sme/actions) |
| [giellalt/lang-smj](https://github.com/giellalt/lang-smj) | Lule Sami     | XXX | [![Build Status](https://github.com/giellalt/lang-smj/workflows/Build%20Speller%20Archives%20and%20Bundles/badge.svg)](https://github.com/giellalt/lang-smj/actions) |
| [giellalt/lang-smn](https://github.com/giellalt/lang-smn) | Inari Sami    | XXX | [![Build Status](https://github.com/giellalt/lang-smn/workflows/Build%20Speller%20Archives%20and%20Bundles/badge.svg)](https://github.com/giellalt/lang-smn/actions) |
| [giellalt/lang-sms](https://github.com/giellalt/lang-sms) | Skolt Sami    | XXX | [![Build Status](https://github.com/giellalt/lang-sms/workflows/Build%20Speller%20Archives%20and%20Bundles/badge.svg)](https://github.com/giellalt/lang-sms/actions) |
