# Changelog

All notable changes to this project are documented in this file.

## [1.0.2] - 2026-08-09

Updated the internship report content and PDF inclusion workflow.

### Fixed

- Included all pages of the internship-program PDF with `pages=-`.
- Refined the weekly tasks and conclusion to match the completed AI-agent internship work.

## [1.0.1] - 2026-08-09

Updated the English internship report with additional container-runtime and hypervisor analysis.

### Added

- Explicit comparison of OS-level containers, gVisor, Firecracker, and QEMU-based hypervisor isolation.
- Discussion of VM-level security boundaries, startup latency, and memory-overhead trade-offs.

### Fixed

- Updated the internship-program PDF inclusion to embed all pages with `pages=-` while preserving the requested scaling.
- Refined the weekly internship tasks and conclusion to match the completed AI-agent internship work.
- Removed outdated generic bug-fix claims from the final review section.

## [1.0.0] - 2026-08-09

Initial release of the English internship report for the AI Applied Engineer internship at GreenNode.

### Added

- AI internship report covering LLM fundamentals, agent frameworks, sandbox research, infrastructure analysis, and SRE Agent development.
- Figures and supporting images for LangGraph, Jaeger, OpenSandbox, Deep Agent, and agent harness architecture.
- LaTeX CI workflow for building and releasing the report PDF from the `master` branch.
