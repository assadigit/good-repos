---
source: https://github.com/ggml-org/whisper.cpp
aliases:
  - whisper.cpp
  - ggml-org/whisper.cpp
tags: [c++, c-cpp, speech-to-text, inference, whisper, self-hosted, openai, transformer, speech-recognition, c, cuda, metal]
category: LLM-Tools
stars: 53352
org: ggml-org
primary_language: C++
languages: [C++, C, Cuda, Metal, GLSL]
credibility_score: 70.5/100
date_processed: 2026-09-01
last_release: 2026-08-20
cover: attachments/banners/whisper_cpp_banner.png

---

![banner](attachments/banners/whisper_cpp_banner.png)

# whisper.cpp

> **TL;DR:** High-performance C/C++ inference engine for OpenAI's Whisper speech-to-text model with multi-GPU and CPU support.

**`ggml-org/whisper.cpp`** · ⭐ 53,352 · 🔧 C++

## What is it?
whisper.cpp is a high-performance, dependency-free C/C++ port of OpenAI's Whisper automatic speech recognition (ASR) model. It enables local transcription of audio to text without requiring Python, PyTorch, or any external ML framework, making it ideal for embedded systems, low-latency pipelines, and environments where heavy runtime dependencies are undesirable. The project is maintained by ggml-org, the same organization behind llama.cpp, and carries an MIT license with active CI and packaging via Conan and npm.

Key capabilities include first-class Apple Silicon optimization through ARM NEON intrinsics, the Accelerate framework, Metal, and Core ML; AVX intrinsics for x86 CPUs; VSX intrinsics for POWER architectures; mixed F16/F32 precision; integer quantization; and zero runtime memory allocations. It supports CPU-only inference as well as GPU acceleration via NVIDIA CUDA, AMD ROCm, Vulkan, and AMD Ryzen AI NPU, making it one of the most portable local ASR runtimes available.

The project ships with a simple C API and command-line tools, allowing developers to drop speech recognition into existing applications with minimal integration overhead. Its 53k+ stars and 6k+ forks reflect broad adoption across hobbyist and production contexts alike.

## How does it work?
Under the hood, whisper.cpp reimplements Whisper's transformer encoder-decoder architecture in plain C/C++ using the ggml tensor library (the same math backend used by llama.cpp). The model weights are loaded from GGML/GGUF files, and inference proceeds through a sequence of matrix multiplications, attention layers, and positional encodings that are dispatched to the optimal hardware path at compile time. On Apple Silicon, kernels are vectorized with ARM NEON and offloaded to Metal or Core ML; on x86, AVX intrinsics accelerate the linear algebra; on NVIDIA and AMD GPUs, CUDA and ROCm backends handle tensor operations in parallel.

The runtime is designed for zero allocations during inference: all buffers are pre-allocated at model load time, and the decode loop reuses them across steps. Mixed F16/F32 precision and optional integer quantization (Q8_0, Q5_1, etc.) let users trade memory footprint for speed depending on the target platform. The result is a self-contained inference binary or static library that can be linked into any C/C++ project without pulling in a Python interpreter or GPU driver stack beyond what the chosen backend requires.

## Why is it important? (Core Value)
For a software engineer building AI-agent pipelines and developer tooling, whisper.cpp removes the single biggest friction point in adding voice input to a product: the need for a cloud API or a heavyweight Python runtime. Because it is a plain C/C++ library with zero external dependencies, it can be embedded directly into agent runtimes, MCP servers, or CLI tools that already target C/C++, Rust (via FFI), or Go—exactly the kind of low-level integration the user's knowledge base tracks. It also serves as a self-hosted alternative to OpenAI's hosted Whisper API and to Python-based ASR stacks like faster-whisper, aligning with the user's stated preference for self-hostable, homelab-friendly software.

In practice, this means an AI agent can accept voice commands or transcribe meeting recordings entirely on-device, with no network round-trip and no per-token API cost. The ggml-org provenance (the same team behind llama.cpp) signals long-term maintenance and a predictable release cadence, which matters when the library is a dependency in production code. For the user's Obsidian vault, whisper.cpp slots neatly into the AI-Domain / LLM-Tools domain as the reference implementation for local ASR, complementing llama.cpp for text generation.

## Key Features & Technologies
- Plain C/C++ with zero runtime dependencies and no Python required
- Apple Silicon optimization via ARM NEON, Accelerate, Metal, and Core ML
- GPU acceleration through NVIDIA CUDA, AMD ROCm, Vulkan, and Ryzen AI NPU
- Integer quantization (Q8_0, Q5_1) and mixed F16/F32 precision for memory control
- AVX intrinsics for x86 and VSX intrinsics for POWER architectures
- MIT-licensed with active CI, Conan packaging, and npm distribution
- Maintained by ggml-org (same team as llama.cpp) with 53k+ stars

## Difference from Others
Compared to OpenAI's original Python/PyTorch Whisper implementation, whisper.cpp eliminates the entire Python runtime, CUDA wheel stack, and GPU driver dependencies in favor of a single C/C++ codebase that compiles on any platform. Versus faster-whisper (another Python-based optimization), it trades Python-level flexibility for a smaller binary surface area and direct linkage into native binaries—critical when embedding ASR into an agent's core loop rather than calling it as a subprocess.

Against general-purpose C/C++ ML runtimes like ONNX Runtime or TensorRT, whisper.cpp is model-specific: it does not aim to be a generic inference engine but instead hard-codes Whisper's architecture for maximum kernel-level optimization on the target hardware. That specialization—combined with the ggml tensor backend shared with llama.cpp—makes it the go-to choice when the only task is transcribing audio quickly and locally, without the overhead of a general-purpose ML framework.

## 🏢 Organization & Credibility
- **Developer:** ggml-org
- **Reputation:** Unknown
- **Stars:** 53,352
- **Forks:** 6124
- **Recent Activity:** 419 commits in 3 months
- **Credibility Score:** 70.5/100 (Average)
- **Languages:** C++, C, Cuda, Metal, GLSL
- **Last Release:** 2026-08-20
- **Quality:** ✅ good

## 💡 My Ideas & Notes
[Add your personal thoughts here]

## 📱 Social Signal (Manual)
- **Source:** [Dropdown: Reddit/X/Instagram/GitHub Search/Other]
- **Link:** [URL]
- **Notes:** [Context]

## 📔 Journal
[Date] - [Your experiences]

---
*Source: [GitHub](https://github.com/ggml-org/whisper.cpp)*
