# urbit-skills

Comprehensive collection of 87 AI agent skills for Urbit development, operations, and tooling. These skills give AI agents practical knowledge of ship runtime, terminal commands, Hoon programming, Nock assembly language, and deployment workflows.

**Total Skills**: 87
- 53 Knowledge Skills - Reference material for concepts and APIs
- 6 Assistant Skills - Active guidance for development and debugging
- 26 Workflow Skills - Step-by-step processes for complex tasks
- 2 Interaction Skills - Ship terminal and socket communication

## Categories

### 📚 Knowledge Skills (53)

Reference material and comprehensive documentation for Urbit concepts, languages, and operations.

#### Hoon Development (18 skills)

**Foundation**:
- [hoon-basics](./skills/hoon-basics/) - Quick reference for syntax fundamentals
- [hoon-fundamentals](./skills/hoon-fundamentals/) - Subject-oriented programming and noun model
- [rune-reference](./skills/rune-reference/) - Complete reference for 90+ runes

**Language**:
- [type-system](./skills/type-system/) - Structural typing, auras, molds, type casting
- [functional-programming-patterns](./skills/functional-programming-patterns/) - Pure functions, higher-order functions, recursion
- [advanced-patterns](./skills/advanced-patterns/) - Doors, wet gates, mold builders, metaprogramming
- [irregular-forms](./skills/irregular-forms/) - Syntactic shortcuts and best practices
- [hoon-style-guide](./skills/hoon-style-guide/) - Naming conventions and code organization

**Data**:
- [data-structures](./skills/data-structures/) - Lists, sets, maps, mops, jars, jugs
- [string-handling](./skills/string-handling/) - Cord, tape, term, knot types
- [serialization](./skills/serialization/) - JSON, vases, jam/cue, marks

**Libraries**:
- [stdlib-reference](./skills/stdlib-reference/) - Comprehensive standard library documentation
- [zuse-libraries](./skills/zuse-libraries/) - HTTP, JSON, crypto, scry utilities

**Applications**:
- [gall-agents](./skills/gall-agents/) - Complete Gall agent development lifecycle
- [generators](./skills/generators/) - Naked, %say, %ask generators for CLI tools
- [parsing](./skills/parsing/) - Parser combinators and custom parsers
- [app-development-workflow](./skills/app-development-workflow/) - End-to-end development process
- [sail-markup](./skills/sail-markup/) - HTML templating in Hoon

#### Nock Development (12 skills)

