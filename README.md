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
- [hoon-basics](./hoon-basics/) - Quick reference for syntax fundamentals
- [hoon-fundamentals](./hoon-fundamentals/) - Subject-oriented programming and noun model
- [rune-reference](./rune-reference/) - Complete reference for 90+ runes

**Language**:
- [type-system](./type-system/) - Structural typing, auras, molds, type casting
- [functional-programming-patterns](./functional-programming-patterns/) - Pure functions, higher-order functions, recursion
- [advanced-patterns](./advanced-patterns/) - Doors, wet gates, mold builders, metaprogramming
- [irregular-forms](./irregular-forms/) - Syntactic shortcuts and best practices
- [hoon-style-guide](./hoon-style-guide/) - Naming conventions and code organization

**Data**:
- [data-structures](./data-structures/) - Lists, sets, maps, mops, jars, jugs
- [string-handling](./string-handling/) - Cord, tape, term, knot types
- [serialization](./serialization/) - JSON, vases, jam/cue, marks

**Libraries**:
- [stdlib-reference](./stdlib-reference/) - Comprehensive standard library documentation
- [zuse-libraries](./zuse-libraries/) - HTTP, JSON, crypto, scry utilities

**Applications**:
- [gall-agents](./gall-agents/) - Complete Gall agent development lifecycle
- [generators](./generators/) - Naked, %say, %ask generators for CLI tools
- [parsing](./parsing/) - Parser combinators and custom parsers
- [app-development-workflow](./app-development-workflow/) - End-to-end development process
- [sail-markup](./sail-markup/) - HTML templating in Hoon

#### Nock Development (12 skills)

