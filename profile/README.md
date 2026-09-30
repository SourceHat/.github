# SourceHat Labs

Independent research in applied AI and security.

We investigate how software behaves under real operating constraints: what models can do on available hardware, how to measure their performance, and where complex systems fail.

## Applied AI

Local inference, quantization, model evaluation, and the trade-offs between quality, memory, latency, and cost. Our focus is practical experimentation and methods that make results easier to interpret and reproduce.

Selected public work:

- [SourceHat RLCD](https://huggingface.co/SourceHat-Labs/RLCD-Qwen3.5-9B-Gated-Decision) - a research release for bounded decisions using a frozen Qwen3.5-9B backbone and learned scoring heads. Given caller-supplied choices, it can propose a complete object, return alternatives, or abstain. The model card includes aggregate evaluation results, limitations, and a pinned inference example.

## Security

Research spanning smart contracts, operating systems, embedded devices, and vehicle software.

Selected public work:

- [Chronomaly on LG webOS](https://github.com/AnalyticETH/chronomaly-webos) - Linux kernel exploitation and persistent root access on consumer hardware.
- [Tesla security research](https://github.com/AnalyticETH/tesla-security-research) - vulnerability research on Model 3/Y infotainment systems, including root access and persistence.

## Earlier work

SourceHat began as Solidity Finance in 2020, initially focused on smart-contract audits. It became SourceHat in 2023 as the security practice broadened. Historical reports remain available in the [audit archive](https://sourcehat.com/audits/).

[Website](https://sourcehat.com/) | [Hugging Face](https://huggingface.co/SourceHat-Labs)