**Foundation**:
- [nock-essentials](./skills/nock-essentials/) - Nouns (atoms/cells), reduction model, evaluation semantics
- [nock-operators](./skills/nock-operators/) - Complete reference for 6 operators (?, +, =, /, #, *)
- [nock-instructions](./skills/nock-instructions/) - All 13 reduction rules (0-12) with examples

**Implementation**:
- [nock-interpreter-patterns](./skills/nock-interpreter-patterns/) - Design patterns for building Nock VMs
- [nock-multi-language-implementations](./skills/nock-multi-language-implementations/) - C, Python, Rust, Haskell, JavaScript patterns

**Optimization**:
- [nock-jetting-optimization](./skills/nock-jetting-optimization/) - Jet acceleration: hint processing, cold/hot/warm states
- [nock-performance-profiling](./skills/nock-performance-profiling/) - CPU/memory profiling, benchmarking

**Advanced**:
- [nock-tree-addressing](./skills/nock-tree-addressing/) - Binary tree addressing: axis encoding, slot calculation
- [nock-cores-arms-batteries](./skills/nock-cores-arms-batteries/) - Core structure pattern: batteries, payloads, arms
- [nock-metacircular-evaluation](./skills/nock-metacircular-evaluation/) - Self-interpretation: +mock (Nock-in-Nock)

**Integration**:
- [nock-hoon-compilation](./skills/nock-hoon-compilation/) - How Hoon compiles to Nock
- [nock-specification-reference](./skills/nock-specification-reference/) - Complete formal Nock 4K specification

#### Urbit Operations (23 skills)

**Core Fundamentals**:
- [urbit-fundamentals](./skills/urbit-fundamentals/) - Nock, Hoon, Arvo, vanes, Azimuth, Ames
- [ship-deployment-guide](./skills/ship-deployment-guide/) - Step-by-step deployment procedures
- [urbit-troubleshooting](./skills/urbit-troubleshooting/) - Systematic diagnostics

**Deployment & Infrastructure**:
- [vps-deployment-providers](./skills/vps-deployment-providers/) - DigitalOcean, Linode, Vultr, AWS, Hetzner, OVH
- [groundseg-installation](./skills/groundseg-installation/) - Docker setup, Anchor networking, MinIO S3
- [groundseg-troubleshooting](./skills/groundseg-troubleshooting/) - Container issues, DNS, SSL certificates
- [kubernetes-urbit](./skills/kubernetes-urbit/) - StatefulSets, persistent volumes, GitOps
- [multi-ship-orchestration](./skills/multi-ship-orchestration/) - Resource allocation, network isolation

**Networking & Security**:
- [anchor-networking](./skills/anchor-networking/) - Reverse proxy, Let's Encrypt SSL, custom domains
- [network-security-advanced](./skills/network-security-advanced/) - Zero-trust networking, VPNs, network policies
- [container-security](./skills/container-security/) - User namespaces, capabilities, AppArmor, Seccomp
- [advanced-security-patterns](./skills/advanced-security-patterns/) - Defense-in-depth, intrusion detection

**Storage & Backup**:
- [minio-s3-integration](./skills/minio-s3-integration/) - Self-hosted S3 for ship storage
- [backup-disaster-recovery](./skills/backup-disaster-recovery/) - Automated backups, restoration procedures
- [disaster-recovery-advanced](./skills/disaster-recovery-advanced/) - Multi-region failover, cross-region replication

**Monitoring & Operations**:
- [monitoring-observability](./skills/monitoring-observability/) - Prometheus, Grafana, Loki, AlertManager
- [performance-optimization](./skills/performance-optimization/) - Disk I/O tuning, memory optimization, network throughput
- [performance-profiling](./skills/performance-profiling/) - Bottleneck identification, capacity planning
- [sla-management](./skills/sla-management/) - Uptime targets, incident response, error budgets

**Management**:
- [fleet-operations](./skills/fleet-operations/) - Terraform IaC, Helm templating, staged OTA updates
- [managed-hosting-comparison](./skills/managed-hosting-comparison/) - Tlon vs Red Horizon vs UrbitHost
- [app-development-workflow](./skills/app-development-workflow/) - Local development, desk publishing

**Compliance**:
- [compliance-frameworks](./skills/compliance-frameworks/) - GDPR, HIPAA, SOC2, ISO 27001

### 🤖 Assistant Skills (6)

Active guidance skills for development, debugging, and operations.

#### Hoon Development
- [hoon-expert-assistant](./skills/hoon-expert-assistant/) - Expert Hoon coding help, type errors, performance optimization
- [debugging-specialist-assistant](./skills/debugging-specialist-assistant/) - Systematic debugging from compilation errors to runtime failures

#### Nock Development
- [nock-interpreter-engineer-assistant](./skills/nock-interpreter-engineer-assistant/) - Build Nock interpreters in multiple languages
- [nock-optimization-specialist-assistant](./skills/nock-optimization-specialist-assistant/) - Optimize Nock performance (10x-1000x speedups)
- [nock-fundamentals-tutor-assistant](./skills/nock-fundamentals-tutor-assistant/) - Educational Nock learning from nouns through cores

#### Urbit Operations
- [performance-engineer-assistant](./skills/performance-engineer-assistant/) - Performance troubleshooting, tuning, capacity planning

### 🔄 Workflow Skills (26)

Structured step-by-step processes for complex tasks.

#### Hoon Development Workflows (8)
- [hoon-review-workflow](./skills/hoon-review-workflow/) - 5-phase code review (quality, security, performance, maintainability)
- [hoon-optimize-workflow](./skills/hoon-optimize-workflow/) - 4-phase performance optimization with benchmarking
- [hoon-debug-workflow](./skills/hoon-debug-workflow/) - 5-phase systematic debugging workflow
- [hoon-refactor-workflow](./skills/hoon-refactor-workflow/) - 6-phase safe refactoring while preserving correctness
- [hoon-test-workflow](./skills/hoon-test-workflow/) - 5-phase testing (unit, integration, property-based, TDD)
- [hoon-migrate-workflow](./skills/hoon-migrate-workflow/) - 5-phase safe state migration for Gall agents
- [hoon-scaffold-workflow](./skills/hoon-scaffold-workflow/) - 6-phase project bootstrapping with best practices
- [orchestrate-feature-workflow](./skills/orchestrate-feature-workflow/) - End-to-end feature development orchestration

#### Nock Development Workflows (7)
- [build-nock-interpreter-workflow](./skills/build-nock-interpreter-workflow/) - 8-phase workflow for building production-ready interpreters
- [optimize-nock-performance-workflow](./skills/optimize-nock-performance-workflow/) - 6-phase systematic optimization from profiling through production
- [learn-nock-fundamentals-workflow](./skills/learn-nock-fundamentals-workflow/) - 5-phase interactive learning path
- [debug-nock-execution-workflow](./skills/debug-nock-execution-workflow/) - 5-phase systematic debugging from error analysis to resolution
- [hoon-to-nock-workflow](./skills/hoon-to-nock-workflow/) - 4-phase workflow analyzing Hoon compilation output
- [nock-implement-exercise-workflow](./skills/nock-implement-exercise-workflow/) - 6-phase hands-on guided exercises
- [orchestrate-interpreter-workflow](./skills/orchestrate-interpreter-workflow/) - Complete Nock mastery orchestration

#### Urbit Operations Workflows (11)
- [deploy-planet-workflow](./skills/deploy-planet-workflow/) - Bare-metal planet deployment (10 phases)
- [deploy-vps-planet-workflow](./skills/deploy-vps-planet-workflow/) - VPS-optimized deployment
- [deploy-groundseg-workflow](./skills/deploy-groundseg-workflow/) - Multi-ship Docker orchestration
- [deploy-fleet-workflow](./skills/deploy-fleet-workflow/) - Kubernetes fleet deployment for 100+ ships
- [setup-production-workflow](./skills/setup-production-workflow/) - 20-phase security hardening
- [setup-monitoring-workflow](./skills/setup-monitoring-workflow/) - Observability stack deployment
- [setup-cicd-pipeline-workflow](./skills/setup-cicd-pipeline-workflow/) - CI/CD for ship updates
- [troubleshoot-ship-workflow](./skills/troubleshoot-ship-workflow/) - Systematic diagnostics
- [migrate-deployment-workflow](./skills/migrate-deployment-workflow/) - Zero-downtime migration
- [optimize-performance-workflow](./skills/optimize-performance-workflow/) - Performance tuning
- [orchestrate-deployment-workflow](./skills/orchestrate-deployment-workflow/) - Intelligent deployment coordination

### 💻 Interaction Skills (2)

Ship terminal and socket communication tools.

- [urbit-conn](./skills/urbit-conn/) - Programmatic ship interaction via `conn.c` socket. Supports scry, runtime queries, thread execution, raw event injection. Templates for `|pack`, `|meld`, `+code`, `+vats`, `|ota`, `|install`.
- [urbit-terminal](./skills/urbit-terminal/) - Interactive dojo access through screen or tmux. Discovers sessions, sends commands, captures output. Includes dojo command reference and safety guards.

## Installation

Add skills directory to your Claude Code configuration:

```bash
/add-dir /path/to/urbit-skills
```

Or place individual skill directories into `~/.claude/skills/`.

## Requirements

### Knowledge & Assistant Skills
No specific requirements - provide reference material and guidance.

### Workflow Skills
Depend on task-specific tools (e.g., file editing, terminal access, network connectivity).

### Interaction Skills
- **urbit-conn**: `urbit` binary on PATH (required). `click` on PATH (recommended). `nc` (netcat) for raw socket communication.
- **urbit-terminal**: `screen` or `tmux` with a ship running in a named session.

## Contributing

To create new skills for this repository, see [AGENTS.md](AGENTS.md) for a complete guide on skill creation, frontmatter configuration, and best practices for Urbit-specific skills.

## License

MIT License - see [LICENSE](LICENSE) file for details.
