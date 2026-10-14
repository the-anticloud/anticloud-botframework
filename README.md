# BOTFRAMEWORK

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-chat_platforms-lightgrey)

> Anticloud-hardened packaging of the upstream project `BOTFRAMEWORK` in category **CHAT PLATFORMS**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** CHAT PLATFORMS · **Upstream:** https://github.com/microsoft/botframework-sdk · **Upstream pin:** `ed8adc25069b8f94c18ff34cf834741f993dc360` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# ARCHIVE NOTICE:

The Bot Framework SDK is being retired with final long term support ending December 2025. This means that this project will no longer be updated or maintained. Customers using this tool will not be disrupted and bots built with the SDK will continue to function. However, the tool will no longer be supported through service tickets in the Azure portal and will *not* receive any product or feature updates. It will not have any regular non-critical dependency updates.

To build agents with your choice of AI services, orchestration, and knowledge, consider using the [Microsoft 365 Agents SDK](aka.ms/agents). The Agents SDK is GA and has support for C#, JavaScript or Python. You can learn more about the Agents SDK at aka.ms/agents. If you're looking for a SaaS-based agent platform, consider Microsoft Copilot Studio. If you have an existing bot built with the Bot Framework SDK, you can update your bot to the Agents SDK. You can review the core changes and updates at Bot Framework SDK to Agents SDK migration guidance [here](https://learn.microsoft.com/en-us/microsoft-365/agents-sdk/bf-migration-guidance). Support tickets for the Bot Framework SDK will no longer be serviced as of December 31, 2025.

We plan to archive this project no later than end of December of 2025.

# ![Bot Framework](./docs/media/BotFrameworkSDK.png)

### [What's new with Bot Framework?](https://docs.microsoft.com/en-us/azure/bot-service/what-is-new?view=azure-bot-service-4.0)

Bot Framework provides the most comprehensive experience for building conversation applications.

