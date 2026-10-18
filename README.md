# Kaylor Tate Céspedes

**Systems & AI Evaluation Engineer** | San José, Costa Rica  
Specializing in **High-Throughput LLM Serving**, **AST Static Analysis**, **Deterministic Alignment Verification**, and **Inference Optimization**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-keytate1--creator-181717?style=flat&logo=github)](https://github.com/keytate1-creator)

---

### Technical Focus & Research Areas

* **Deterministic LLM Output Verification:** Static analysis over Abstract Syntax Trees (ASTs), McCabe cyclomatic complexity auditing, and zero-tolerance negative constraint checking at 29k+ samples/sec.
* **Corpus Engineering & Decontamination:** Mass-scale MinHash and Locality-Sensitive Hashing (LSH) for pre-training corpora de-duplication and benchmark leak prevention.
* **Inference Runtime Acceleration:** Radix Tree (Prefix Trie) Key-Value cache management with O(1) LRU eviction, and lossless Speculative Decoding with tree-structured candidate verification (Medusa/Eagle).
* **High-Assurance AI Evaluation:** Rubric adherence, RLHF preference calibration, and side-by-side model auditing under defense and enterprise-grade constraints.

---

### Flagship Open-Source Engineering Suites

| Project | Description | Core Architecture |
| :--- | :--- | :--- |
| **[`eval-guard`](https://github.com/keytate1-creator/eval-guard)** | Deterministic AST & Constraint Evaluation Engine | Static AST visitor, McCabe complexity analyzer, token budgeting |
| **[`corpus-dedup-lsh`](https://github.com/keytate1-creator/corpus-dedup-lsh)** | Vectorized MinHash LSH Deduplication Engine | 64-bit universal permutations, band-bucket hashing, Union-Find |
| **[`kv-radix-cache`](https://github.com/keytate1-creator/kv-radix-cache)** | Radix Prefix Trie & KV Cache Eviction Runtime | Edge-compressed prefix trie, O(1) doubly-linked list LRU |
| **[`spec-draft-eval`](https://github.com/keytate1-creator/spec-draft-eval)** | Speculative Decoding & Hypothesis Tree Verification | Lossless rejection sampling, residual recovery, Monte Carlo engine |

---

### Core Technical Proficiencies

* **Languages:** Python (3.10+, CPython Internals, AST), Modern C++ (C++17/20), Rust (Foundations), Bash/POSIX.
* **AI & Serving Runtimes:** PyTorch, vLLM, TensorRT-LLM, HuggingFace Transformers, SGLang Architecture.
* **Systems & Data Engineering:** Algorithms & Data Structures, Locality-Sensitive Hashing, Memory Management, Linux/POSIX System Internals, Git CI/CD.
* **Methodologies:** Test-Driven Development (TDD), High-Assurance Evaluation, Static Code Analysis, Empirical Benchmarking.

---
*Maintained by Kaylor Tate Céspedes.*
