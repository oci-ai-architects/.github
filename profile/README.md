<h3 align="center">AI Architects</h3>

<p align="center">
  Open skills, patterns and worked examples for architects who design AI systems on any cloud.
</p>

<p align="center">
  <em>Independent community project.</em>
</p>

---

This org started as a set of Oracle Cloud Infrastructure skill packs. It is being reshaped into a
cloud-agnostic home: one vendor-neutral core of architecture skills and patterns, plus one pack per
provider. OCI stays as one of those packs.

The tables below list each repo by its current name first, followed by the name it is expected to
carry after the reshape. Planned names are not final. "Live" means the content exists today at the
linked repo. "Coming" means the repo has not been built yet.

## Vendor-neutral core

| Current repo | Planned name | Status | What it holds |
| --- | --- | --- | --- |
| [multi-cloud-ai-architect](https://github.com/oci-ai-architects/multi-cloud-ai-architect) | `architect-skills` (planned name) | Live | Skills for RAG, MCP, agent orchestration, AI security, FinOps, diagramming, IaC and Kubernetes |
| Not built yet | `patterns` (planned name) | Coming | Solution patterns with a mapping to each provider |
| [oci-genai-guides](https://github.com/oci-ai-architects/oci-genai-guides) | `genai-guides` (planned name) | Live | Provider comparisons, migration guides between providers, an article series on GenAI systems on OCI |
| [oci-ai-coe-starter-kit](https://github.com/oci-ai-architects/oci-ai-coe-starter-kit) | `ai-coe-starter-kit` (planned name) | Live | Skill packs for setting up an AI Center of Excellence, team by team. OCI is the first implementation |

## Provider packs

| Current repo | Planned name | Status | What it holds |
| --- | --- | --- | --- |
| [claude-code-oci-ai-architect-skills](https://github.com/oci-ai-architects/claude-code-oci-ai-architect-skills), with harness adapters in [cline-oci-ai-architect-skills](https://github.com/oci-ai-architects/cline-oci-ai-architect-skills) and [codex-oci-ai-architect-skills](https://github.com/oci-ai-architects/codex-oci-ai-architect-skills) | `pack-oci` (planned name) | Live | OCI GenAI, AI Agent Platform, Autonomous Database, ADK and Agent Spec skills |
| Not built yet | `pack-aws` (planned name) | Coming | Bedrock, AgentCore, SageMaker |
| Not built yet | `pack-azure` (planned name) | Coming | Azure OpenAI, AI Foundry, AI Search |
| Not built yet | `pack-gcp` (planned name) | Coming | Vertex AI, Gemini API, ADK, A2A |
| Not built yet | `pack-cloudflare` (planned name) | Coming | Workers AI, AI Gateway, Vectorize, Agents SDK |
| Not built yet | `pack-vercel` (planned name) | Coming | AI SDK, AI Gateway, Sandbox, Workflow |
| Not built yet | `pack-railway` (planned name) | Coming | Templates, services, volumes and private networking for agent runtimes |

Proposed, not yet adopted: a shared contract for every pack, covering `SKILL.md` skills, adapters
for each coding agent (Claude Code, Codex, Cline, Cursor, Roo, Windsurf), references, a price table
with source links and retrieval dates, evals, and a disclaimer. A link will be added here once the
spec is published.

## Stacks and examples

| Current repo | Planned name | Status | What it holds |
| --- | --- | --- | --- |
| [oci-one-click-stacks](https://github.com/oci-ai-architects/oci-one-click-stacks) and [openclaw-on-oci](https://github.com/oci-ai-architects/openclaw-on-oci) | `stacks-oci` (planned name) | Live | One-click Resource Manager stacks |
| [invoice-oci](https://github.com/oci-ai-architects/invoice-oci) | `example-invoice-extraction` (planned name) | Live | End-to-end invoice extraction: object storage, an LLM, JSON, an ERP interface |

## Licences

Each repository's own `LICENSE` file governs its contents, and the licences differ. Several repos
(invoice-oci, oci-genai-guides, oci-ai-coe-starter-kit and the three OCI skill packs) are MIT.
multi-cloud-ai-architect, oci-one-click-stacks and openclaw-on-oci have no `LICENSE` file yet, and a
repo without one grants no licence until one is added. The Apache-2.0 `LICENSE` in this `.github`
repository applies only to the content of this `.github` repository, including this profile.

## Contributing

Issues and pull requests are welcome on any repo. Start with the repo's `CONTRIBUTING.md` where
there is one. Never commit credentials, tenancy IDs or private data.

---

<sub>Independent community project, maintained by <a href="https://github.com/frankxai">frankxai</a>. Not affiliated with, endorsed by, or sponsored by Oracle Corporation or Oracle Cloud Infrastructure (OCI), or by Amazon, Microsoft, Google, Cloudflare, Vercel or Railway. Oracle and OCI are trademarks or registered trademarks of Oracle Corporation. Other names are marks of their respective owners.</sub>