With the [Bot Framework SDK](#bot-framework-sdk-v4), developers can build bots that converse free-form or with guided interactions including using simple text or rich cards that contain text, images, and action buttons.

Developers can model and build sophisticated conversation using their favorite programming languages including C#, JS, and Python for developers and multi-disciplinary teams to design and build conversational experiences.

Checkout the [Bot Framework ecosystem](#bot-framework-ecosystem) section to learn more about other tooling and services related to the Bot Framework SDK.

## Quicklinks
| [C# project](https://github.com/Microsoft/botbuilder-dotnet)  | [JS project](https://github.com/Microsoft/botbuilder-js)  | [Python project](https://github.com/Microsoft/botbuilder-python) | [BF CLI](https://github.com/Microsoft/botframework-cli) |

## Bot Framework SDK v4
The Bot Framework SDK v4 is an [open source SDK][1a] that enable developers to model and build sophisticated conversation using their favorite programming language.

|   | C#  | JS  | Python |
|---|:---:|:---:|:------:|
|Stable Release |[packages][1] | [packages][2] | [packages][3] |
|Docs | [docs][5] |[docs][5] |[docs][5]  |
|Samples |[.NET Core][6], [WebAPI][10] |[Node.js][7] , [TypeScript][8], [es6][9]  | [Python][111] |

[1a]:https://github.com/microsoft/botframework-sdk/#readme
[1]:https://github.com/Microsoft/botbuilder-dotnet/#packages
[2]:https://github.com/Microsoft/botbuilder-js#packages
[3]:https://github.com/microsoft/botbuilder-python/#packages
[5]:https://docs.microsoft.com/en-us/azure/bot-service/?view=azure-bot-service-4.0
[6]:https://github.com/Microsoft/BotBuilder-Samples/tree/main/samples/csharp_dotnetcore
[7]:https://github.com/Microsoft/BotBuilder-Samples/tree/main/samples/javascript_nodejs
[8]:https://github.com/Microsoft/BotBuilder-Samples/tree/main/samples/typescript_nodejs
[9]:https://github.com/Microsoft/BotBuilder-Samples/tree/main/samples/javascript_es6
[10]:https://github.com/Microsoft/BotBuilder-Samples/tree/main/samples/csharp_webapi
[111]:https://github.com/microsoft/BotBuilder-Samples/tree/main/samples/python

## Channels and Adapters
There are two ways to connect your bot to a client experience:
* **Azure Bot Service Channel** - Language and SDK independent support via Azure Bot Service
* **Bot Framework SDK Adapter** -  A per language Adapter component

| Client          | Azure Channel  | C# Adapter           | JS Adapter        |
|-----------------|:--------------:|:--------------------:|:-----------------:|
| Microsoft Teams | [Azure][55abs] |                      |                   |
| Direct Line     | [Azure][55abs] |                      |                   |
| Web Chat        | [Azure][55abs] |                      | [Botkit][55bk]    |
| Skype           | [Azure][55abs] |                      |                   |
| Email           | [Azure][55abs] |                      |                   |
| Facebook        | [Azure][55abs] |  [Community][55sdkcsfb]    | [Botkit][55bk]    |
| Slack           | [Azure][55abs] |  [Community][55sdkcsslack] | [Botkit][55bk]    |
| Kik             | [Azure][55abs] |                      |                   |
| Telegram        | [Azure][55abs] |                      |                   |
| Line            | [Azure][55abs] |                      |                   |
| GroupMe         | [Azure][55abs] |                      |                   |
| Twilio (SMS)    | [Azure][55abs] | [Community][55sdkcstwilio] | [Botkit][55bk]    |
| Alexa Skills    |                | [Community][55cs]    | [Community][55js] |
| Google Actions  |                | [Community][55cs]    | [Community][55js] |
| Google Hangouts |                |                      | [Botkit][55bk]    |
| WebEx           |                | [Community][55sdkcswebex]    | [Botkit][55bk]    |
| WhatsApp (Infobip)  |            | [Community][55cs]    |                   |
| Zoom            |                | [Community][55cs]    |                   |
| RingCentral     |                | [Community][55cs]    |                   |
| Cortana         | [Azure][55abs] |                      |                   |
| Console         |                |                      | [Community][55js] |

[55abs]:https://docs.microsoft.com/en-us/azure/bot-service/bot-service-manage-channels?view=azure-bot-service-4.0
[55cs]:https://github.com/BotBuilderCommuni

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `Common/`, `Orchestrator/`, `dri/`, `parsers/`, `schemas/`, `specs/`, `tools/`
- Snapshot size: **855 files**, **35958 lines of code** (measured; see Benchmarks)
- Primary languages: `.lu` (257), `.json` (168), `.js` (110), `.md` (104), `.svg` (45), `.qna` (25)
- Upstream commit pinned for this packaging: `ed8adc25069b8f94c18ff34cf834741f993dc360`

---

## Installation

We plan to archive this project no later than end of December of 2025.

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

<a name="ABS-whats-new"></a>

* **Direct Line Speech Channel**: We are bringing together the Bot Framework and Microsoft's Speech Services to provide a channel that enables streamed speech and text bi-directionally from the client to the bot application.  To sign up, add the 'Direct Line Speech' channel to your Azure Bot Service.

[27]:https://azure.microsoft.com/en-us/services/bot-service/
[28]:https://docs.microsoft.com/en-us/azure/bot-service/bot-service-overview-introduction?view=azure-bot-service-4.0
[29]:https://docs.microsoft.com/en-us/azure/bot-service/bot-service-manage-channels?view=azure-bot-service-4.0
[30]:https://github.com/Microsoft/BotFramework-DirectLineJS/blob/main/README.md

* **Better isolation for your Bot - Direct Line App Service Extension** : The Direct Line App Service Extension can be deployed as part of a VNET, allowing IT administrators to have more control over conversation traffic and improved latency in conversations due to reduction in the number of hops. Get started with Direct Line App Service Extension here. A VNET lets you create your own private space in Azure and is crucial to your cloud network as it offers isolation, segmentation, and other key benefits.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

The upstream API surface is defined by the `BOTFRAMEWORK` source tree vendored in `UPSTREAM_CLONE/` (Unknown (no standard manifest detected) ecosystem). Public entry points:

- Source modules: `Common/`, `Orchestrator/`, `dri/`, `parsers/`, `schemas/`, `specs/`, `tools/`
- The snapshot declares 30 dependency references across 1 ecosystem(s); see Dependencies below.
- Overlay API: `anticloud/cli.py` exposes 13 subcommands with JSON stdout; `anticloud/bench/runner.py` runs the 16-check suite; `anticloud/provenance/chain.py` exposes the SHA3-256 + Ed25519 provenance chain.

---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 855 |
| Lines of code | 35958 |
| Dependency references | 30 |
| Dependencies by ecosystem | npm: 30 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | @azure/cognitiveservices-luis-authoring | 4.0.0-preview.1 | parsers/LU/JS/packages/lu/package.json |
| npm | @azure/ms-rest-azure-js | 2.0.1 | parsers/LU/JS/packages/lu/package.json |
| npm | @types/node-fetch | ~2.5.5 | parsers/LU/JS/packages/lu/package.json |
| npm | antlr4 | ^4.7.2 | parsers/LU/JS/packages/lu/package.json |
| npm | chalk | 2.4.1 | parsers/LU/JS/packages/lu/package.json |
| npm | console-stream | ^0.1.1 | parsers/LU/JS/packages/lu/package.json |
| npm | deep-equal | ^1.0.1 | parsers/LU/JS/packages/lu/package.json |
| npm | delay | ^4.3.0 | parsers/LU/JS/packages/lu/package.json |
| npm | fs-extra | ^8.1.0 | parsers/LU/JS/packages/lu/package.json |
| npm | get-stdin | ^6.0.0 | parsers/LU/JS/packages/lu/package.json |
| npm | globby | ^10.0.1 | parsers/LU/JS/packages/lu/package.json |
| npm | intercept-stdout | ^0.1.2 | parsers/LU/JS/packages/lu/package.json |
| npm | lodash | ^4.17.19 | parsers/LU/JS/packages/lu/package.json |
| npm | node-fetch | ~2.6.0 | parsers/LU/JS/packages/lu/package.json |
| npm | semver | ^5.5.1 | parsers/LU/JS/packages/lu/package.json |
| ... | (15 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- None detected at the snapshot root; consult the upstream documentation link in the Upstream section.

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Instructions for Contributing Code

## Contributing bug fixes and features

The Bot Framework team is currently accepting contributions in the form of bug fixes and new 
features. Any submission must have an issue tracking it in the issue tracker that has
 been approved by the Bot Framework team. Your pull request should include a link to 
 the bug that you are fixing. If you've submitted a PR for a bug, please post a 
 comment in the bug to avoid duplication of effort.

## Legal

If your contribution is more than 15 lines of code, you will need to complete a Contributor 
License Agreement (CLA). Briefly, this agreement testifies that you are granting us permission
 to use the submitted change according to the terms of the project's license, and that the work
  being submitted is under appropriate copyright.

Please submit a Contributor License Agreement (CLA) before submitting a pull request. 
You may visit https://cla.azure.com to sign digitally. Alternatively, download the 
agreement ([Microsoft Contribution License Agreement.docx](https://www.codeplex.com/Download?ProjectName=typescript&DownloadId=822190) or
 [Microsoft Contribution License Agreement.pdf](https://www.codeplex.com/Download?ProjectName=typescript&DownloadId=921298)), sign, scan, 
 and email it back to <cla@microsoft.com>. Be sure to include your github user name along with the agreement. Once we have received the 
 signed CLA, we'll review the request.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
The MIT License (MIT)

Copyright (c) 2016 Microsoft

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `BOTFRAMEWORK` (category: CHAT PLATFORMS)
- **Upstream URL:** https://github.com/microsoft/botframework-sdk
- **Pinned commit (SHA):** `ed8adc25069b8f94c18ff34cf834741f993dc360`
- **Branch:** main
- **Pin provenance:** GitHub API commits/main. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`5e920b904239a1194b108319819886c6834171ec039c4f88b52abfd2b92d364f`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

