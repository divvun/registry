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
| divvunspell-mso | Necessary proprietary fork for Microsoft Office support, ask Børre for access | Rust | Windows | Proprietary | [![Build Status](https://dev.azure.com/divvun/msoffice/_apis/build/status/divvun.ci-divvunspell-mso?branchName=master)](https://dev.azure.com/divvun/msoffice/_build/latest?definitionId=3&branchName=master) | 
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

| Repository | Spoken Language(s) | License | CI Report |
| ---------- | ------------------ | ------- | --------- |
| [giellalt/keyboard-crk](https://github.com/giellalt/keyboard-crk) | Plains Cree | XXX | [![Build Status](https://dev.azure.com/giellalt/crk/_apis/build/status/giellalt.keyboard-crk?branchName=master)](https://dev.azure.com/giellalt/crk/_build/latest?definitionId=1&branchName=master) |
| [giellalt/keyboard-sma](https://github.com/giellalt/keyboard-sma) | Southern Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/sma/_apis/build/status/giellalt.keyboard-sma?branchName=master)](https://dev.azure.com/giellalt/sma/_build/latest?definitionId=3&branchName=master) |
| [giellalt/keyboard-sme](https://github.com/giellalt/keyboard-sme) | Northern Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/sme/_apis/build/status/giellalt.keyboard-sme?branchName=master)](https://dev.azure.com/giellalt/sme/_build/latest?definitionId=6&branchName=master) |
| [giellalt/keyboard-smj](https://github.com/giellalt/keyboard-smj) | Lule Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/smj/_apis/build/status/giellalt.keyboard-smj?branchName=master)](https://dev.azure.com/giellalt/smj/_build/latest?definitionId=5&branchName=master) |
| [giellalt/keyboard-smn](https://github.com/giellalt/keyboard-smn) | Inari Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/smn/_apis/build/status/giellalt.keyboard-smn?branchName=master)](https://dev.azure.com/giellalt/smn/_build/latest?definitionId=2&branchName=master) |
| [giellalt/keyboard-sms](https://github.com/giellalt/keyboard-sms) | Skolt Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/sms/_apis/build/status/giellalt.keyboard-sms?branchName=master)](https://dev.azure.com/giellalt/sms/_build/latest?definitionId=4&branchName=master) |

### Languages

| Repository | Spoken Language(s) | License | CI Report |
| ---------- | ------------------ | ------- | --------- |
| [giellalt/lang-crk](https://github.com/giellalt/lang-crk) | Plains Cree | XXX | [![Build Status](https://dev.azure.com/giellalt/crk/_apis/build/status/giellalt.lang-crk?branchName=master)](https://dev.azure.com/giellalt/crk/_build/latest?definitionId=12&branchName=master) |
| [giellalt/lang-sma](https://github.com/giellalt/lang-sma) | Southern Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/sma/_apis/build/status/giellalt.lang-sma?branchName=master)](https://dev.azure.com/giellalt/sma/_build/latest?definitionId=8&branchName=master) |
| [giellalt/lang-sme](https://github.com/giellalt/lang-sme) | Northern Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/sme/_apis/build/status/giellalt.lang-sme?branchName=master)](https://dev.azure.com/giellalt/sme/_build/latest?definitionId=9&branchName=master) |
| [giellalt/lang-smj](https://github.com/giellalt/lang-smj) | Lule Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/smj/_apis/build/status/giellalt.lang-smj?branchName=master)](https://dev.azure.com/giellalt/smj/_build/latest?definitionId=10&branchName=master) |
| [giellalt/lang-smn](https://github.com/giellalt/lang-smn) | Inari Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/smn/_apis/build/status/giellalt.lang-smn?branchName=master)](https://dev.azure.com/giellalt/smn/_build/latest?definitionId=7&branchName=master) |
| [giellalt/lang-sms](https://github.com/giellalt/lang-sms) | Skolt Sami | XXX | [![Build Status](https://dev.azure.com/giellalt/sms/_apis/build/status/giellalt.lang-sms?branchName=master)](https://dev.azure.com/giellalt/sms/_build/latest?definitionId=11&branchName=master) |

## CI/CD

### Azure Project Setup
All languages have their own project on Azure for CI/CD. Before setting up pipelines for keyboards and languages you will need to create that project.

#### Initial project setup
1. Go to [https://dev.azure.com/giellalt](https://dev.azure.com/giellalt)
2. Click `Create project` and follow the instructions
  * Project name should be `<code>`
  * Write a description that contains the language name in readable format
  * Project should be public

#### Connection to divvun-ci-config
Since the keyboard and speller pipelines rely on the azure templates in the [divvun-ci-config](https://github.com/divvun/divvun-ci-config) repo you must create a service connection.

1. Select the `<code>` project
2. Go to `Project settings`
3. Go to `Service connections`
4. Select `New service connection`
5. Select `GitHub`
6. Make sure `Grant Access` is selected and name the connection `divvun-ci`
7. `Allow all pipelines to use this connection` and select `Ok`

### Setup Keyboard CI/CD
Keyboard CI/CD is running on [Azure](https://dev.azure.com/giellalt) using templates for easier setup of new languages. The [template](https://github.com/divvun/divvun-ci-config/blob/master/repo/templates/keyboards.yml) will deploy:
* Windows 8+ keyboard to Páhkat
* macOS keyboard to Páhkat
* iOS keyboard to App Store
* Android keyboard to Google Play

#### Speller archives
The iOS and Android keyboard pipelines rely on the nightly speller archives of [https://apertium.projectjj.com](https://apertium.projectjj.com).

#### Create repository
Create a `giellalt` git repository named `keyboard-<code>` where code is the ISO 639-2 code of the language.
* Add kbdgen configuration

#### Páhkat packages
The template requires windows and macOS to use separate Páhkat repositories, each with the following package set up on the `nightly` channel:

* `keyboard-<code>`

#### Azure pipelines configuration file
Create a file named `azure-pipelines.yml` in the `keyboard-<code>` repository. Replace the values of the commented lines with values that apply to the new keyboard.

```yaml
trigger:
- master

resources:
  repositories:
    - repository: templates
      type: GitHub
      name: divvun/divvun-ci-config
      endpoint: divvun-ci

jobs:
  - template: repo/templates/keyboards.yml@templates
    parameters:
      # the language code used when creating the lang-<code> repo
      name: crk
      # the name of the páhkat package
      packageName: keyboard-crk
      # the name of the folder in the keyboard-<code> repository that
      # contains the kbdgen configuration
      kbdgenFolder: "crk.kbdgen"
      # páhkat repository url for windows
      repositoryWin: "https://pahkat.uit.no/repo/windows"
      # páhkat repository url for macOS
      repositoryMac: "https://pahkat.uit.no/repo/macos"
      languages:
        # the folder part of the url to the zhfst bundle on projectjj
        # this example will expand to:
        # https://apertium.projectjj.com/apt/nightly/pool/main/g/giella-sma
        - projectjjName: giella-crk
          # the path of the zhfst in the bundle on projectjj
          path: usr/share/giella/mobilespellers/crk-mobile.zhfst
          # language code to use while bundling
          name: crk
```

#### Azure pipeline setup
First make sure you have a project by following the instructions in the Azure Setup section.
1. Select the `<code>` project
2. Go to `Pipelines`, select `New pipeline` and follow the instructions
  * Connect to the `keyboard-<code>` repository on github
  * Use the `azure-pipelines.yml` configuration file from that repository

#### Configure pipeline variables
1. Select the keyboard build pipeline `giellalt.keyboard-<code>`
2. Select `Edit`
3. From the menu select `Variables` and configure the following variables

| Name | Value |
| ---------- | ------------------ |
| android.version | The version of the keyboard as set in `targets/android.yml` |
| divvunKey | The key used to decrypt the [divvun-ci-config](https://github.com/divvun/divvun-ci-config) repo |
| ios.version | The version of the keyboard as set in `targets/ios.yml` |
| pfxPassword | The password for the windows code sign pfx in the [divvun-ci-config](https://github.com/divvun/divvun-ci-config) repo |
| svnUser | divvunci |
| svnPassword | The password for the divvunci svn user |
| svnCommit | Set to 1 to actually commit to svn, otherwise consider the pipeline to dry-run |

##### Update this README
* Add the new keyboard to the Keyboards table under Resources
* Repository link should redirect to the repository on github
* Add a CI report using the `Sample Markdown` found by clicking `Status badge` in the pipeline menu on Azure

### Setup Language CI/CD
Language CI/CD is running on [Azure](https://dev.azure.com/giellalt) using templates for easier setup of new languages. The [template](https://github.com/divvun/divvun-ci-config/blob/master/repo/templates/spellers.yml) will deploy:
* System speller for windows 8+ and macOS
* LibreOffice speller for windows and macOS
* MSOffice speller for windows

##### Speller archives
The language pipelines rely on the nightly speller archives of [https://apertium.projectjj.com](https://apertium.projectjj.com).

##### Create repository
Create a `giellalt` git repository named `lang-<code>` where code is the ISO 639-2 code of the language.
* Add a plain text file called `version.txt` containing the speller version
* Add a license file called `LICENSE`

##### Páhkat packages
The template requires windows and macOS to use separate Páhkat repositories, with the following packages set up on the `nightly` channel:

Windows

* `speller-<code>`
* `speller-<code>-lo`
* `speller-<code>-mso`

macOS

* `speller-<code>`
* `speller-<code>-lo`

The package definition files `index.nightly.json` contains the UUIDs needed for the azure pipelines configuration.

##### Azure pipelines configuration file
Create a file named `azure-pipelines.yml` in the `lang-<code>` repository. Replace the values of the commented lines with values that apply to the new language.

```yaml
trigger:
- master

resources:
  repositories:
    - repository: templates
      type: GitHub
      name: divvun/divvun-ci-config
      endpoint: divvun-ci

schedules:
- cron: "3 0 * * *"
  displayName: Nightly build 
  branches:
    include:
    - master
  always: true

jobs:
  - template: repo/templates/spellers.yml@templates
    parameters:
      # the language code used when creating the lang-<code> repo
      name: sma
      # páhkat repository url for windows
      repositoryWin: "https://pahkat.uit.no/repo/windows"
      # páhkat repository url for macOS
      repositoryMac: "https://pahkat.uit.no/repo/macos"
      # language name in readable format
      humanName: "Southern Sami Speller"
      # UUID used by páhkat for the windows windows system package
      uuidWin: '51852B34-FDAC-5748-B467-CF731D711EE0'
      # UUID used by páhkat for the windows libreoffice package
      uuidLO: '602CF630-93AE-47DB-AEB7-D18143F7D807'
      # UUID used by páhkat for the windows msoffice package
      uuidWinMso: '4F5DBECF-5760-487C-9CAB-62DAA3A86EAF'
      languages:
        # the folder part of the url to the zhfst bundle on projectjj
        # this example will expand to:
        # https://apertium.projectjj.com/apt/nightly/pool/main/g/giella-sma
        - projectjjName: giella-sma
          # the path of the zhfst in the bundle on projectjj
          path: usr/share/voikko/3/sma.zhfst
          # language code to use while bundling
          name: sma
```

##### Azure pipeline setup
1. Select the `<code>` project
2. Go to `Pipelines`, select `New pipeline` and follow the instructions
  * Connect to the `lang-<code>` repository on github
  * Use the `azure-pipelines.yml` configuration file from that repository

##### Configure pipeline variables
1. Select the language build pipeline `giellalt.lang-<code>`
2. Select `Edit`
3. From the menu select `Variables` and configure the following variables

| Name | Value |
| ---------- | ------------------ |
| divvunKey | The key used to decrypt the [divvun-ci-config](https://github.com/divvun/divvun-ci-config) repo |
| pfxPassword | The password for the windows code sign pfx in the [divvun-ci-config](https://github.com/divvun/divvun-ci-config) repo |
| svnUser | divvunci |
| svnPassword | The password for the divvunci svn user |
| svnCommit | Set to 1 to actually commit to svn, otherwise consider the pipeline to dry-run |

##### Update this README
* Add the new language to the Languages table under Resources
* Repository link should redirect to the repository on github
* Add a CI report using the `Sample Markdown` found by clicking `Status badge` in the pipeline menu on Azure
