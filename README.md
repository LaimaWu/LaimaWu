# LaimaWu

I build open-source developer tools and contribute to coding-agent workflows.
My current focus is read-only investigation, practical agent integration, and
reproducible validation: commands that can be rerun, observations tied to a
revision, and conclusions that stay within the evidence.

## Experimental tools

- [Issue Boundary Evidence](https://github.com/LaimaWu/issue-boundary-evidence)
  — A read-only Python CLI that collects traceable dependency, runtime, upstream,
  and version-history evidence from public GitHub issues, with explicit evidence gaps.
- [Release State Reconcile](https://github.com/LaimaWu/release-state-reconcile)
  — A read-only Python CLI that reconciles fixes, backports, checks, release notes,
  and published releases while keeping missing links and unknown states visible.

Both are experimental tools for investigation and review; maintainer judgment
remains part of the workflow.

## Selected merged contributions

- [wanaku-barn #175](https://github.com/wanaku-ai/wanaku-barn/pull/175)
  — Added skill installation for Codex, Claude, and custom destinations, with
  existing-target protection and JVM/native validation.
- [anythingmcp #886](https://github.com/HelpCode-ai/anythingmcp/pull/886)
  — Added shared agent instructions based on exercised setup and validation commands,
  documenting contribution boundaries and local test failures.
- [Semantiq #156](https://github.com/Logorythmus-org/Semantiq/pull/156)
  — Corrected Python SDK examples and platform-specific checksum instructions,
  with executable-example verification.

## Integration and validation

For [ripwire's Hermes integration](https://github.com/redhat-et/ripwire/issues/69#issuecomment-6006900867),
I tested a running Hermes agent on macOS x86_64: MCP registration and scoped MCP
use worked, while default-mode tool selection and a wrapper path containing spaces
exposed limitations. These observations apply to the reported versions and environment.

My ripwire PRs for [Elixir quote handling](https://github.com/redhat-et/ripwire/pull/380)
and [Python import captures](https://github.com/redhat-et/ripwire/pull/382) remain open.

I value reproducible tests, traceable evidence, and clear disclosure of failures,
uncertainty, and scope.
