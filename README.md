# Hi, I'm Jackson

I'm a software engineer in Philadelphia who spent ten years keeping production infrastructure running before moving into software. I bring an operator's instinct to code: I care about correctness, testability, and systems that don't page someone at 3am. These days I'm focused on building reliable software—establishing test suites, modernizing legacy codebases, and applying the same rigor I brought to infrastructure to the software that runs on top of it. When I'm not writing code or automation, you'll find me on hiking trails, carving ski slopes, or finding balance on the yoga mat. I'm equally at home debugging a flaky test suite, watching Formula 1, or getting lost in a good novel with a well-earned beer.

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

- Python, PowerShell, Ruby, Bash
- Test suite development & code modernization (Pester)
- CI quality gates with GitHub Actions
- REST API integration: Microsoft Graph, GitHub Enterprise, Entra ID

### Cloud & Infrastructure

- Azure, AWS, VMware vSphere
- Infrastructure-as-Code (Terraform, Ansible)
- High-availability architecture & disaster recovery

### Observability & Automation

- New Relic, Zabbix, Prometheus
- OpenTelemetry instrumentation
- AI-assisted development with explicit review checkpoints
- Local LLM deployment (Ollama, Mixtral)

### Platform Engineering

- Linux/Windows server architecture
- SQL Server clustering & availability groups
- Zero Trust deployment & PKI management

## Current Focus

- Bringing test coverage and CI quality gates to existing codebases
- Reliable, unattended API integrations: Microsoft Graph, GitHub, identity platforms
- GitHub Enterprise governance and developer experience that doesn't slow teams down
- AI-assisted development with explicit research, planning, and review checkpoints

## Recent Wins

- Built an internal PowerShell standard library for a four-engineer team, now used in 24 production scripts (47 call sites) in its first repository, with shared test infrastructure and CI
- Stood up the first Pester test suite and CI quality gates for an existing codebase; the tests caught a latent production bug during refactoring
- Moved shared mail delivery to the Microsoft Graph API, retiring legacy SMTP dependencies
- Part of the operations team that took a 1,200-server hybrid platform from 40–60% to 99.99% availability; I owned monitoring, automation, and three VMware datacenters
- Eliminated $400K+ in annual outsourcing costs and cut monthly vulnerability exposure 70% with an automated patching pipeline

Context for each number: [jacksonasmith.com/experience](https://jacksonasmith.com/experience/)

## Featured Projects

### [Keel](https://github.com/jackson-asmith/keel)

Tested PowerShell modules for unattended automation: bounded HTTP retries and Graph-first mail that won't resend after an ambiguous failure. [Read the case study →](https://jacksonasmith.com/projects/keel/)

### [PublicPowerShell](https://github.com/jackson-asmith/PublicPowerShell)

A collection of PowerShell scripts and automation tools I've built for system administration tasks. Feel free to use, modify, or contribute!

### [apacheloganalyzer](https://github.com/jackson-asmith/apacheloganalyzer)

A Ruby-based Apache log analyzer for quick insights into web server traffic and patterns.

### [LinuxConfig](https://github.com/jackson-asmith/LinuxConfig)

Automated Linux server configuration script for standardizing new system setups—because manual configuration is so 2010.

### [Email Alignment Checker](https://github.com/jackson-asmith/jackson-asmith/blob/main/.github/workflows/update-mail-alignment.yml)

Scheduled GitHub Actions workflow that monitors this domain's SPF, DKIM, and DMARC records and commits only when something actually changes. [Read the case study →](https://jacksonasmith.com/projects/email-alignment-checker/)

**Relatively live status of [jacksonasmith.com](https://jacksonasmith.com) DMARC alignment:**
<!-- DNS_STATUS_START -->
| Record | Status | Value |
|--------|--------|-------|
| MX | ✅ | `aspmx.l.google.com.` |
| SPF | ✅ | `~all` |
| DMARC | ✅ | `p=reject` |
| DKIM | ✅ | `google` |

*Last changed: 2026-06-12 15:13 UTC • Score: 3/3 (DKIM informational).*
<!-- DNS_STATUS_END -->

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
