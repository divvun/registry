# Divvun Repository Registry

An overview of the software repositories of [Divvun](https://github.com/divvun).
For private repos see [this page](https://github.com/divvun/private-registry) (restricted access).

The GiellaLT linguistic resources are not listed here — see the automatically generated overviews of
[keyboard layouts](https://giellalt.github.io/KeyboardLayouts.html),
[language models](https://giellalt.github.io/LanguageModels.html) and
[shared resources](https://giellalt.github.io/SharedResources.html) instead.

All repos are listed with core info like:

- short description, programming language and target platforms
- license
- open issues

CI/CD for all repositories runs on [Buildkite](https://buildkite.com/divvun) — see [CI_CD.md](CI_CD.md)
and the build overview at [builds.giellalt.org](https://builds.giellalt.org).

## Content

- [Product Software](#product-software)
- [Support Software](#support-software)
- [Build and Release Infrastructure](#build-and-release-infrastructure)

## Product Software

| Repository | Description | Programming Language(s) | Platform | License | Open&nbsp;Issues |
| ---------- | ----------- | ----------------------- | -------- | ------- | ---------------- |
| [divvun-manager-macos](https://github.com/divvun/divvun-manager-macos) | Divvun Manager for macOS, the desktop client for the Páhkat package manager | Swift | macOS | GPL-3.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-manager-macos)](https://github.com/divvun/divvun-manager-macos/issues) |
| [divvun-manager-windows](https://github.com/divvun/divvun-manager-windows) | Divvun Manager for Windows | C# | Windows | GPL-3.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-manager-windows)](https://github.com/divvun/divvun-manager-windows/issues) |
| [divvun-keyboard](https://github.com/divvun/divvun-keyboard) | iOS and Android keyboard apps for production-grade GiellaLT mobile keyboard layouts (meta repo) | - | Android, iOS | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-keyboard)](https://github.com/divvun/divvun-keyboard/issues) |
| [divvun-dev-keyboard](https://github.com/divvun/divvun-dev-keyboard) | Keyboard app for experimental layouts, new technologies and general testing (meta repo) | - | Android, iOS | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-dev-keyboard)](https://github.com/divvun/divvun-dev-keyboard/issues) |
| [divvun-gramcheck-web](https://github.com/divvun/divvun-gramcheck-web) | Grammar checker plugin for MS&nbsp;Office & Google&nbsp;Docs | TypeScript | MS&nbsp;Office, Google&nbsp;Docs | GPL-3.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-gramcheck-web)](https://github.com/divvun/divvun-gramcheck-web/issues) |
| [divvun-gramcheck-webextension](https://github.com/divvun/divvun-gramcheck-webextension) | Divvun grammar checker browser extension | TypeScript | Web | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-gramcheck-webextension)](https://github.com/divvun/divvun-gramcheck-webextension/issues) |
| [divvun-webeditor](https://github.com/divvun/divvun-webeditor) | Online grammar and spell checking editor | TypeScript | Web | GPL-3.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-webeditor)](https://github.com/divvun/divvun-webeditor/issues) |
| [divvunspell-libreoffice](https://github.com/divvun/divvunspell-libreoffice) | LibreOffice spell checking extension based on divvunspell | C++ | LibreOffice | Apache-2.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvunspell-libreoffice)](https://github.com/divvun/divvunspell-libreoffice/issues) |
| [keyboard-viewer](https://github.com/divvun/keyboard-viewer) | Web app to view, edit and test GiellaLT keyboard layouts | TypeScript | Web | Apache-2.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/keyboard-viewer)](https://github.com/divvun/keyboard-viewer/issues) |
| [satni-backend](https://github.com/divvun/satni-backend) | GraphQL backend serving [sátni.org](https://satni.org) | Python | Web | GPL-3.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/satni-backend)](https://github.com/divvun/satni-backend/issues) |
| [satni-frontend](https://github.com/divvun/satni-frontend) | React frontend for [sátni.org](https://satni.org) | TypeScript | Web | GPL-3.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/satni-frontend)](https://github.com/divvun/satni-frontend/issues) |
| [gielese](https://github.com/divvun/gielese) | Language learning web and mobile app for South Sámi | TypeScript | Web | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/gielese)](https://github.com/divvun/gielese/issues) |
| [jietnasiella.org](https://github.com/divvun/jietnasiella.org) | Support website for the Jietnašiella "donate your speech" app | HTML, CSS | Web | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/jietnasiella.org)](https://github.com/divvun/jietnasiella.org/issues) |

## Support Software

| Repository | Description | Programming Language(s) | Platform | License | Open&nbsp;Issues |
| ---------- | ----------- | ----------------------- | -------- | ------- | ---------------- |
| [bidiff](https://github.com/divvun/bidiff) | A Rust take on bsdiff, for binary diffing and patching | Rust | Any | Apache-2.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/bidiff)](https://github.com/divvun/bidiff/issues) |
| [CorpusTools](https://github.com/divvun/CorpusTools) | Tools to manage and convert GiellaLT corpus files | Python | Any | GPL-3.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/CorpusTools)](https://github.com/divvun/CorpusTools/issues) |
| [divvun-runtime](https://github.com/divvun/divvun-runtime) | Modular language processing pipeline system for grammar checkers and text-to-speech | Rust | Any | Apache-2.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-runtime)](https://github.com/divvun/divvun-runtime/issues) |
| [divvun-worker-grammar](https://github.com/divvun/divvun-worker-grammar) | Grammar checker web service | TypeScript | Web | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-worker-grammar)](https://github.com/divvun/divvun-worker-grammar/issues) |
| [divvun-worker-speller](https://github.com/divvun/divvun-worker-speller) | Spell checker web service | Rust | Web | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-worker-speller)](https://github.com/divvun/divvun-worker-speller/issues) |
| [divvun-worker-tts](https://github.com/divvun/divvun-worker-tts) | Text-to-speech web service | TypeScript | Web | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-worker-tts)](https://github.com/divvun/divvun-worker-tts/issues) |
| [divvunspell](https://github.com/divvun/divvunspell) | Spell checking engine and library for ZHFST/BHFST spellers | Rust | Any | Apache-2.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvunspell)](https://github.com/divvun/divvunspell/issues) |
| [giellakbd-android](https://github.com/divvun/giellakbd-android) | Open source keyboard implementation for Android (used by kbdgen-built apps) | Java, Kotlin | Android | Apache-2.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/giellakbd-android)](https://github.com/divvun/giellakbd-android/issues) |
| [giellakbd-ios](https://github.com/divvun/giellakbd-ios) | Open source keyboard implementation for iOS (used by kbdgen-built apps) | Swift | iOS | Apache-2.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/giellakbd-ios)](https://github.com/divvun/giellakbd-ios/issues) |
| [GiellaLTGramTools](https://github.com/divvun/GiellaLTGramTools) | Tools for testing GiellaLT grammar checkers | Python, Rust | Any | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/GiellaLTGramTools)](https://github.com/divvun/GiellaLTGramTools/issues) |
| [GiellaLTLexTools](https://github.com/divvun/GiellaLTLexTools) | Tools for testing and processing GiellaLT lexical resources | Python | Any | GPL-3.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/GiellaLTLexTools)](https://github.com/divvun/GiellaLTLexTools/issues) |
| [gut](https://github.com/divvun/gut) | A Git(Hub) multirepo maintenance tool | Rust | Any | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/gut)](https://github.com/divvun/gut/issues) |
| [iso639-databases](https://github.com/divvun/iso639-databases) | Machine-readable ISO 639 tables for autonyms, LCIDs and default ISO 15924 scripts | - | Any | CC0-1.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/iso639-databases)](https://github.com/divvun/iso639-databases/issues) |
| [kbdgen](https://github.com/divvun/kbdgen) | Keyboard layout generator, outputting Android, iOS, Windows, macOS and Linux keyboard layouts | Rust | Any | Apache-2.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/kbdgen)](https://github.com/divvun/kbdgen/issues) |
| [kbdi](https://github.com/divvun/kbdi) | Windows keyboard installation and registry configuration utility | Rust | Windows | Apache-2.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/kbdi)](https://github.com/divvun/kbdi/issues) |
| [macdivvun-service](https://github.com/divvun/macdivvun-service) | Spell checking service for macOS | Swift | macOS | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/macdivvun-service)](https://github.com/divvun/macdivvun-service/issues) |
| [morph-test](https://github.com/divvun/morph-test) | Test runner for generation and analysis of morphological transducers | Python | Any | CC0-1.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/morph-test)](https://github.com/divvun/morph-test/issues) |
| [morph-test-rs](https://github.com/divvun/morph-test-rs) | Rust version of morph-test | Rust | Any | CC0-1.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/morph-test-rs)](https://github.com/divvun/morph-test-rs/issues) |
| [nfd-fixer](https://github.com/divvun/nfd-fixer) | Recodes NFD-encoded filenames in git repos to NFC | Rust | Any | MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/nfd-fixer)](https://github.com/divvun/nfd-fixer/issues) |
| [outto](https://github.com/divvun/outto) | Installation backend for Windows | Rust | Windows | MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/outto)](https://github.com/divvun/outto/issues) |
| [pahkat](https://github.com/divvun/pahkat) | Reference implementation of the Páhkat package management standard | Rust | Any | Apache-2.0 OR MIT / GPL-3.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/pahkat)](https://github.com/divvun/pahkat/issues) |
| [pahkat-reposrv](https://github.com/divvun/pahkat-reposrv) | Páhkat repository server | Rust | Any | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/pahkat-reposrv)](https://github.com/divvun/pahkat-reposrv/issues) |
| [see-modes](https://github.com/divvun/see-modes) | SubEthaEdit syntax modes for GiellaLT text file formats | - | macOS | MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/see-modes)](https://github.com/divvun/see-modes/issues) |
| [TermWikiTools](https://github.com/divvun/TermWikiTools) | Tools for working with the TermWiki terminology service | Python | Any | GPL-3.0+ | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/TermWikiTools)](https://github.com/divvun/TermWikiTools/issues) |
| [windivvun-service](https://github.com/divvun/windivvun-service) | Spell checking service for Windows | Rust | Windows | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/windivvun-service)](https://github.com/divvun/windivvun-service/issues) |

## Build and Release Infrastructure

| Repository | Description | Programming Language(s) | License | Open&nbsp;Issues |
| ---------- | ----------- | ----------------------- | ------- | ---------------- |
| [divvun-actions](https://github.com/divvun/divvun-actions) | Builders, pipelines and tasks for all Divvun and GiellaLT CI/CD | TypeScript (Deno) | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/divvun-actions)](https://github.com/divvun/divvun-actions/issues) |
| [buildkite-overview](https://github.com/divvun/buildkite-overview) | UI for [builds.giellalt.org](https://builds.giellalt.org), the build status overview | TypeScript | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/buildkite-overview)](https://github.com/divvun/buildkite-overview/issues) |
| [zulip-buildkite-bot](https://github.com/divvun/zulip-buildkite-bot) | Buildkite bot for Zulip | Rust | Apache-2.0 OR MIT | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/zulip-buildkite-bot)](https://github.com/divvun/zulip-buildkite-bot/issues) |
| [rsigncode](https://github.com/divvun/rsigncode) | Code signing tool for Windows binaries | Rust | Apache-2.0 | [![GitHub issues](https://img.shields.io/github/issues-raw/divvun/rsigncode)](https://github.com/divvun/rsigncode/issues) |
