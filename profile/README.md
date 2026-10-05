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

The repos below are listed by the name they are expected to carry after the reshape. Names are
planned, not final. "Live" means the content exists today at the linked repo. "Coming" means the
repo has not been built yet.

## Vendor-neutral core

| Planned repo | Status | What it holds |
| --- | --- | --- |
| `architect-skills` | Live as [multi-cloud-ai-architect](https://github.com/oci-ai-architects/multi-cloud-ai-architect) | Skills for RAG, MCP, agent orchestration, AI security, FinOps, diagramming, IaC and Kubernetes |
| `patterns` | Coming | Solution patterns with a mapping to each provider |
| `genai-guides` | Live as [oci-genai-guides](https://github.com/oci-ai-architects/oci-genai-guides) | Provider comparisons, migration guides between providers, a production series |
| `ai-coe-starter-kit` | Live as [oci-ai-coe-starter-kit](https://github.com/oci-ai-architects/oci-ai-coe-starter-kit) | Skill packs for setting up an AI Center of Excellence, team by team. OCI is the first implementation |

## Provider packs

| Planned repo | Status | What it holds |
| --- | --- | --- |
| `pack-oci` | Live as [claude-code-oci-ai-architect-skills](https://github.com/oci-ai-architects/claude-code-oci-ai-architect-skills), with harness adapters in [cline-oci-ai-architect-skills](https://github.com/oci-ai-architects/cline-oci-ai-architect-skills) and [codex-oci-ai-architect-skills](https://github.com/oci-ai-architects/codex-oci-ai-architect-skills) | OCI GenAI, AI Agent Platform, Autonomous Database, ADK and Agent Spec skills |
| `pack-aws` | Coming | Bedrock, AgentCore, SageMaker |
| `pack-azure` | Coming | Azure OpenAI, AI Foundry, AI Search |
| `pack-gcp` | Coming | Vertex AI, Gemini API, ADK, A2A |
| `pack-cloudflare` | Coming | Workers AI, AI Gateway, Vectorize, Agents SDK |
| `pack-vercel` | Coming | AI SDK, AI Gateway, Sandbox, Workflow |
| `pack-railway` | Coming | Templates, services, volumes and private networking for agent runtimes |

Every pack will follow one contract: `SKILL.md` skills, adapters for each coding agent (Claude
Code, Codex, Cline, Cursor, Roo, Windsurf), references, a price table with source links and
retrieval dates, evals, and a disclaimer.

## Stacks and examples

| Planned repo | Status | What it holds |
| --- | --- | --- |
| `stacks-oci` | Live as [oci-one-click-stacks](https://github.com/oci-ai-architects/oci-one-click-stacks) and [openclaw-on-oci](https://github.com/oci-ai-architects/openclaw-on-oci) | One-click Resource Manager stacks |
| `example-invoice-extraction` | Live as [invoice-oci](https://github.com/oci-ai-architects/invoice-oci) | End-to-end invoice extraction: object storage, an LLM, JSON, an ERP interface |

## Contributing

Issues and pull requests are welcome on any repo. Start with the repo's `CONTRIBUTING.md` where
there is one. Never commit credentials, tenancy IDs or private data.

---

<sub>Independent community project, maintained by <a href="https://github.com/frankxai">frankxai</a>. Not affiliated with, endorsed by, or sponsored by Oracle, Amazon, Microsoft, Google, Cloudflare, Vercel or Railway. All product names and marks are trademarks of their respective owners.</sub>
