# 🔬 Extension & Plugin Skills Library (`KARTHIKEYASHARMA672/extension-skills`)

> **Comprehensive repository of official Antigravity extension and plugin skills migrated from local installations to GitHub to optimize agent context window and token usage. Queried dynamically on demand.**

---

### 📋 Metadata & Repository Information

| Property | Value |
| :--- | :--- |
| **Repository** | [`KARTHIKEYASHARMA672/extension-skills`](https://github.com/KARTHIKEYASHARMA672/extension-skills) |
| **Total Skills** | **88 Specialized Skills** (48 Science, 37 Vercel, 3 Android) |
| **Tier Classification** | **Tier 4: Extension & Plugin Skills** (On-Demand Agent Capabilities) |
| **Author / Maintainer** | [KARTHIKEYASHARMA672](https://github.com/KARTHIKEYASHARMA672) |
| **Status** | 🟢 **100% Secret-Free, Validated YAML Frontmatter, Clean Syntax** |
| **Companion Repos** | [`KARTHIKEYASHARMA672/skills`](https://github.com/KARTHIKEYASHARMA672/skills) (52 Core) · [`KARTHIKEYASHARMA672/new-skills`](https://github.com/KARTHIKEYASHARMA672/new-skills) (521 Curated) · [`KARTHIKEYASHARMA672/claude-skills`](https://github.com/KARTHIKEYASHARMA672/claude-skills) (90 Multi-Modal) |

---

## 📑 Table of Contents

- [1. Purpose & Token Optimization Architecture](#1-purpose--token-optimization-architecture)
- [2. Skills Breakdown](#2-skills-breakdown)
  - [2.1 Science Suite (48 Skills)](#21-science-suite-48-skills)
  - [2.2 Vercel Suite (37 Skills)](#22-vercel-suite-37-skills)
  - [2.3 Android Suite (3 Skills)](#23-android-suite-3-skills)
- [3. Dynamic On-Demand Usage Protocol](#3-dynamic-on-demand-usage-protocol)

---

## 1. 🌐 Purpose & Token Optimization Architecture

Locally mounted plugin skills inject metadata directly into the Antigravity session context on every turn, consuming **12,500+ tokens (62.6%+ of the customization budget)**. By hosting them in this canonical GitHub repository:
1. **Zero Context Overhead:** The agent starts every session with minimal token consumption.
2. **On-Demand Intelligence:** Antigravity fetches and studies only the specific science, vercel, or android skills required for a particular task via `github-mcp-server` or the GitHub API.
3. **Preserved Capabilities:** All documentation, scripts, schemas, and workflows remain completely accessible and version-controlled.

---

## 2. 📚 Skills Breakdown

### 2.1 Science Suite (48 Skills)
Located in `science/`:
- **Structural Biology & Folding:** `alphafold-database-fetch-and-analyze`, `biomolecular-structure-viewer`, `foldseek-structural-search`, `pdb-database`, `pymol`, `protein-sequence-msa`, `protein-sequence-similarity-search`.
- **Cheminformatics & Pharmacology:** `chembl-database`, `cheminformatics-cofolding`, `cheminformatics-core`, `cheminformatics-doc2mol`, `cheminformatics-ml`, `cheminformatics-physics`, `cheminformatics-reactions`, `pubchem-database`, `rdkit-general`, `openfda-database`, `clinical-trials-database`, `opentargets-database`.
- **Genomics, Variants & Regulation:** `alphagenome-atlas-website-links`, `alphagenome-single-variant-analysis`, `alphagenome-variant-impact-score`, `clinvar-database`, `dbsnp-database`, `encode-ccres-database`, `ensembl-database`, `gnomad-database`, `gtex-database`, `human-protein-atlas-database`, `interpro-database`, `jaspar-database`, `ncbi-sequence-fetch`, `quickgo-database`, `reactome-database`, `string-database`, `ucsc-conservation-and-tfbs`, `unibind-database`, `uniprot-database`.
- **Literature & Discovery:** `literature-search-arxiv`, `literature-search-biorxiv`, `literature-search-europepmc`, `literature-search-openalex`, `pubmed-database`, `predictingthepast`, `embl-ebi-ols`, `credentials`, `uv`, `workflow-skill-creator`.

### 2.2 Vercel Suite (37 Skills)
Located in `vercel/`:
- **Deployment, CI/CD & Platform:** `access-protected-vercel-deployment`, `deployments-cicd`, `domains`, `env-vars`, `microfrontends`, `offload-to-sandbox`, `routing-middleware`, `runtime-cache`, `vercel-agent`, `vercel-cli`, `vercel-connect`, `vercel-firewall`, `vercel-functions`, `vercel-sandbox`, `vercel-services`, `vercel-storage`, `vercel-tracing`, `verification`.
- **AI & Agent Architecture:** `ai-gateway`, `ai-sdk`, `build-agents`, `chat-sdk`, `eve`, `is-agentic`.
- **Performance & Framework Patterns:** `cdn-caching`, `create-a-backend`, `custom-metrics`, `daemons`, `flags-sdk`, `marketplace`, `queues`, `react-best-practices`, `vercel-flags`, `workflow`, `knowledge-update`, `bootstrap`, `auth`.

### 2.3 Android Suite (3 Skills)
Located in `android/`:
- `android-cli`: Command-line tool instructions for Android projects, virtual devices, and SDKs.
- `android-device-hub`: Sidecar instructions for controlling, mirroring, and inspecting connected devices and emulators.
- `compose-preview`: Jetpack Compose @Preview rendering and visual review tools.

---

## 3. 🚀 Dynamic On-Demand Usage Protocol

Antigravity coding agents access these skills dynamically:
1. **Analyze:** Parse the user request to determine if science, Vercel, or Android specialized guidance is required.
2. **Fetch:** Query `KARTHIKEYASHARMA672/extension-skills` via `github-mcp-server` (`get_file_contents` / `search_code`).
3. **Execute:** Follow the verified patterns, scripts, and workflows without inflating prompt token overhead.
