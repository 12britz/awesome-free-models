# Awesome Free Models [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of free AI models, APIs, and tools you can use without paying a cent.

![Last Updated](https://img.shields.io/badge/Last%20Checked-July%2024%2C%202026-brightgreen?style=for-the-badge)
![Models](https://img.shields.io/badge/Models-39-blue?style=flat-square)
![Tools](https://img.shields.io/badge/Tools-194-blue?style=flat-square)
![Sections](https://img.shields.io/badge/Sections-16-blue?style=flat-square)
![License](https://img.shields.io/badge/License-CC0-lightgrey?style=flat-square)

> ✅ All links verified live on July 24, 2026. 270+ URLs checked. Added 7 new free API providers (SambaNova, OVHcloud, Chutes.ai, ModelScope, Z.ai, LongCat AI, Coze). Removed Glhf.chat (service discontinued). All other links working.

Running AI shouldn't require a credit card. This list curates genuinely free models — open-weight models you can self-host, free API tiers from major providers, and tools to run everything locally.

---

## Contents

- [🧠 Open-Weight Models](#-open-weight-models)
- [🔌 Free API Providers](#-free-api-providers)
- [🔀 Free API Routers](#-free-api-routers)
- [💻 Local Inference Tools](#-local-inference-tools)
- [💬 AI Chatbot UIs](#-ai-chatbot-uis)
- [🤖 AI Coding Assistants](#-ai-coding-assistants)
- [📝 Code Models](#-code-models)
- [🔍 RAG & Vector Databases](#-rag--vector-databases)
- [🧩 Agentic Frameworks](#-agentic-frameworks)
- [🎛 Fine-tuning Tools](#-fine-tuning-tools)
- [✨ Prompt Engineering Tools](#-prompt-engineering-tools)
- [📊 Datasets](#-datasets)
- [☁ Model Hosting Platforms](#-model-hosting-platforms)
- [📚 Learning Resources](#-learning-resources)
- [🏆 Resources & Leaderboards](#-resources--leaderboards)
- [👥 Communities](#-communities)

---

## 🧠 Open-Weight Models

> 📅 Last checked: July 24, 2026

Notable open-weight models you can download and run on your own hardware.

- [Llama 4 Scout / Maverick](https://huggingface.co/meta-llama) — Meta's latest MoE generation. Scout: 109B, 10M context. Maverick: 402B, 1M context. Native multimodal. [[License]](https://github.com/meta-llama/llama-models/blob/main/README.md#llama-models-1)
- [DeepSeek V4](https://huggingface.co/deepseek-ai) — Latest generation with extreme cost-efficiency. MIT license.
- [DeepSeek-V4-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash) — **Apr 2026.** Efficiency-focused variant of DeepSeek V4. 1M token context, optimized for fast inference. MIT license.
- [Gemma 4 31B / 26B MoE / E4B / E2B](https://huggingface.co/google) — Fully permissive Apache 2.0. 256K context, native multimodal. New standard for open-weight.
- [Inkling (Thinking Machines Lab)](https://huggingface.co/thinkingmachines/Inkling) — **Jul 2026.** 975B MoE (41B active). Leading US open-weight model. Native multimodal (text, image, audio). Apache 2.0. 1M context.
- [GLM-5.2 (Zhipu AI)](https://huggingface.co/zai-org) — 744B MoE model optimized for autonomous coding and engineering tasks. 1M-token context. MIT license.
- [LongCat-2.0 (ByteDance)](https://huggingface.co/bytedance) — Large-scale open-weight model for heavy agentic coding. MIT license.
- [MiniMax M3](https://huggingface.co/MiniMaxAI) — Frontier-tier 1M context, native multimodal + computer use. MSA architecture.
- [Trinity (Arcee AI)](https://huggingface.co/arcee-ai) — 400B parameter enterprise model. Apache 2.0.
- [Step 3.7 Flash (StepFun)](https://huggingface.co/stepfun-ai) — **May 2026.** Apache 2.0. Native multimodal (image+video), strong agentic performance. Efficient enough for high-end local hardware.
- [Kimi K2.6 (Moonshot AI)](https://huggingface.co/moonshotai) — **Apr 2026.** 1T-parameter MoE model. Modified MIT license. Exceptional coding (SWE-Bench ~54%) and multi-agent swarm orchestration.
- [Qwen 3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B) — **Apr 2026.** MoE variant with only 3B active parameters. Extremely efficient for consumer hardware. Apache 2.0.
- [InternLM 3 (Shanghai AI Lab)](https://huggingface.co/internlm) — **Early 2026.** Strong long-context reasoning and agentic performance. Competitive in open-weight benchmarks.
- [MiMo-V2.5-Pro (Xiaomi)](https://huggingface.co/XiaomiMiMo/MiMo-V2.5-Pro) — **Apr 2026.** 1.02T-parameter MoE (42B active). Optimized for complex agentic tasks, coding, and long-context.
- [Bonsai 8B (PrismML)](https://huggingface.co/prism-ml/Bonsai-8B-gguf) — **Apr 2026.** Groundbreaking 1-bit quantized model. Extremely efficient for edge and consumer hardware (Apple Silicon).
- [Mistral Small 3.1 (Mistral)](https://huggingface.co/mistralai/Mistral-Small-3.1-24B-Instruct-2503) — **Mar 2025.** Versatile 24B multimodal model. Strong text performance with native image understanding and 128K context. Apache 2.0.
- [Mistral Small 4 (Mistral)](https://huggingface.co/mistralai/Mistral-Small-4-119B-2603) — **Mar 2026.** Hybrid MoE (6.5B active params) unifying instruction, reasoning, and multimodal capabilities. Efficient frontier-class model. Apache 2.0.
- [Command A+ (Cohere)](https://huggingface.co/CohereLabs/command-a-plus-05-2026-w4a4) — **May 2026.** Enterprise multimodal MoE optimized for sovereignty and multilingual RAG across 48 languages. Apache 2.0.
- [Hermes 4 (NousResearch)](https://huggingface.co/NousResearch/Hermes-4-70B) — **Feb 2026.** Self-improving agentic model with closed-loop learning. Curates own memory and builds skills from experience. Apache 2.0.
- [Snowflake Arctic](https://huggingface.co/Snowflake/snowflake-arctic-instruct) — **Apr 2024.** Enterprise MoE model balancing high-quality performance with efficient training costs. Optimized for complex data operations. Apache 2.0.
- [Falcon 3 (TII)](https://huggingface.co/tiiuae/Falcon3-7B-Instruct) — **Dec 2024.** Compact high-performance model with strong reasoning. Designed for efficient deployment on resource-constrained hardware. TII Falcon-LLM License 2.0.
- [Apple OpenELM](https://huggingface.co/Apple/OpenELM-3B) — **Apr 2024.** Family of efficient on-device SLMs using layer-wise attention scaling. Runs locally on Apple Silicon with full privacy. Apple Sample Code License.

---

## 🔌 Free API Providers

> 📅 Last checked: July 24, 2026

Providers offering free tiers to access models via API — no local hardware required.

- [Google AI Studio](https://aistudio.google.com/) — **Most generous free tier.** Access Gemini 2.5 Flash, Gemini 2.0 Flash, and other models. Generous rate limits for prototyping.
- [OpenRouter](https://openrouter.ai/) — Aggregates 500+ models. Filter by "Free" to see models available at no cost. Includes experimental and subsidized open-weight models.
- [AnyAPI](https://anyapi.ai/) — 400+ models with OpenAI-compatible API. Free tier: 100K tokens/day, unlimited users. Includes free and basic models. No credit card required.
- [Groq](https://console.groq.com/) — Ultra-fast inference. Free tier includes Llama, Gemma, Mixtral, Whisper models with generous daily rate limits.
- [Hugging Face Inference Providers](https://huggingface.co/inference-api) — Free tier for thousands of community models. Rate-limited but excellent for testing.
- [NVIDIA NIM](https://build.nvidia.com/) — Free API access to accelerated versions of Llama, Mistral, Gemma, and more on NVIDIA infrastructure.
- [DeepInfra](https://deepinfra.com/) — Serverless inference. Free tier with daily rate limits for popular open-source models.
- [Together AI](https://www.together.ai/) — Free trial credits for new users. Fast inference on open-source models.
- [Fireworks AI](https://fireworks.ai/) — Free tier for community models. Optimized for low latency.
- [SiliconFlow](https://siliconflow.cn/) — Rising platform with free access to many open-source models.
- [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/) — Free tier for running select open-source models at the edge.
- [Black Forest Labs](https://api.bfl.ai/) — Free Flux 2 Dev and Flux Kontext Dev image generation via API. Rate-limited, no credit card required.
- [Replicate](https://replicate.com/) — Free tier with limited credits for running open-source models.
- [Poe (Quora)](https://poe.com/) — Free tier with daily credits for GPT-4 mini, Claude instant, and community bots.
- [Qwen Studio (Alibaba)](https://chat.qwen.ai/) — Free access to Qwen 3.6-Plus, Qwen 3.6-Max, and other Qwen models via web chat and API. 1M token context for agentic coding.
- [Ollama Cloud](https://ollama.com/cloud) — Free tier for running open-source models on Ollama's cloud infrastructure. Light usage with session limits (reset every 5 hours) and weekly limits. 1 concurrent model. Same `ollama run` command as local. Prompt/response data never logged or trained on.
- [Mistral AI (La Plateforme)](https://mistral.ai/) — Free API tier with access to Mistral Large, Mistral Nemo, Codestral and more. 1 req/s, 500k tokens/min. Requires phone verification and data usage opt-in.
- [Cohere](https://cohere.com/) — Free evaluation API key for Command R, Command R+, Embed, and Rerank models. 20 req/min, 1,000 req/month.
- [DeepSeek Platform](https://deepseek.com/) — Free API credits for new users (5M tokens). Access to DeepSeek V4, DeepSeek-R1, and other models. Generous free allocation.
- [GitHub Models](https://github.com/marketplace?type=models) — Free tier for GitHub users. Access GPT-4o, Llama 3.3, Mistral, and more with rate-limited playground and API.
- [Hyperbolic](https://www.hyperbolic.ai/) — Open-access AI cloud with affordable inference. Free compute credits via referral program. Supports Llama, Qwen, DeepSeek, and other open models.
- [Novita AI](https://novita.ai/) — Free credits for testing 100+ models including Llama, Qwen, DeepSeek, and Mistral. OpenAI-compatible API with competitive pricing beyond the free tier.
- [Anakin.ai](https://anakin.ai/) — **30 daily free credits** for accessing multiple AI models. Web chat interface and API access. Supports GPT-4, Claude, and open-weight models.
- [Nebius AI](https://nebius.com/) — **$100 free credits** for new users. AI Studio with access to Llama, Qwen, DeepSeek, and other open-weight models. Fast inference on NVIDIA H100 infrastructure.
- [Fal.ai](https://fal.ai/) — Free starter credits for AI inference. Fast, serverless platform supporting Llama, Flux, and Stable Diffusion models. Pay-as-you-go beyond free tier.
- [Vercel AI Gateway](https://vercel.com/ai) — **$5/month free credits** for the AI Gateway. Proxy and cache requests across multiple LLM providers. SDK is open-source and free.
- [AI21 Labs](https://www.ai21.com/) — **$10 trial credits** for accessing Jamba 1.5, Jamba 1.6, and other AI21 models. Valid for 3 months. Requires account sign-up.
- [Amazon Bedrock](https://aws.amazon.com/bedrock/) — **$200 AWS credits** for new customers. Access to Llama, Mistral, Claude, Titan, and other foundation models via API.
- [Microsoft Foundry (Azure)](https://azure.microsoft.com/en-us/products/ai-foundry/) — **$200 free trial credits** (30 days). Access GPT-4o, Llama, Mistral, Phi, and other models via Azure's unified AI platform.
- [RunPod](https://www.runpod.io/) — Free credits for serverless GPU inference. Deploy open-weight models as serverless endpoints. Supports Llama, Qwen, DeepSeek, and more.
- [Cerebras](https://cerebras.ai/) — Free tier with ultra-fast inference on Llama, Gemma, and Mistral models. No credit card required. **Note: Model availability fluctuates.**
- [BazaarLink](https://bazaarlink.ai/) — Free OpenAI-compatible API with `auto:free` routing to zero-cost models. No credit card, no trial expiry. 10 RPM, 130 req/day.
- [Kimi API (Moonshot)](https://platform.moonshot.cn/) — Free tier for new accounts with access to Kimi K2.5 (128K context). Also free via NVIDIA NIM. OpenAI-compatible.
- [Alibaba DashScope](https://dashscope.aliyun.com/) — Free tier for Qwen models. 1M tokens/month. OpenAI-compatible API.
- [SambaNova Cloud](https://cloud.sambanova.ai/) — Free tier with $5 credits (30-day). Fast RDU inference for Llama 3.1 405B, Llama 3.3 70B, DeepSeek V3.1/V3.2, Qwen 2.5, gpt-oss-120b. 20 RPM, 200K tokens/day. No credit card required.
- [OVHcloud AI Endpoints](https://www.ovhcloud.com/en/public-cloud/ai-endpoints/) — EU-hosted, GDPR-compliant free tier. No registration required for anonymous tier. Models: Qwen, Mistral, Llama, DeepSeek, gpt-oss-120B, embeddings, image generation. 12 RPM. OpenAI-compatible.
- [Chutes.ai](https://chutes.ai/) — Community-powered free GPU inference for open-source models. DeepSeek-R1, Llama 3.1 70B, Qwen 2.5 72B. OpenAI-compatible API. No credit card.
- [ModelScope](https://modelscope.cn/) — Chinese platform with 50+ free open models. Qwen, DeepSeek, GLM, and more. No credit card required.
- [Z.ai (Zhipu AI)](https://open.bigmodel.cn/) — Free tier for GLM models including GLM-4.5, GLM-4V. No credit card required.
- [LongCat AI](https://longcat.chat/) — Free API for LongCat open-weight models. One-time 10M token grant after signup + KYC. Free cached tokens. OpenAI-compatible. MIT license.
- [Coze (ByteDance)](https://www.coze.com/) — Free bot-building platform with API access to GPT-4o, Gemini 1.5 Pro, and other models. No credit card required. OpenAI-compatible.

---

## 🔀 Free API Routers

> 📅 Last checked: July 24, 2026

Open-source tools that route requests across multiple AI providers — unified API, automatic failover, and cost optimization.

- [9Router](https://9router.com/) — Open-source gateway connecting 40+ providers with RTK token compression (2-4x reduction). One API key for all services. MIT license. [GitHub](https://github.com/decolua/9router)
- [OmniRoute](https://omniroute.online/) — Full-stack AI gateway with 250+ providers, 90+ free. TypeScript, runs on Web/Desktop/Android. Prompt compression, 3-level proxy for geo restrictions. [GitHub](https://github.com/diegosouzapw/OmniRoute)
- [LiteLLM](https://litellm.ai/) — Python-based proxy unifying 100+ LLMs behind a single API. Spend tracking, virtual keys, production-ready. MIT license. [GitHub](https://github.com/BerriAI/litellm)
- [Portkey AI Gateway](https://portkey.ai/) — Production guardrails and routing for AI apps. Hybrid open-source (community) and managed (enterprise) tiers. [GitHub](https://github.com/Portkey-AI/gateway)

---

## 💻 Local Inference Tools

> 📅 Last checked: July 24, 2026

Run models on your own machine — no API keys needed, full privacy.

- [Ollama](https://ollama.com/) — The easiest way to run local LLMs. One command to download and run any model. macOS, Linux, Windows. [GitHub](https://github.com/ollama/ollama)
- [LM Studio](https://lmstudio.ai/) — Polished desktop GUI. Browse, download, and chat with models. Built-in model browser and local API server.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) — High-performance C++ inference engine. Runs on CPU and GPU. Supports GGUF quantization. Powers most other local tools.
- [Jan](https://www.jan.ai/) — Open-source ChatGPT alternative for desktop. Built-in model downloader, local API server. [GitHub](https://github.com/janhq/jan)
- [GPT4All](https://www.nomic.ai/gpt4all) — ⚠️ **Unmaintained since Feb 2025.** Privacy-focused local chatbot. Runs on consumer hardware. Built-in model browser. [GitHub](https://github.com/nomic-ai/gpt4all)
- [text-generation-webui (Oobabooga)](https://github.com/oobabooga/textgen) — Feature-rich web UI. Supports multiple backends (Transformers, llama.cpp, ExLlama, AutoGPTQ).
- [LocalAI](https://localai.io/) — Drop-in OpenAI API replacement. Run models locally with an OpenAI-compatible API. [GitHub](https://github.com/mudler/LocalAI)
- [KoboldCPP](https://github.com/LostRuins/koboldcpp) — Single-file executable for running GGUF models. Focused on story generation but general-purpose.
- [llamafile (Mozilla)](https://github.com/mozilla-ai/llamafile) — Distributable single-file executables that run LLMs. No installation needed.
- [vLLM](https://github.com/vllm-project/vllm) — High-throughput production inference engine. Uses PagedAttention for efficient serving.
- [SGLang](https://github.com/sgl-project/sglang) — Fast inference framework with structured generation and RadixAttention.
- [TensorRT-LLM (NVIDIA)](https://github.com/NVIDIA/TensorRT-LLM) — NVIDIA's optimized inference engine. Best performance on NVIDIA GPUs.
- [ExLlamaV3](https://github.com/turboderp-org/exllamav3) — Optimized inference for Llama-family models. Successor to ExLlamaV2. Fastest option for single-GPU inference.
- [Aphrodite Engine](https://github.com/dphnAI/sonar) — High-performance LLM serving engine with advanced quantization support.
- [TabbyAPI](https://github.com/theroyallab/tabbyAPI) — Lightweight, fast OpenAI-compatible API server for ExLlamaV2.
- [LlamaEdge](https://llamaedge.com/) — Lightweight inference framework for edge devices. OpenAI-compatible API for open-source models. Runs on WasmEdge for portability. [GitHub](https://github.com/LlamaEdge/LlamaEdge)
- [MLC LLM](https://github.com/mlc-ai/mlc-llm) — Universal deployment engine by UW/SJTU. Runs LLMs on any hardware — laptops, phones, browsers. OpenAI-compatible API.
- [WebLLM](https://github.com/mlc-ai/web-llm) — In-browser LLM inference via WebGPU. Runs models directly in your browser with zero setup. No server needed.
- [FastChat (LMSYS)](https://github.com/lm-sys/FastChat) — Open platform for training, serving, and evaluating LLMs. Provides OpenAI-compatible API and web UI for local models.
- [Hugging Face TGI](https://github.com/huggingface/text-generation-inference) — Production-grade serving toolkit for large language models. Optimized for high throughput on local hardware. **Note: Archived Mar 2026, maintenance mode. Consider vLLM or SGLang.**
- [DeepSpeed (Microsoft)](https://github.com/microsoft/DeepSpeed) — Deep learning optimization library with inference acceleration. Enables running larger models on limited hardware through ZeRO optimization.
- [AirLLM](https://github.com/lyogavin/airllm) — ⚠️ **Unmaintained since Aug 2024.** Run large models (70B+) on consumer hardware with limited memory. Loads models layer-by-layer for extreme memory efficiency.
- [AI Toolkit for VS Code (Microsoft)](https://marketplace.visualstudio.com/items?itemName=ms-windows-ai-studio.windows-ai-studio) — VS Code extension to browse, test, fine-tune, and deploy models locally. Integrates ONNX and llama.cpp.
- [Ollama Grid Search](https://github.com/dezoito/ollama-grid-search) — Desktop utility for systematic model evaluation. Test multiple models, prompts, and inference parameters side-by-side via a Rust/React GUI.

---

## 💬 AI Chatbot UIs

> 📅 Last checked: July 24, 2026

Free, open-source web interfaces for chatting with AI models — self-host or use hosted versions.

- [Open WebUI](https://openwebui.com/) — Feature-rich ChatGPT-like interface for Ollama and OpenAI-compatible backends. RAG, image generation, multi-user. [GitHub](https://github.com/open-webui/open-webui)
- [LibreChat](https://www.librechat.ai/) — Open-source ChatGPT clone supporting 40+ providers, multi-user, plugins, and RAG. **Note: Acquired by ClickHouse.** [GitHub](https://github.com/danny-avila/LibreChat)
- [AnythingLLM](https://anythingllm.com/) — All-in-one desktop app for chatting with documents and models. Built-in RAG pipeline. [GitHub](https://github.com/Mintplex-Labs/anything-llm)
- [Big-AGI](https://big-agi.com/) — Feature-rich AI chat with personas, multi-model support, voice, and code execution. [GitHub](https://github.com/enricoros/big-agi)
- [Lobe Chat](https://lobehub.com/) — Multi-agent orchestration platform with plugin system and multi-provider support. [GitHub](https://github.com/lobehub/lobehub)

---

## 🤖 AI Coding Assistants

> 📅 Last checked: July 24, 2026

Free tools that integrate AI into your development workflow.

- [Continue.dev](https://www.continue.dev/) — **Acquired by Cursor.** Open-source AI code assistant for VS Code and JetBrains. [GitHub](https://github.com/continuedev/continue)
- [Aider](https://aider.chat/) — AI pair programming in the terminal. Edits code in your local git repo. Supports GPT, Claude, and local models. [GitHub](https://github.com/Aider-AI/aider)
- [Gemini CLI (Google)](https://github.com/google-gemini/gemini-cli) — **Jul 2026.** Open-source terminal agent with generous free Gemini quota. Supports agentic coding workflows.
- [Kilo Code](https://github.com/Kilo-Org/kilocode) — **2026.** VS Code/JetBrains agentic coding extension with model-agnostic support and Plan/Act oversight.
- [Tabby](https://www.tabbyml.com/) — Self-hosted AI coding assistant with no dependency on external services. [GitHub](https://github.com/TabbyML/tabby)
- [Cody (Sourcegraph)](https://sourcegraph.com/cody) — Free tier for individuals. Chat, autocomplete, and commands with codebase context.
- [Llama Coder (Nutlope)](https://llamacoder.together.ai/) — Free AI code generation tool. Generate entire apps from prompts.
- [Bolt.new (StackBlitz)](https://bolt.new/) — Free tier for AI-powered full-stack web app development in browser.
- [Claude Code (Anthropic)](https://code.claude.com/docs) — Terminal-based AI coding assistant. Most features require a Claude subscription or API credits. Limited free usage via terminal CLI.
- [Cursor 3](https://cursor.com/) — **Apr 2026.** AI-native code editor with deep model integration and agentic features. Free tier available.
- [CodeBuff](https://www.codebuff.com/) — CLI-based AI coding assistant that understands entire codebases. Multi-agent architecture, works with any model provider through natural language instructions.
- [Pi](https://pi.dev/) — Open-source terminal AI coding agent with a unified multi-provider API. Model-agnostic, supports OpenAI, Anthropic, Google, and any OpenAI-compatible endpoint. Extensible plugin architecture. [GitHub](https://github.com/earendil-works/pi)
- [Cline](https://cline.bot/) — Popular autonomous VS Code agent. Creates/edits files, runs terminal commands, browses web. Open-source, BYOK (bring your own API key). [GitHub](https://github.com/cline/cline)
- [OpenHands](https://www.openhands.dev/) — Autonomous AI software engineer. Navigates file systems, runs shell commands, tests code in browser. Self-hostable. [GitHub](https://github.com/All-Hands-AI/OpenHands)
- [Goose](https://goose-docs.ai/) — Open-source CLI agent for complex software engineering tasks. Extensible plugin system. Built by Block/Square. [GitHub](https://github.com/aaif-goose/goose)

---

## 📝 Code Models

> 📅 Last checked: July 24, 2026

Specialized for code generation, completion, and analysis.

- [MAI-Code-1-Flash (Microsoft)](https://huggingface.co/microsoft) — **Jun 2026.** Microsoft's open-weight coding model for lowering infrastructure costs.
- [DeepSeek Coder](https://huggingface.co/deepseek-ai) — State-of-the-art open-weight code generation. DeepSeek's coder series leads SWE-bench. MIT license.
- [Qwen2.5-Coder (Alibaba)](https://huggingface.co/collections/Qwen/qwen25-coder) — Highly capable code model series (1.5B–32B). Excellent balance of speed and quality. Apache 2.0.
- [Codestral (Mistral)](https://huggingface.co/mistralai/Codestral-22B-v0.1) — Mistral's dedicated code generation model — fill-in-the-middle, completion, and instruction.
- [CodeGemma (Google)](https://huggingface.co/google/codegemma-7b) — Google's Gemma architecture fine-tuned for code completion and instruction. Apache 2.0.
- [StarCoder2 (BigCode)](https://huggingface.co/bigcode/starcoder2-15b) — Transparently trained code model covering 619 languages. OpenRAIL-M license.
- [Yi-Coder (01.AI)](https://huggingface.co/01-ai/Yi-Coder-9B-Chat) — Efficient coding model with strong long-context understanding. Yi License (Apache 2.0 compatible).
- [Granite Code (IBM)](https://huggingface.co/ibm-granite/granite-8b-code-base-4k) — IBM's enterprise-grade code model, available in multiple sizes. Apache 2.0.
- [Phi-4-mini (Microsoft)](https://huggingface.co/microsoft/Phi-4-mini-instruct) — Lightweight model optimized for reasoning and code. Punches above its weight class. MIT license.
- [Qwen3-Coder-Next (Alibaba)](https://huggingface.co/Qwen/Qwen3-Coder-Next) — **Early 2026.** Latest generation of Qwen's code series. Strong reasoning and long-context coding capabilities. Apache 2.0.
- [CodeLlama (Meta)](https://huggingface.co/meta-llama/CodeLlama-7b-hf) — **Aug 2023.** Llama 2-based code generation pioneer. Supports infilling, completion, and instruction. Llama 2 Community License.
- [WizardCoder (WizardLM)](https://huggingface.co/WizardLMTeam/WizardCoder-15B-V1.0) — **2023.** Evol-Instruct fine-tuned for complex coding tasks. Strong general code generation performance. Apache 2.0.
- [OpenCodeInterpreter](https://huggingface.co/m-a-p/OpenCodeInterpreter-DS-6.7B) — **2024.** Integrates execution feedback to iteratively improve generated code. Bridges generation and execution. Apache 2.0.
- [Stable Code 3B (Stability AI)](https://huggingface.co/stabilityai/stable-code-3b) — **Aug 2023.** Lightweight 3B code model optimized for fill-in-the-middle. Efficient for local autocompletion. StabilityAI license.
- [CodeGeeX2 (THUDM)](https://huggingface.co/zai-org/codegeex2-6b) — **2023.** Multilingual code model supporting 20+ languages. Strong in both Chinese and English code tasks. Apache 2.0.
- [CodeT5+ (Salesforce)](https://huggingface.co/Salesforce/codet5p-16b) — **2023.** Encoder-decoder architecture unifying code generation, completion, and understanding. BSD-3 license.
- [SantaCoder (BigCode)](https://huggingface.co/bigcode/santacoder) — **2023.** Light 1.1B model specialized for Python, Java, and JavaScript. Fast and efficient for IDE integration.

---

## 🔍 RAG & Vector Databases

> 📅 Last checked: July 24, 2026

Free tools for building retrieval-augmented generation pipelines — vector storage, embedding search, and document retrieval.

- [Chroma](https://www.trychroma.com/) — AI-native open-source embedding database. Runs in-process, no GPU needed. [GitHub](https://github.com/chroma-core/chroma)
- [Qdrant](https://qdrant.tech/) — High-performance vector search engine. Free tier on Qdrant Cloud or self-host via Docker. [GitHub](https://github.com/qdrant/qdrant)
- [pgvector](https://github.com/pgvector/pgvector) — Vector similarity search inside PostgreSQL. Free if you already run Postgres.
- [LanceDB](https://lancedb.com/) — Developer-friendly vector database built on Lance columnar format. Runs locally, no server needed. [GitHub](https://github.com/lancedb/lancedb)
- [Weaviate](https://weaviate.io/) — Open-source vector database. Free sandbox tier on Weaviate Cloud. [GitHub](https://github.com/weaviate/weaviate)
- [Milvus (Zilliz)](https://zilliz.com/) — Cloud-native vector database. Free tier on Zilliz Cloud or self-host. [GitHub](https://github.com/milvus-io/milvus)
- [txtai](https://neuml.github.io/txtai/) — AI-powered semantic search and RAG in a single Python package. [GitHub](https://github.com/neuml/txtai)
- [R2R (SciPhi)](https://github.com/SciPhi-AI/R2R) — Production-ready RAG engine with API, user management, and observability. **Note: Last release Jun 2025. Consider alternatives like Dify or LangGraph.**
- [Docling (IBM)](https://www.docling.ai/) — Document understanding and conversion for RAG pipelines. Extracts PDFs, images, and more. [GitHub](https://github.com/docling-project/docling)
- [Unstructured.io](https://unstructured.io/) — Preprocessing toolkit for documents (PDF, HTML, Word) for RAG pipelines. Free tier available.

---

## 🧩 Agentic Frameworks

> 📅 Last checked: July 24, 2026

Free, open-source frameworks for building AI agents and multi-agent systems.

- [LangGraph (LangChain)](https://langchain-ai.github.io/langgraph/) — Low-level framework for building stateful, multi-agent applications. [GitHub](https://github.com/langchain-ai/langgraph)
- [CrewAI](https://crewai.com/) — Multi-agent framework for orchestrating specialized AI agents to work together. [GitHub](https://github.com/crewAIInc/crewAI)
- [AutoGen (Microsoft)](https://microsoft.github.io/autogen/stable/) — Extensible framework for building multi-agent conversations. **Note: In maintenance mode.** [GitHub](https://github.com/microsoft/autogen)
- [Agno (formerly Phidata)](https://www.agno.com/) — Full-stack AI framework for building multimodal agents with memory, knowledge, and tools. [GitHub](https://github.com/agno-agi/agno)
- [PydanticAI](https://pydantic.dev/docs/ai/overview/) — Agent framework by Pydantic with type-safe outputs and dependency injection. [GitHub](https://github.com/pydantic/pydantic-ai)
- [Mastra](https://mastra.ai/) — TypeScript framework for building AI applications and agent workflows. [GitHub](https://github.com/mastra-ai/mastra)
- [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/) — Lightweight SDK for building single and multi-agent systems. [GitHub](https://github.com/openai/openai-agents-python)
- [Semantic Kernel (Microsoft)](https://learn.microsoft.com/en-us/semantic-kernel/) — SDK for orchestrating AI agents with planners, memory, and connectors. [GitHub](https://github.com/microsoft/semantic-kernel)
- [Dify](https://dify.ai/) — LLM app development platform with visual workflow builder and agent capabilities. [GitHub](https://github.com/langgenius/dify)
- [Flowise](https://flowiseai.com/) — Low-code visual LLM flow builder with drag-and-drop interface. **Note: Acquired by Workday.** [GitHub](https://github.com/FlowiseAI/Flowise)
- [Fazm](https://github.com/mediar-ai/fazm) — **Apr 2026.** Open-source local computer-use agent for macOS. Drives apps via accessibility APIs, model-agnostic, faster than screenshot-based agents.
- [Smolagents (Hugging Face)](https://github.com/huggingface/smolagents) — Minimalist agent library where agents "think in code." Lightweight, zero boilerplate. Supports code agents and tool-calling agents.
- [Swarms](https://github.com/kyegomez/swarms) — ⚠️ **Unmaintained since Dec 2024.** Enterprise-grade multi-agent orchestration framework. Scalable infrastructure for autonomous agent swarms. Highly modular.
- [Letta (MemGPT)](https://github.com/letta-ai/letta) — Framework for long-term agent memory. Virtual memory management that pages data in/out of context like an OS. Persistent agents.
- [Griptape](https://github.com/griptape-ai/griptape) — Enterprise agent framework with strictly typed Pipelines, Workflows, and Agents. Structure-first, production-ready.
- [Atomic Agents](https://github.com/Eigenwise/atomic-agents) — Framework inspired by Atomic Design. Compose agents from small, reusable, modular components. Testable and scalable.
- [PraisonAI](https://github.com/MervinPraison/PraisonAI) — Low-code multi-agent framework. Define agent roles, tasks, and flows via YAML configuration. Wraps underlying agent frameworks.
- [Cognee](https://github.com/topoteretes/cognee) — GraphRAG framework for agent knowledge management. Builds interconnected knowledge graphs from unstructured data.
- [MetaGPT](https://github.com/FoundationAgents/MetaGPT) — Multi-agent framework simulating a full software team. Assigns Agent, Product Manager, Engineer roles. Implements SOPs for end-to-end code generation. **Note: Last release Apr 2024. Effectively unmaintained.**
- [ChatDev (OpenBMB)](https://github.com/OpenBMB/ChatDev) — Virtual software company driven by multi-agent collaboration. Follows waterfall model through design, coding, testing, and documentation.
- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) — The original autonomous agent experiment. Sets its own goals, iterates on tasks, and executes without continuous human input. Web browsing and file management.
- [Bee Agent Framework (IBM)](https://github.com/i-am-bee/beeai-framework) — Production-ready framework for building reliable AI agents in Python and TypeScript. Modular, with built-in observability and IBM research optimizations.
- [Eliza (elizaOS)](https://github.com/elizaOS/eliza) — Multi-platform agent framework for creating character-driven AI agents. Handles social media interaction, complex decision-making, and autonomous behavior across platforms.
- [Qwen-Agent (Alibaba)](https://github.com/QwenLM/Qwen-Agent) — Agent framework tightly integrated with the Qwen model family. Optimized for function calling, code execution, RAG, and tool use with Qwen models.
- [AGiXT](https://github.com/Josh-XT/AGiXT) — Extensible modular AI agent automation platform. Plugin system for swapping LLMs, memory backends, and tools. Highly customizable agent workflows.

---

## 🎛 Fine-tuning Tools

> 📅 Last checked: July 24, 2026

Tools to fine-tune free models on your own data — all free and open-source.

- [Unsloth](https://github.com/unslothai/unsloth) — Fast memory-efficient fine-tuning. 2x faster, 50% less memory. Supports QLoRA, LoRA, full fine-tune.
- [Axolotl](https://github.com/axolotl-ai-cloud/axolotl) — Streamlined fine-tuning framework supporting multiple model architectures and quantization methods.
- [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) — Easy-to-use fine-tuning with web UI. Supports 100+ models, multiple training methods.
- [Hugging Face TRL](https://github.com/huggingface/trl) — Transformer Reinforcement Learning library. SFT, PPO, DPOTrainer, GRPOTrainer for aligning models.
- [XTuner (InternLM)](https://github.com/InternLM/xtuner) — Efficient fine-tuning toolkit supporting QLoRA, LoRA, and full fine-tune with multiple model architectures.
- [Ludwig (Predibase)](https://ludwig.ai/) — Declarative ML framework. Fine-tune models with a simple config file. [GitHub](https://github.com/ludwig-ai/ludwig)

---

## ✨ Prompt Engineering Tools

> 📅 Last checked: July 24, 2026

Free tools for testing, managing, and optimizing prompts.

- [Promptfoo](https://www.promptfoo.dev/) — **Acquired by OpenAI.** Open-source tool for prompt testing and evaluation. Systematic A/B testing of prompts. [GitHub](https://github.com/promptfoo/promptfoo)
- [Fabric (Daniel Miessler)](https://github.com/danielmiessler/fabric) — Open-source framework for augmenting humans with AI. Library of curated prompts (patterns) for common tasks.
- [LangFuse](https://langfuse.com/docs) — Open-source LLM engineering platform with prompt management, versioning, and evaluation. [GitHub](https://github.com/langfuse/langfuse)
- [DSPy (Stanford)](https://dspy.ai/) — Framework for algorithmically optimizing LM prompts and weights. [GitHub](https://github.com/stanfordnlp/dspy)
- [Agenta](https://agenta.ai/) — Open-source LLM platform for prompt management, evaluation, and deployment. [GitHub](https://github.com/Agenta-AI/agenta)

---

## 📊 Datasets

> 📅 Last checked: July 24, 2026

Free, open datasets for training, fine-tuning, and evaluating models.

- [Hugging Face Datasets](https://huggingface.co/datasets) — The standard hub for open datasets. 150,000+ datasets across all tasks.
- [Common Corpus](https://huggingface.co/datasets/PleIAs/Common-Corpus) — Massive open-source dataset for training large language models. (Requires HuggingFace login)
- [The Stack v2 (BigCode)](https://huggingface.co/datasets/bigcode/the-stack-v2) — Large-scale code dataset covering 619 programming languages. Permissive license.
- [FineWeb (Hugging Face)](https://huggingface.co/datasets/HuggingFaceFW/fineweb) — High-quality web dataset for LLM pre-training. 15T tokens.
- [Dolly (Databricks)](https://huggingface.co/datasets/databricks/databricks-dolly-15k) — 15k instruction-response pairs for fine-tuning. CC-BY-SA.
- [OpenAssistant Conversations](https://huggingface.co/datasets/OpenAssistant/oasst1) — 160k human-generated assistant conversations. Apache 2.0.
- [ShareGPT (RyokoAI)](https://huggingface.co/datasets/anon8231489123/ShareGPT_Vicuna_unfiltered) — Real user-ChatGPT conversations for fine-tuning.
- [UltraChat (Sean C.)](https://huggingface.co/datasets/HuggingFaceH4/ultrachat_200k) — 200k multi-turn conversations synthesized by ChatGPT.
- [No Robots (Hugging Face)](https://huggingface.co/datasets/HuggingFaceH4/no_robots) — 10k high-quality human-written instructions. Apache 2.0.
- [MMLU / GSM8K](https://huggingface.co/datasets) — Standard benchmarks for evaluation.

---

## ☁ Model Hosting Platforms

> 📅 Last checked: July 24, 2026

Free platforms that host models — run inference without downloading anything.

- [Hugging Face Spaces](https://huggingface.co/spaces) — Free hosting for ML apps (Gradio, Streamlit). Thousands of community demos.
- [Hugging Face Inference Endpoints (Free Tier)](https://huggingface.co/inference-endpoints) — Deploy models with free trial credits.
- [Google Colab (Free Tier)](https://colab.research.google.com/) — Free GPU (T4, sometimes A100). Perfect for running models and fine-tuning.
- [Kaggle Notebooks](https://www.kaggle.com/code) — Free GPU (T4 x2). 30 hours/week. Good for heavier workloads.
- [Lightning AI Studio](https://lightning.ai/) — Free tier with GPU access for development and prototyping.
- [Modal](https://modal.com/) — Free monthly credits for serverless GPU compute.
- [Replicate (Free Tier)](https://replicate.com/) — Free credits for running community models.
- [Deepnote](https://deepnote.com/) — Free tier with GPU for data science and ML notebooks.

---

## 📚 Learning Resources

> 📅 Last checked: July 24, 2026

Free courses, books, and tutorials for learning AI and LLMs.

- [Fast.ai](https://www.fast.ai/) — Code-first deep learning education. Practical, free courses from fundamentals to advanced.
- [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course) — Comprehensive free course on transformers, tokenizers, datasets, and deployment.
- [DeepLearning.AI Short Courses](https://www.deeplearning.ai/courses) — Free short courses on LLMs, RAG, LangChain, and AI agents.
- [Full Stack Deep Learning](https://fullstackdeeplearning.com/) — Free course on ML engineering: training, deploying, and maintaining models.
- [Andrej Karpathy's Course](https://karpathy.ai/zero-to-hero.html) — From-scratch neural network implementation videos.
- [Neural Networks: Zero to Hero](https://www.youtube.com/watch?v=VMj-3S1tku0&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) — YouTube series building neural networks from scratch.
- [Prompt Engineering Guide (DAIR.AI)](https://www.promptingguide.ai/) — Comprehensive free guide on prompt engineering techniques.
- [Anthropic Cookbook](https://github.com/anthropics/claude-cookbooks) — Free recipes and patterns for working with Claude.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) — Free examples and guides for the OpenAI API.

---

## 🏆 Resources & Leaderboards

> 📅 Last checked: July 24, 2026

- [Perplexity](https://www.perplexity.ai/) — Free AI search and research assistant with real-time answers and source citations.
- [BenchLM.ai](https://benchlm.ai/) — **New.** LLM leaderboard with 281 models compared across 8 categories. Verified benchmark data updated weekly.
- [Hugging Face Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) — The primary benchmark for open-weight models. Updated regularly.
- [LMSYS Chatbot Arena](https://arena.ai/) — Human preference rankings of models. Best source for real-world quality comparisons.
- [Artificial Analysis](https://artificialanalysis.ai/) — Independent benchmarks for speed, pricing, and quality across providers.
- [Hugging Face Models](https://huggingface.co/models) — Search 1M+ models. Filter by license, task, framework.
- [OpenRouter Models](https://openrouter.ai/models) — Browse models available via API with pricing and free tiers.
- [Ollama Library](https://ollama.com/library) — Browse models available for one-command local setup.
- [cheahjs/free-llm-api-resources](https://github.com/cheahjs/free-llm-api-resources) — Community-maintained list of free LLM API resources.

---

## 👥 Communities

> 📅 Last checked: July 24, 2026

- [Hugging Face Discord](https://discord.gg/huggingface) — Model releases, discussions, and community support.
- [r/LocalLLaMA](https://reddit.com/r/LocalLLaMA) — The largest Reddit community for running local LLMs.
- [Ollama Discord](https://discord.gg/ollama) — Ollama community for local model enthusiasts.
- [LM Studio Discord](https://discord.gg/lmstudio) — LM Studio community.
- [Hugging Face Forums](https://discuss.huggingface.co/) — Discussions on models, datasets, and Spaces.
- [r/MachineLearning](https://reddit.com/r/MachineLearning) — General ML/AI research and news.
- [Discord: AI Agents](https://discord.gg/ai-agents) — Community for AI agent development and agentic frameworks.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.
