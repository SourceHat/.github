# SourceHat Labs

Independent research in AI and security.

We study AI models, inference systems, and software security. We publish models, experiments, and technical findings, with the methods and limitations needed to examine the work.

## AI

Model research and evaluation, bounded decisions, and inference engineering under real memory, latency, and hardware constraints.

- [SourceHat RLCD](https://huggingface.co/SourceHat-Labs/RLCD-Qwen3.5-9B-Gated-Decision) is a research release for bounded decisions using a frozen Qwen3.5-9B backbone and learned scoring heads. Given caller-supplied choices, it can propose a complete object, return alternatives, or abstain. The release includes the learned heads, inference implementation, aggregate evaluation, and documented limitations; base model weights are separate.

## Security

Research across software, operating systems, embedded devices, vehicle systems, and smart contracts.

- [Tesla security research](https://github.com/AnalyticETH/tesla-security-research): a six-report historical SourceHat program covering diagnostic access, persistence, authentication, vehicle-to-cloud services, and telemetry integrity. Individual reports retain their disclosure and remediation records.
- [Chronomaly on LG webOS](https://github.com/AnalyticETH/chronomaly-webos): SourceHat's adaptation of the upstream Chronomaly exploit to ARM64 consumer hardware, with original attribution and tested-target limits.

## Earlier work

SourceHat began as Solidity Finance in 2020, initially focused on smart-contract audits. The practice broadened into software security under the SourceHat name in 2023 and operated until 2025. In early 2026, the focus shifted to independent research. Original reports remain available in the [historical audit archive](https://sourcehat.com/audits/).

[Website](https://sourcehat.com/) | [Hugging Face](https://huggingface.co/SourceHat-Labs)