**Foundation**:
- [nock-essentials](./nock-essentials/) - Nouns (atoms/cells), reduction model, evaluation semantics
- [nock-operators](./nock-operators/) - Complete reference for 6 operators (?, +, =, /, #, *)
- [nock-instructions](./nock-instructions/) - All 13 reduction rules (0-12) with examples

**Implementation**:
- [nock-interpreter-patterns](./nock-interpreter-patterns/) - Design patterns for building Nock VMs
- [nock-multi-language-implementations](./nock-multi-language-implementations/) - C, Python, Rust, Haskell, JavaScript patterns

**Optimization**:
- [nock-jetting-optimization](./nock-jetting-optimization/) - Jet acceleration: hint processing, cold/hot/warm states
- [nock-performance-profiling](./nock-performance-profiling/) - CPU/memory profiling, benchmarking

**Advanced**:
- [nock-tree-addressing](./nock-tree-addressing/) - Binary tree addressing: axis encoding, slot calculation
- [nock-cores-arms-batteries](./nock-cores-arms-batteries/) - Core structure pattern: batteries, payloads, arms
- [nock-metacircular-evaluation](./nock-metacircular-evaluation/) - Self-interpretation: +mock (Nock-in-Nock)

**Integration**:
- [nock-hoon-compilation](./nock-hoon-compilation/) - How Hoon compiles to Nock
- [nock-specification-reference](./nock-specification-reference/) - Complete formal Nock 4K specification

#### Urbit Operations (23 skills)

**Core Fundamentals**:
- [urbit-fundamentals](./urbit-fundamentals/) - Nock, Hoon, Arvo, vanes, Azimuth, Ames
- [ship-deployment-guide](./ship-deployment-guide/) - Step-by-step deployment procedures
- [urbit-troubleshooting](./urbit-troubleshooting/) - Systematic diagnostics

**Deployment & Infrastructure**:
- [vps-deployment-providers](./vps-deployment-providers/) - DigitalOcean, Linode, Vultr, AWS, Hetzner, OVH
- [groundseg-installation](./groundseg-installation/) - Docker setup, Anchor networking, MinIO S3
- [groundseg-troubleshooting](./groundseg-troubleshooting/) - Container issues, DNS, SSL certificates
- [kubernetes-urbit](./kubernetes-urbit/) - StatefulSets, persistent volumes, GitOps
- [multi-ship-orchestration](./multi-ship-orchestration/) - Resource allocation, network isolation

**Networking & Security**:
- [anchor-networking](./anchor-networking/) - Reverse proxy, Let's Encrypt SSL, custom domains
- [network-security-advanced](./network-security-advanced/) - Zero-trust networking, VPNs, network policies
- [container-security](./container-security/) - User namespaces, capabilities, AppArmor, Seccomp
- [advanced-security-patterns](./advanced-security-patterns/) - Defense-in-depth, intrusion detection

**Storage & Backup**:
- [minio-s3-integration](./minio-s3-integration/) - Self-hosted S3 for ship storage
- [backup-disaster-recovery](./backup-disaster-recovery/) - Automated backups, restoration procedures
- [disaster-recovery-advanced](./disaster-recovery-advanced/) - Multi-region failover, cross-region replication

**Monitoring & Operations**:
- [monitoring-observability](./monitoring-observability/) - Prometheus, Grafana, Loki, AlertManager
- [performance-optimization](./performance-optimization/) - Disk I/O tuning, memory optimization, network throughput
- [performance-profiling](./performance-profiling/) - Bottleneck identification, capacity planning
- [sla-management](./sla-management/) - Uptime targets, incident response, error budgets

**Management**:
- [fleet-operations](./fleet-operations/) - Terraform IaC, Helm templating, staged OTA updates
- [managed-hosting-comparison](./managed-hosting-comparison/) - Tlon vs Red Horizon vs UrbitHost
- [app-development-workflow](./app-development-workflow/) - Local development, desk publishing

**Compliance**:
- [compliance-frameworks](./compliance-frameworks/) - GDPR, HIPAA, SOC2, ISO 27001

### 🤖 Assistant Skills (6)

Active guidance skills for development, debugging, and operations.

#### Hoon Development
- [hoon-expert-assistant](./hoon-expert-assistant/) - Expert Hoon coding help, type errors, performance optimization
- [debugging-specialist-assistant](./debugging-specialist-assistant/) - Systematic debugging from compilation errors to runtime failures

#### Nock Development
- [nock-interpreter-engineer-assistant](./nock-interpreter-engineer-assistant/) - Build Nock interpreters in multiple languages
- [nock-optimization-specialist-assistant](./nock-optimization-specialist-assistant/) - Optimize Nock performance (10x-1000x speedups)
- [nock-fundamentals-tutor-assistant](./nock-fundamentals-tutor-assistant/) - Educational Nock learning from nouns through cores

#### Urbit Operations
- [performance-engineer-assistant](./performance-engineer-assistant/) - Performance troubleshooting, tuning, capacity planning

### 🔄 Workflow Skills (26)

Structured step-by-step processes for complex tasks.

#### Hoon Development Workflows (8)
- [hoon-review-workflow](./hoon-review-workflow/) - 5-phase code review (quality, security, performance, maintainability)
- [hoon-optimize-workflow](./hoon-optimize-workflow/) - 4-phase performance optimization with benchmarking
- [hoon-debug-workflow](./hoon-debug-workflow/) - 5-phase systematic debugging workflow
- [hoon-refactor-workflow](./hoon-refactor-workflow/) - 6-phase safe refactoring while preserving correctness
- [hoon-test-workflow](./hoon-test-workflow/) - 5-phase testing (unit, integration, property-based, TDD)
- [hoon-migrate-workflow](./hoon-migrate-workflow/) - 5-phase safe state migration for Gall agents
- [hoon-scaffold-workflow](./hoon-scaffold-workflow/) - 6-phase project bootstrapping with best practices
- [orchestrate-feature-workflow](./orchestrate-feature-workflow/) - End-to-end feature development orchestration

#### Nock Development Workflows (7)
- [build-nock-interpreter-workflow](./build-nock-interpreter-workflow/) - 8-phase workflow for building production-ready interpreters
- [optimize-nock-performance-workflow](./optimize-nock-performance-workflow/) - 6-phase systematic optimization from profiling through production
- [learn-nock-fundamentals-workflow](./learn-nock-fundamentals-workflow/) - 5-phase interactive learning path
- [debug-nock-execution-workflow](./debug-nock-execution-workflow/) - 5-phase systematic debugging from error analysis to resolution
- [hoon-to-nock-workflow](./hoon-to-nock-workflow/) - 4-phase workflow analyzing Hoon compilation output
- [nock-implement-exercise-workflow](./nock-implement-exercise-workflow/) - 6-phase hands-on guided exercises
- [orchestrate-interpreter-workflow](./orchestrate-interpreter-workflow/) - Complete Nock mastery orchestration

#### Urbit Operations Workflows (11)
- [deploy-planet-workflow](./deploy-planet-workflow/) - Bare-metal planet deployment (10 phases)
- [deploy-vps-planet-workflow](./deploy-vps-planet-workflow/) - VPS-optimized deployment
- [deploy-groundseg-workflow](./deploy-groundseg-workflow/) - Multi-ship Docker orchestration
- [deploy-fleet-workflow](./deploy-fleet-workflow/) - Kubernetes fleet deployment for 100+ ships
- [setup-production-workflow](./setup-production-workflow/) - 20-phase security hardening
- [setup-monitoring-workflow](./setup-monitoring-workflow/) - Observability stack deployment
- [setup-cicd-pipeline-workflow](./setup-cicd-pipeline-workflow/) - CI/CD for ship updates
- [troubleshoot-ship-workflow](./troubleshoot-ship-workflow/) - Systematic diagnostics
- [migrate-deployment-workflow](./migrate-deployment-workflow/) - Zero-downtime migration
- [optimize-performance-workflow](./optimize-performance-workflow/) - Performance tuning
- [orchestrate-deployment-workflow](./orchestrate-deployment-workflow/) - Intelligent deployment coordination

### 💻 Interaction Skills (2)

Ship terminal and socket communication tools.

- [urbit-conn](./urbit-conn/) - Programmatic ship interaction via `conn.c` socket. Supports scry, runtime queries, thread execution, raw event injection. Templates for `|pack`, `|meld`, `+code`, `+vats`, `|ota`, `|install`.
- [urbit-terminal](./urbit-terminal/) - Interactive dojo access through screen or tmux. Discovers sessions, sends commands, captures output. Includes dojo command reference and safety guards.

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
