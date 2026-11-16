# Hi, I'm Jackson

I'm a software engineer in Philadelphia who spent ten years keeping production infrastructure running before moving into software. I bring an operator's instinct to code: I care about correctness, testability, and systems that don't page someone at 3am. These days I'm focused on building reliable software—establishing test suites, modernizing legacy codebases, and applying the same rigor I brought to infrastructure to the software that runs on top of it. That includes code written with AI help: it gets the same tests, review, and recorded design decisions as anything else.

## How I Approach Engineering

- **Reliability is a feature:** systems shouldn't need heroics to operate
- **Automation must reduce risk, not create it**
- **Modernize incrementally:** improve what exists before reaching for a rewrite
- **Governance should enable engineers:** make the compliant path the easiest path
- **Testing comes before trust:** confidence comes from evidence, not familiarity
- **Documentation is engineering work**

More on each, with examples: [jacksonasmith.com/principles](https://jacksonasmith.com/principles/)

## What I Work With

### Software Engineering

- PowerShell, Python, Bash, Ruby; contributed upstream in C#, Go, Java, TypeScript, PHP, and Dart (Microsoft Kiota)
- Testing & CI: Pester, bats, ShellCheck, Go testing; GitHub Actions quality gates and egress firewall
- HTTP & API engineering: retry and backoff policy, idempotency and duplicate-send safety, redirect handling; REST and GraphQL (Microsoft Graph, GitHub, Entra ID)
- Library engineering: versioned modules, public/private API separation, architecture decision records
- AI-assisted development that stays test-gated and reviewed (Claude Code, GitHub Copilot custom instructions)
- Local models through Ollama (Qwen, DeepSeek)

### GitHub Platform & Governance

- GitHub Enterprise rulesets, required checks, and secret scanning
- `gh` CLI extensions, including [gh-baseline](https://github.com/jackson-asmith/gh-baseline)
- Copilot administration and cost controls through the billing API

### Cloud & Infrastructure

- Azure, AWS, VMware vSphere
- Infrastructure-as-Code (Terraform, Ansible)
- High-availability architecture & disaster recovery

### Observability & Automation

- New Relic, Zabbix, Prometheus
- OpenTelemetry instrumentation

### Platform Engineering

- Linux/Windows server architecture
- SQL Server clustering & availability groups
- Zero Trust deployment & PKI management

## Current Focus

- Bringing test coverage and CI quality gates to existing codebases
- Reliable, unattended API integrations: Microsoft Graph, GitHub, identity platforms
- GitHub governance and security baselines that don't slow teams down
- AI-assisted development with explicit research, planning, and review checkpoints

## Recent Wins

- Designed an opt-in retry-safety option for Microsoft Kiota, the HTTP runtime under the Microsoft Graph SDKs, so a POST that may already have been processed isn't resent; at the maintainer's request, ported it to all 8 language SDKs, with [every PR merged upstream](https://jacksonasmith.com/writing/2026/one-retry-fix-eight-sdks/)
- Built an internal PowerShell standard library for a four-engineer team, now used in 24 production scripts (47 call sites) in its first repository, with shared test infrastructure and CI
- Stood up the first Pester test suite and CI quality gates for an existing codebase; the tests caught a latent production bug during refactoring
- Built GitHub Enterprise billing reporting end to end, from an API ETL pipeline to Power BI dashboards and automated Copilot budget controls, then re-platformed the pipeline to Python so the data team could maintain it
- Eliminated $400K+ in annual outsourcing costs and cut monthly vulnerability exposure 70% with an automated patching pipeline
- Part of the operations team that took a 1,200-server hybrid platform from 40–60% to 99.99% availability; I owned monitoring, automation, and three VMware datacenters
- As LOPSA's vice president, led the board's search for a successor organization and moved every member to two years of ACM membership when the association dissolved in 2025

Context for each number: [jacksonasmith.com/experience](https://jacksonasmith.com/experience/)

## Featured Projects

### [gh-baseline](https://github.com/jackson-asmith/gh-baseline)

A read-only `gh` extension that reports where your GitHub repositories drift from a tiered security baseline you declare once, in a file: branch rulesets, where required checks may come from, secret scanning, action pinning, and workflows that still reference secrets long after a repo went quiet. Anything the API won't show is reported as `unknown`, never `pass`. Written in Go with only the standard library. [Read the case study →](https://jacksonasmith.com/projects/gh-baseline/)

```sh
gh extension install jackson-asmith/gh-baseline
```

### [Keel](https://github.com/jackson-asmith/keel)

PowerShell modules for unattended automation, CI-tested on Windows PowerShell 5.1 and PowerShell 7: bounded HTTP retries and Graph-first mail that won't resend after an ambiguous failure. [Read the case study →](https://jacksonasmith.com/projects/keel/)

### [LinuxConfig](https://github.com/jackson-asmith/LinuxConfig)

Modular Bash pipeline that bootstraps RHEL hosts into Active Directory and Red Hat Satellite: SSH, firewall, and audit hardening, Kerberos/SSSD domain join, and a self-healing domain rejoin. Every stage supports dry-run mode and is covered by bats tests and ShellCheck in CI.

### [Email Alignment Checker](https://github.com/jackson-asmith/email-alignment-checker)

Scheduled GitHub Actions workflow that monitors this domain's SPF, DKIM, and DMARC records and commits only when something actually changes. [Read the case study →](https://jacksonasmith.com/projects/email-alignment-checker/)

[![Mail alignment](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/jackson-asmith/email-alignment-checker/main/status.json)](https://github.com/jackson-asmith/email-alignment-checker)

## Beyond the Terminal

When I'm not in the command line, I'm:

- Suffering Scuderia Ferrari fan (yes, *that* kind of reliability engineering)
- Chasing powder on the slopes
- Finding zen through yoga
- Reading everything from sci-fi to philosophy
- Exploring trails around Philly and beyond

## Get In Touch

- Website: [jacksonasmith.com](https://jacksonasmith.com), including [projects & case studies](https://jacksonasmith.com/projects/) and my full [experience](https://jacksonasmith.com/experience/)
- Email: [jackson@jacksonasmith.com](mailto:jackson@jacksonasmith.com)
- LinkedIn: [jackson-a-smith](https://www.linkedin.com/in/jackson-a-smith/)
- Location: Philadelphia, PA
- Let's talk about: distributed systems, Ferrari's pitwall calls, ski recommendations, book swaps, or hiking trails
