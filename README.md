# AI Research

Research artifacts from AI collaboration experiments at ECAD Labs.

## Papers

### Human-AI API Testing
**"Scoped AI Collaboration for API Test Automation"** (January 2026)

A methodology for human-AI collaboration in API integration testing using large language models. Introduces:
- Six-step workflow loop for collaborative test development
- "Work Universe" concept for constraining AI scope
- Multi-agent collaboration patterns (Claude Code + GPT 5.2)
- Activity logging and dual-channel reporting
- Error monitoring integration via Model Context Protocol (MCP)

**Files:**
- `papers/human-ai-api-testing/human_ai_api_testing.tex` - LaTeX source
- `papers/human-ai-api-testing/human_ai_api_testing.pdf` - Compiled PDF

---

### Croquet AI
**"Expert-Guided Training of a Neural Association Rules Croquet Simulator"** (2025)

Deep reinforcement learning approach to Association Croquet, demonstrating:
- Dueling DQN architecture adapted for long-horizon physical games
- Expert-derived reward shaping from elite tournament data (2020-2025)
- Analysis of why naive reward functions produce suboptimal play
- Pioneer-focused break construction vs. naive ball clustering
- Automated pipeline for extracting tactics from video transcripts

**Files:**
- `papers/croquet-ai/croquet_ai_paper.tex` - LaTeX source
- `papers/croquet-ai/croquet_ai_paper.pdf` - Compiled PDF

**Related project:** [croquet-simulator](https://github.com/michaelkernaghan/croquet-simulator)

---

### BLS Signing on Raspberry Pi
**"Remote BLS Signing on Raspberry Pi: A Study in Lightweight Cryptographic Infrastructure"** (August 2025)

Investigation into deploying Tezos BLS remote signing on commodity hardware:
- Boneh-Lynn-Shacham (BLS) signatures on Raspberry Pi 4B
- Aggregated attestations for proof-of-stake consensus
- Signing latency and throughput benchmarks on Seoulnet testnet
- Feasibility of threshold signatures on low-power devices

**Files:**
- `papers/bls-raspberry-pi/bls_rpi_signing.tex` - LaTeX source
- `papers/bls-raspberry-pi/bls_rpi_signing.pdf` - Compiled PDF

**Related project:** [mk-tezos-rpi-bls-signer](https://github.com/michaelkernaghan/mk-tezos-rpi-bls-signer)

---

## Structure

```
ai-research/
├── papers/                    # Academic papers and preprints
│   ├── human-ai-api-testing/  # API testing methodology paper
│   ├── croquet-ai/            # Croquet reinforcement learning paper
│   └── bls-raspberry-pi/      # Tezos BLS signing on Raspberry Pi
├── experiments/               # Experimental code and results
└── notes/                     # Research notes and drafts
```

## Author

Michael Kernaghan
ECAD Labs
michaelkernaghan@ecadlabs.com

## Acknowledgments

Research conducted in collaboration with Claude Code (Anthropic) and GPT 5.2 (OpenAI).
