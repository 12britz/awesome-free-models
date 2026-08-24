# Awesome Free Models [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of free AI models, APIs, and tools you can use without paying a cent.

![Last Updated](https://img.shields.io/badge/Last%20Updated-August%2022%2C%202026-brightgreen?style=for-the-badge)
![Models](https://img.shields.io/badge/Models-49-blue?style=flat-square)
![Tools](https://img.shields.io/badge/Tools-245-blue?style=flat-square)
![Sections](https://img.shields.io/badge/Sections-21-blue?style=flat-square)
![License](https://img.shields.io/badge/License-CC0-lightgrey?style=flat-square)
[![GitGem](https://gitgem.org/api/badge/github/12britz/awesome-free-models.svg)](https://gitgem.org/github/12britz/awesome-free-models)

> ✅ All links re-verified on August 22, 2026 (328 URLs). This run also detected a number of unreachable/blocked endpoints (e.g., Poe/Perplexity may return HTTP 403; some Hugging Face pages return HTTP 401).

Running AI shouldn't require a credit card. This list curates genuinely free models — open-weight models you can self-host, free API tiers from major providers, and tools to run everything locally.

---

## Contents

- [🧠 Open-Weight Models](#-open-weight-models) — Downloadable model weights you can run on your own hardware
- [🔌 Free API Providers](#-free-api-providers) — Cloud APIs with generous free tiers for model inference
- [🖼️ Image & Video Generation](#-image--video-generation) — Open-weight and API-based visual generation models
- [🔀 Free API Routers](#-free-api-routers) — Unified gateways routing requests across multiple providers
- [💻 Local Inference Tools](#-local-inference-tools) — Software to run models locally with full privacy
- [💬 AI Chatbot UIs](#-ai-chatbot-uis) — Self-hosted web interfaces for chatting with models
- [🎵 Audio & Speech Models](#-audio--speech-models) — Open-weight TTS, STT, and voice generation models
- [🤖 AI Coding Assistants](#-ai-coding-assistants) — IDE extensions and CLI tools for AI-assisted development
- [📝 Code Models](#-code-models) — Models specialized for code generation and analysis
- [🧬 Embedding Models](#-embedding-models) — Models for semantic search, RAG, and text representation
- [🔍 RAG & Vector Databases](#-rag--vector-databases) — Vector storage and retrieval for augmented generation
- [🧩 Agentic Frameworks](#-agentic-frameworks) — Frameworks for building autonomous AI agents and multi-agent systems
- [🔧 MCP Servers & Tools](#-mcp-servers--tools) — Model Context Protocol servers connecting AI to external tools
- [🎛 Fine-tuning Tools](#-fine-tuning-tools) — Tools for adapting models to your specific data
- [✨ Prompt Engineering Tools](#-prompt-engineering-tools) — Tools for testing, managing, and optimizing prompts
- [📊 LLM Evaluation & Observability](#-llm-evaluation--observability) — Tracing, evaluation, and monitoring for LLM apps
- [📊 Datasets](#-datasets) — Open datasets for training, fine-tuning, and evaluation
- [☁ Model Hosting Platforms](#-model-hosting-platforms) — Free cloud platforms for hosting and running models
- [📚 Learning Resources](#-learning-resources) — Free courses, tutorials, and guides for AI engineering
- [🏆 Resources & Leaderboards](#-resources--leaderboards) — Benchmarks, leaderboards, and model discovery tools
- [👥 Communities](#-communities) — Discord servers, subreddits, and forums for discussion

---

## 🧠 Open-Weight Models

> 📅 Last checked: August 19, 2026

Notable open-weight models you can download and run on your own hardware.

- [Muse Glimmer (Meta Superintelligence Lab)](https://huggingface.co/meta-models/Muse-Glimmer-30B) — **Aug 2026.** 30B dense multimodal model distilled from Muse Spark for local agentic workflows. Multi-step reasoning, tool use, vision, and failure recovery on consumer hardware (4-bit quant fits 24GB VRAM). 131K context. Apache 2.0.
- [Llama 4 Scout / Maverick](https://huggingface.co/meta-llama) — Meta's latest MoE generation. Scout: 109B, 10M context. Maverick: 402B, 1M context. Native multimodal. [[License]](https://github.com/meta-llama/llama-models/blob/main/README.md#llama-models-1)
- [DeepSeek V4 Pro](https://huggingface.co/deepseek-ai) — **Apr 2026.** 1.6T MoE (49B active). SWE-bench Verified 80.6% (top open-weight). 1M context. MIT license.
- [DeepSeek V4](https://huggingface.co/deepseek-ai) — Core generation with extreme cost-efficiency. 1M context. MIT license.
- [DeepSeek-V4-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash) — **Apr 2026.** Efficiency-focused variant. 284B total (13B active). 1M context. MIT license.
- [Gemma 4 31B / 26B MoE / E4B / E2B](https://huggingface.co/google) — Fully permissive Apache 2.0. 256K context, native multimodal. New standard for open-weight.
- [Inkling (Thinking Machines Lab)](https://huggingface.co/thinkingmachines/Inkling) — **Jul 2026.** 975B MoE (41B active). Leading US open-weight model. Native multimodal (text, image, audio). Apache 2.0. 1M context.
- [GLM-5.2 (Zhipu AI)](https://huggingface.co/zai-org) — 744B MoE model optimized for autonomous coding and engineering tasks. 1M-token context. MIT license.
- [LongCat-2.0 (ByteDance)](https://huggingface.co/bytedance) — Large-scale open-weight model for heavy agentic coding. MIT license.
- [MiniMax M3](https://huggingface.co/MiniMaxAI) — Frontier-tier 1M context, native multimodal + computer use. MSA architecture.
- [Trinity (Arcee AI)](https://huggingface.co/arcee-ai) — 400B parameter enterprise model. Apache 2.0.
- [Step 3.7 Flash (StepFun)](https://huggingface.co/stepfun-ai) — **May 2026.** Apache 2.0. Native multimodal (image+video), strong agentic performance. Efficient enough for high-end local hardware.
- [Kimi K3 (Moonshot AI)](https://huggingface.co/moonshotai) — **Jul 2026.** 2.8T-parameter MoE (896 experts, ~50B active). World's largest open-weight model. 1M context, native vision + video. #1 Frontend Code Arena. Modified MIT license. Weights released Jul 27.
- [Kimi K2.6 (Moonshot AI)](https://huggingface.co/moonshotai) — **Apr 2026.** 1T-parameter MoE model. Modified MIT license. Exceptional coding (SWE-Bench ~54%) and multi-agent swarm orchestration.
- [Qwen 3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B) — **Apr 2026.** MoE variant with only 3B active parameters. Extremely efficient for consumer hardware. Apache 2.0.
- [InternLM 3 (Shanghai AI Lab)](https://huggingface.co/internlm) — **Early 2026.** Strong long-context reasoning and agentic performance. Competitive in open-weight benchmarks.
- [MiMo-V2.5-Pro (Xiaomi)](https://huggingface.co/XiaomiMiMo/MiMo-V2.5-Pro) — **Apr 2026.** 1.02T-parameter MoE (42B active). Optimized for complex agentic tasks, coding, and long-context.
- [Kimi K2.7 Code (Moonshot AI)](https://huggingface.co/moonshotai) — **Jun 2026.** 1T MoE specialized for long-running coding agents. +21.8% over K2.6 on coding benchmarks. Modified MIT.
- [Nemotron 3 Super (NVIDIA)](https://huggingface.co/nvidia) — **May 2026.** 120B total (12B active). 1M context. Published weights, data, recipes, and eval infra. NVIDIA Open Model License.
- [Phi-4 14B (Microsoft)](https://huggingface.co/microsoft/phi-4) — **2025.** Compact 14B dense model. Strong reasoning and code. MIT license. Excellent for on-device and small deployments.
- [Bonsai 8B (PrismML)](https://huggingface.co/prism-ml/Bonsai-8B-gguf) — **Apr 2026.** Groundbreaking 1-bit quantized model. Extremely efficient for edge and consumer hardware (Apple Silicon).
- [Aether-7B-5Attn (VIDRAFT)](https://huggingface.co/FINAL-Bench/Aether-7B-5Attn) — **Jul 2026.** 100% open foundation model (weights, data, code, logs). 7B MoE (~3B active) with heterogeneous attention. Apache 2.0.
- [Mistral Large 3 (Mistral)](https://huggingface.co/mistralai) — **Jun 2026.** 675B MoE (41B active). European multilingual flagship. Frontier-class reasoning, native multimodal. Apache 2.0.
- [Mistral Small 3.1 (Mistral)](https://huggingface.co/mistralai/Mistral-Small-3.1-24B-Instruct-2503) — **Mar 2025.** Versatile 24B multimodal model. Strong text performance with native image understanding and 128K context. Apache 2.0.
- [Mistral Small 4 (Mistral)](https://huggingface.co/mistralai/Mistral-Small-4-119B-2603) — **Mar 2026.** Hybrid MoE (6.5B active params) unifying instruction, reasoning, and multimodal capabilities. Efficient frontier-class model. Apache 2.0.
- [Command A+ (Cohere)](https://huggingface.co/CohereLabs/command-a-plus-05-2026-w4a4) — **May 2026.** Enterprise multimodal MoE optimized for sovereignty and multilingual RAG across 48 languages. Apache 2.0.
- [Apertus 1.5 (ETH Zurich / EPFL)](https://huggingface.co/collections/apertus-ai) — **Jul 2026.** Fully open LLM (weights, data, training code). 8B and 70B with image understanding, thinking mode, and tool use. Apache 2.0.
- [Hy3 (Tencent)](https://huggingface.co/tencent/Hy3) — **Jul 2026.** 295B MoE (21B active). Strong reasoning and agentic performance. Competes with models 2-5x its size. Apache 2.0.
- [Hermes 4 (NousResearch)](https://huggingface.co/NousResearch/Hermes-4-70B) — **Feb 2026.** Self-improving agentic model with closed-loop learning. Curates own memory and builds skills from experience. Apache 2.0.
- [Snowflake Arctic](https://huggingface.co/Snowflake/snowflake-arctic-instruct) — **Apr 2024.** Enterprise MoE model balancing high-quality performance with efficient training costs. Optimized for complex data operations. Apache 2.0.
- [Falcon 3 (TII)](https://huggingface.co/tiiuae/Falcon3-7B-Instruct) — **Dec 2024.** Compact high-performance model with strong reasoning. Designed for efficient deployment on resource-constrained hardware. TII Falcon-LLM License 2.0.
- [Apple OpenELM](https://huggingface.co/Apple/OpenELM-3B) — **Apr 2024.** Family of efficient on-device SLMs using layer-wise attention scaling. Runs locally on Apple Silicon with full privacy. Apple Sample Code License.

---

## 🔌 Free API Providers

> 📅 Last checked: August 19, 2026

Providers offering free tiers to access models via API — no local hardware required.

- [Google AI Studio](https://aistudio.google.com/) — **15 free models** — **Most generous free tier.** Access Gemini 2.5 Flash, Gemini 2.0 Flash, and other models. Generous rate limits for prototyping.
- [OpenRouter](https://openrouter.ai/) — **16 free models** — Aggregates 400+ models. Filter by "Free" to see models available at no cost. **Note: free models now require a positive credit balance (balance may be $0).** Includes experimental and subsidized open-weight models.
- [AnyAPI](https://anyapi.ai/) — **15 free models** — 400+ models with OpenAI-compatible API. Free tier: 100K tokens/day, unlimited users. Includes free and basic models. No credit card required.
- [Groq](https://console.groq.com/) — **12 free models** — Ultra-fast inference. Free tier includes Llama, Gemma, Mixtral, Whisper models with generous daily rate limits.
- [Hugging Face Inference Providers](https://huggingface.co/inference-api) — **5 free models** — Free tier for thousands of community models. Rate-limited but excellent for testing.
- [NVIDIA NIM](https://build.nvidia.com/) — **100+ free models** — Free, rate-limited API access to accelerated versions of Llama, Mistral, Gemma, and more on NVIDIA infrastructure.
- [DeepInfra](https://deepinfra.com/) — **⚠️ No permanent free-model tier; free tier is now a recurring monthly credit (site advertises ~$10/month; reports cite ~$5 signup + $5/mo recurring).** Serverless inference for popular open-source models.
- [Together AI](https://www.together.ai/) — **⚠️ No permanent free tier; requires ~$5 minimum credit purchase.** Fast inference on many open-source models.
- [Fireworks AI](https://fireworks.ai/) — **⚠️ No free models; ~$1 signup credit only.** Optimized for low latency on open-source models.
- [SiliconFlow](https://siliconflow.cn/) — **3 free models** — Rising platform with free access to many open-source models.
- [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/) — **50+ free models** — Free tier for running select open-source models at the edge.
- [Black Forest Labs](https://api.bfl.ai/) — **2 free models** — Free Flux 2 Dev and Flux Kontext Dev image generation via API. Rate-limited, no credit card required.
- [Replicate](https://replicate.com/) — Limited free runs on select "Try for Free" models, no credit card required; then prepaid pay-as-you-go.
- [Poe (Quora)](https://poe.com/) — **⚠️ Free tier changed over time; link check returned HTTP 403 (may block automation).** Previously reported reduction (~300 compute points/day); verify in your browser before relying on exact numbers.
- [Qwen Studio (Alibaba)](https://chat.qwen.ai/) — Free access to Qwen 3.6-Plus, Qwen 3.6-Max, and other Qwen models via web chat and API. 1M token context for agentic coding.
- [Ollama Cloud](https://ollama.com/cloud) — **(keyword-detected best-effort; exact limits require manual confirmation).** Free tier for running open-source models on Ollama's cloud infrastructure with session/weekly limits and 1 concurrent model. Same `ollama run` command as local.
- [Mistral AI (La Plateforme)](https://mistral.ai/) — **12 free models** — Free API tier with access to Mistral Large, Mistral Nemo, Codestral and more. 1 req/s, 500k tokens/min. Requires phone verification and data usage opt-in.
- [Cohere](https://cohere.com/) — **15 free models** — Free evaluation API key for Command R, Command R+, Embed, and Rerank models. 20 req/min, 1,000 req/month.
- [DeepSeek Platform](https://deepseek.com/) — Free API credits for new users (5M tokens). Access to DeepSeek V4, DeepSeek-R1, and other models. Generous free allocation.
- [Hyperbolic](https://www.hyperbolic.ai/) — Open-access AI cloud with affordable inference. Free trial credits for new accounts. Supports Llama, Qwen, DeepSeek, and other open models.
- [Novita AI](https://novita.ai/) — Free credits for testing 100+ models including Llama, Qwen, DeepSeek, and Mistral. OpenAI-compatible API with competitive pricing beyond the free tier.
- [Anakin.ai](https://anakin.ai/) — **30 daily free credits** for accessing multiple AI models. Web chat interface and API access. Supports GPT-4, Claude, and open-weight models.
- [Nebius AI](https://nebius.com/) — **Note: Free trial suspended July 13, 2026.** Now steers new users to a ~$1 trial credit via Nebius Token Factory (formerly AI Studio), with a $25 minimum deposit for paid usage. Fast inference on NVIDIA H100 infrastructure.
- [Fal.ai](https://fal.ai/) — Free starter credits for AI inference. Fast, serverless platform supporting Llama, Flux, and Stable Diffusion models. Pay-as-you-go beyond free tier.
- [Vercel AI Gateway](https://vercel.com/ai) — **$5/month free credits** for the AI Gateway. Proxy and cache requests across multiple LLM providers. SDK is open-source and free.
- [AI21 Labs](https://www.ai21.com/) — **$10 trial credits** for accessing Jamba 1.5, Jamba 1.6, and other AI21 models. Valid for 3 months. Requires account sign-up.
- [Amazon Bedrock](https://aws.amazon.com/bedrock/) — **$200 AWS credits** for new customers. Access to Llama, Mistral, Claude, Titan, and other foundation models via API.
- [Microsoft Foundry (Azure)](https://azure.microsoft.com/en-us/products/ai-foundry/) — **$200 free trial credits** (30 days). Access GPT-4o, Llama, Mistral, Phi, and other models via Azure's unified AI platform.
- [RunPod](https://www.runpod.io/) — Free credits for serverless GPU inference. Deploy open-weight models as serverless endpoints. Supports Llama, Qwen, DeepSeek, and more.
- [Cerebras](https://cerebras.ai/) — **⚠️ Old "free tier" replaced (Jul 2026).** Now **$5 free trial credits** that expire in 30 days after adding a verified payment method; **no longer a permanent free tier**. Ultra-fast inference on Llama, Gemma, and gpt-oss models. **Note: Model availability fluctuates.**
- [BazaarLink](https://bazaarlink.ai/) — Free OpenAI-compatible API with `auto:free` routing to zero-cost models. No credit card, no trial expiry. 10 RPM, 130 req/day.
- [Kimi API (Moonshot)](https://platform.kimi.com/) — Free tier for new accounts with access to Kimi K2.5 (128K context). Also free via NVIDIA NIM. OpenAI-compatible. **Note: rebranded from platform.moonshot.cn.**
- [Alibaba DashScope](https://dashscope.aliyun.com/) — **5 free models** — Free tier for Qwen models. 1M tokens/month. OpenAI-compatible API.
- [SambaNova Cloud](https://cloud.sambanova.ai/) — **4 free models** — Free tier with $5 credits (30-day). Fast RDU inference for Llama 3.1 405B, Llama 3.3 70B, DeepSeek V3.1/V3.2, Qwen 2.5, gpt-oss-120b. 20 RPM, 200K tokens/day. No credit card required.
- [OVHcloud AI Endpoints](https://www.ovhcloud.com/en/public-cloud/ai-endpoints/) — **14 free models** — EU-hosted, GDPR-compliant free tier. No registration required for anonymous tier. Models: Qwen, Mistral, Llama, DeepSeek, gpt-oss-120B, embeddings, image generation. 12 RPM. OpenAI-compatible.
- [Chutes.ai](https://chutes.ai/) — **⚠️ Free tier ended — now paid only.** Was 2 free models for community-powered GPU inference. No longer free.
- [ModelScope](https://modelscope.cn/) — **55 free models** — Chinese platform with 50+ free open models. Qwen, DeepSeek, GLM, and more. No credit card required.
- [Z.ai (Zhipu AI)](https://open.bigmodel.cn/) — **4 free models** — Free tier for GLM models including GLM-4.5, GLM-4V. No credit card required.
- [LongCat AI](https://longcat.chat/) — Free API for LongCat open-weight models. One-time 10M token grant after signup + KYC. Free cached tokens. OpenAI-compatible. MIT license.
- [Coze (ByteDance)](https://www.coze.com/) — Free bot-building platform with API access to GPT-4o, Gemini 1.5 Pro, and other models. No credit card required. OpenAI-compatible.
- [Free.ai](https://free.ai/developer/) — 400+ AI tools via a single OpenAI-compatible API. Free tier: (keyword-detected best-effort; exact quota requires manual confirmation). Chat, image, video, music, voice, OCR, translation.
- [Requesty](https://www.requesty.ai/free-models) — Free AI API with 200 requests/day. Works with Claude Code, Cline, Cursor. No credit card. OpenAI-compatible.
- [AINative Studio](https://ainative.studio/free-llm-api) — **⚠️ Free tier ended (was 10M tokens/month).** Now a $5/mo Hobbyist plan with a 3-day trial only. 84+ models (Llama, DeepSeek, Mistral, Qwen).
- [CloudCode.ONE](https://cloudcode.one/) — **⚠️ No free tier — credit-based ($2 to start).** OpenAI and Anthropic-compatible API for coding agents. Powered by GLM-4.7-Flash.
- [ZeroLimitAI](https://www.zerolimitai.com/developers) — Free OpenAI-compatible API with `model: "auto"` routing to the best free model. No credit card, no trial expiry. Lifetime free tier available.
- [Chat Oripe](https://api.oriper.com/) — **⚠️ Currently unreachable (HTTP 530) at check time.** Previously offered free tokens via OpenAI-compatible API; verify availability before relying on it.
- [FreeTheAi](https://github.com/Free-The-Ai/free-ai) — **(link check failed: 404).** Open-source Discord signup/free API was previously listed here; please verify the current repository URL before relying on it.
- [OpenCode Zen](https://opencode.ai/zen) — **9 free models** — Curated AI gateway with free general and coding models (DeepSeek V4 Flash Free, MiMo-V2.5 Free, Nemotron 3 Ultra Free, Big Pickle, Qwen 3.6 Plus Free, MiniMax M3 Free, North Mini Code Free, and more). OpenAI-compatible API. No credit card required.
- [LLM7.io](https://llm7.io/) — **15 free models**, no credit card required. DeepSeek R1/V3, GPT-4o mini and more. 1M context, multimodal. 30 RPM free (120 RPM with optional token).
- [Kilo Code](https://kilo.ai/) — **12 free models**, no credit card. Nemotron 3 Ultra, Step 3.7 Flash, and more. 1M context, ~200 req/hr. Free tier for coding agents.
- [Aion Labs](https://www.aionlabs.ai) — **7 free models**, registration only. Includes Aion 2.5. 128K context, 15 RPM. No credit card required.
- [Agnes AI](https://platform.agnes-ai.com/) — **5 free models** — Free tier with Agnes 1.5/2.0 Flash and image models. 256K context, 30 RPM. Registration only, no credit card.
- [Glhf.chat](https://glhf.chat/) — **⚠️ Currently unreachable (HTTP 522) at check time.** Previously offered a free OpenAI-compatible API; verify availability before relying on it.
- [Nscale](https://console.nscale.com/) — **2 free models** — Free tier (registration only) with Llama 3.3 70B and DeepSeek-R1-Distill-70B. 128K context. OpenAI-compatible.
- [OrcaRouter](https://www.orcarouter.ai/offers) — **4 free models** — DeepSeek V4 Pro, DeepSeek V4 Flash, Qwen3.8 27B, and Tencent Hy3 at $0 per token, plus an `orcarouter/free` alias that auto-routes across the free lineup. OpenAI-, Anthropic-, and Gemini-compatible endpoints. No credit card and no trial expiry; rotating voucher, student, and hackathon credit offers are listed on the same page.

---

## 🖼️ Image & Video Generation

> 📅 Last checked: August 19, 2026

Free, open-weight image and video generation models — run locally or via free APIs.

- [FLUX.2-dev (Black Forest Labs)](https://github.com/black-forest-labs/flux2) — **2.6K★.** 32B rectified flow transformer. SOTA open T2I, single/multi-reference editing, in/out-painting. Updated VAE. FLUX.1-dev Non-Commercial License.
- [ERNIE-Image / ERNIE-Image-Turbo (Baidu)](https://github.com/baidu/ernie-image) — **0.5K★.** 8B DiT SOTA among open-weight models. Strong text rendering, layout control. Turbo: 8-step generation. Apache 2.0.
- [Z-Image (Tongyi Lab / Alibaba)](https://github.com/Tongyi-MAI/Z-Image) — **11.8K★.** Open-weight T2I with strong GenEval scores. Z-Image-Turbo for 4-step generation. Apache 2.0.
- [Pollinations.ai](https://pollinations.ai/) — **Free image generation API.** No API key or signup needed. Text-to-image, image-to-image. OpenAI-compatible. Integrates with ComfyUI.
- [OpenImageGen (Hugging Face)](https://huggingface.co/spaces/OpenImageGen/OpenImageGen) — Free, open-source image generation playground. Supports multiple community models via diffusers. Apache 2.0. **Note: login/auth may be required (HTTP 401 at check time).**
- [ComfyUI](https://github.com/Comfy-Org/ComfyUI) — **128K★.** Node-based image and video generation UI. Run FLUX, Stable Diffusion, and more locally. GPL-3.0.

---

## 🔀 Free API Routers

> 📅 Last checked: August 19, 2026

Open-source tools that route requests across multiple AI providers — unified API, automatic failover, and cost optimization.

- [9Router](https://9router.com/) — Open-source gateway connecting 40+ providers with RTK token compression (2-4x reduction). One API key for all services. MIT license. [GitHub](https://github.com/decolua/9router)
- [OmniRoute](https://omniroute.online/) — Full-stack AI gateway with 250+ providers, 90+ free. TypeScript, runs on Web/Desktop/Android. Prompt compression, 3-level proxy for geo restrictions. [GitHub](https://github.com/diegosouzapw/OmniRoute)
- [LiteLLM](https://litellm.ai/) — Python-based proxy unifying 100+ LLMs behind a single API. Spend tracking, virtual keys, production-ready. MIT license. [GitHub](https://github.com/BerriAI/litellm)
- [Portkey AI Gateway](https://portkey.ai/) — Production guardrails and routing for AI apps. Hybrid open-source (community) and managed (enterprise) tiers. [GitHub](https://github.com/Portkey-AI/gateway)

---

## 💻 Local Inference Tools

> 📅 Last checked: August 19, 2026

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
- [Hugging Face TGI](https://github.com/huggingface/text-generation-inference) — **10.9K★.** Production-grade serving toolkit for large language models. **Note: Archived by Hugging Face (Mar 2026).** Consider vLLM, SGLang, or TGI forks for active development.
- [DeepSpeed (Microsoft)](https://github.com/deepspeedai/DeepSpeed) — Deep learning optimization library with inference acceleration. Enables running larger models on limited hardware through ZeRO optimization.
- [AirLLM](https://github.com/lyogavin/airllm) — Run large models (70B+) on consumer hardware with limited memory. Loads models layer-by-layer for extreme memory efficiency. **Actively maintained (last push Jul 2026).**
- [Microsoft Foundry Toolkit for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-windows-ai-studio.windows-ai-studio) — VS Code extension to browse, test, fine-tune, and deploy models locally. Integrates ONNX and llama.cpp. **(link check returned HTTP 404 at check time — repo/marketplace URL may have changed).**
- [Ollama Grid Search](https://github.com/dezoito/ollama-grid-search) — Desktop utility for systematic model evaluation. Test multiple models, prompts, and inference parameters side-by-side via a Rust/React GUI.
- [oMLX](https://github.com/jundot/omlx) — **19.7K★.** LLM inference server for Apple Silicon with continuous batching, tiered KV caching (hot RAM + cold SSD), and macOS menu bar app. OpenAI and Anthropic compatible. Apache 2.0.
- [MTPLX](https://github.com/youssofal/MTPLX) — **1.4K★.** Native MTP speculative decoding on Apple Silicon — ~2x faster decode with no external drafter. Mac app + CLI, OpenAI/Anthropic compatible server. Auto-tunes draft depth per machine. Apache 2.0.

---

## 💬 AI Chatbot UIs

> 📅 Last checked: August 19, 2026

Free, open-source web interfaces for chatting with AI models — self-host or use hosted versions.

- [Open WebUI](https://openwebui.com/) — Feature-rich ChatGPT-like interface for Ollama and OpenAI-compatible backends. RAG, image generation, multi-user. [GitHub](https://github.com/open-webui/open-webui)
- [LibreChat](https://www.librechat.ai/) — Open-source ChatGPT clone supporting 40+ providers, multi-user, plugins, and RAG. **Note: Company acquired by ClickHouse; repo actively maintained (last push Aug 2026).** [GitHub](https://github.com/danny-avila/LibreChat)
- [AnythingLLM](https://anythingllm.com/) — All-in-one desktop app for chatting with documents and models. Built-in RAG pipeline. [GitHub](https://github.com/Mintplex-Labs/anything-llm)
- [Big-AGI](https://big-agi.com/) — Feature-rich AI chat with personas, multi-model support, voice, and code execution. [GitHub](https://github.com/enricoros/big-agi)
- [Lobe Chat](https://lobehub.com/) — Multi-agent orchestration platform with plugin system and multi-provider support. [GitHub](https://github.com/lobehub/lobehub)

---

## 🎵 Audio & Speech Models

> 📅 Last checked: August 19, 2026

Free, open-weight text-to-speech (TTS), speech-to-text (STT), and voice generation models you can run locally.

- [Qwen3-TTS (Alibaba)](https://github.com/QwenLM/Qwen3-TTS) — **13K★.** Voice cloning, voice design, 10 languages. Streaming support with 97ms TTFB. 0.6B/1.7B. Apache 2.0.
- [Chatterbox (Resemble AI)](https://github.com/resemble-ai/chatterbox) — **26.1K★.** SOTA open-source TTS. Multilingual V3 (23+ languages, 0.5B). Turbo: 350M for low-latency agents. Paralinguistic tags. MIT.
- [MOSS-TTS Family (MOSI.AI/OpenMOSS)](https://github.com/OpenMOSS/MOSS-TTS) — **4K★.** 8B flagship + 100M Nano (CPU). Voice cloning, dialogue generation, sound effects, realtime streaming. Apache 2.0.
- [Orpheus-TTS (Canopy Labs)](https://github.com/canopyai/Orpheus-TTS) — **6.3K★.** Llama-3b backbone, human-like speech, zero-shot voice cloning, emotion tags. ~200ms streaming latency. Apache 2.0.
- [NeuTTS (Neuphonic)](https://github.com/neuphonic/neutts) — **6.2K★.** On-device TTS with instant voice cloning. GGUF quantized for CPU/mobile. 120M Nano and 360M Air variants. Apache 2.0.
- [Faster-Whisper](https://github.com/SYSTRAN/faster-whisper) — **25K★.** CTranslate2-based Whisper for 4x faster transcription. MIT.

---

## 🤖 AI Coding Assistants

> 📅 Last checked: August 19, 2026

Free tools that integrate AI into your development workflow.

- [Continue.dev](https://www.continue.dev/) — **Company acquired by Cursor; repo actively maintained (last push Aug 2026).** Open-source AI code assistant for VS Code and JetBrains. [GitHub](https://github.com/continuedev/continue)
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
- [OpenHands](https://www.openhands.dev/) — Autonomous AI software engineer. Navigates file systems, runs shell commands, tests code in browser. Self-hostable. [GitHub](https://github.com/OpenHands/OpenHands)
- [Goose](https://goose-docs.ai/) — Open-source CLI agent for complex software engineering tasks. Extensible plugin system. Built by Block/Square. [GitHub](https://github.com/aaif-goose/goose)
- [Qwen Code](https://github.com/QwenLM/qwen-code) — **2025.** Open-source terminal AI coding agent with 27K+ stars. Multi-protocol (OpenAI, Anthropic, Gemini, Qwen). Auto-memory, sub-agents, agent teams, MCP. Apache 2.0.
- [CodeWhale](https://github.com/Hmbown/CodeWhale) — **2026.** Terminal coding agent with 40K+ stars. 30+ providers, local models via Ollama/vLLM. TUI, headless mode, web UI. MIT license.
- [nanobot (HKUDS)](https://github.com/HKUDS/nanobot) — **2026.** Open-source, ultra-lightweight personal AI agent with WebUI, chat channels, MCP, memory, and scheduling. 47K★. MIT.
- [MiMoCode (Xiaomi)](https://github.com/XiaomiMiMo/MiMo-Code) — **Jun 2026.** Terminal-native coding agent with persistent memory, subagent orchestration, and goal-driven autonomous loops. 12.8K★. MIT.

---

## 📝 Code Models

> 📅 Last checked: August 19, 2026

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

## 🧬 Embedding Models

> 📅 Last checked: August 19, 2026

Free, open-weight embedding and reranker models for semantic search, RAG, and text representation.

- [Qwen3-Embedding (Alibaba)](https://github.com/QwenLM/Qwen3-Embedding) — **2K★.** #1 on MTEB multilingual leaderboard. Sizes: 0.6B/4B/8B. 32K context, MRL support, instruction-aware. Includes reranker models. Apache 2.0.
- [BGE-M3 (BAAI)](https://github.com/FlagOpen/FlagEmbedding/tree/master/research/BGE_M3) — Multi-lingual (100+ languages), multi-functionality (dense, sparse, colbert), multi-granularity (8K tokens). MIT.
- [FlagEmbedding (BAAI)](https://github.com/FlagOpen/FlagEmbedding) — **12K★.** Framework and model zoo: BGE series, BGE-VL (multimodal), bge-en-icl, bge-multilingual-gemma2 (9B multilingual SOTA). MIT.
- [nomic-embed-text-v2 (Nomic AI)](https://huggingface.co/nomic-ai/nomic-embed-text-v2-moe) — **1.5B** MoE embedding model. 8192 context. Matches or exceeds OpenAI text-embedding-3-small. Apache 2.0.
- [mxbai-embed-large-v1](https://huggingface.co/mixedbread-ai/mxbai-embed-large-v1) — **0.3B** lightweight embedding. Top of MTEB among sub-0.5B models. Apache 2.0.

---

## 🔍 RAG & Vector Databases

> 📅 Last checked: August 19, 2026

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
- [GraphRAG (Microsoft)](https://github.com/microsoft/graphrag) — Modular graph-based RAG pipeline. Extracts a knowledge graph from unstructured text via LLM prompting, then answers over it with community-summarization for better global/abstractive queries than vector-only RAG. MIT license. [GitHub](https://github.com/microsoft/graphrag)

---

## 🧩 Agentic Frameworks

> 📅 Last checked: August 19, 2026

Free, open-source frameworks for building AI agents and multi-agent systems.

- [LangGraph (LangChain)](https://langchain-ai.github.io/langgraph/) — Low-level framework for building stateful, multi-agent applications. [GitHub](https://github.com/langchain-ai/langgraph)
- [CrewAI](https://crewai.com/) — Multi-agent framework for orchestrating specialized AI agents to work together. [GitHub](https://github.com/crewAIInc/crewAI)
- [AutoGen (Microsoft)](https://microsoft.github.io/autogen/stable/) — Extensible framework for building multi-agent conversations. **Note: In maintenance mode (last push Apr 2026).** [GitHub](https://github.com/microsoft/autogen)
- [Agno (formerly Phidata)](https://www.agno.com/) — Full-stack AI framework for building multimodal agents with memory, knowledge, and tools. [GitHub](https://github.com/agno-agi/agno)
- [PydanticAI](https://pydantic.dev/docs/ai/overview/) — Agent framework by Pydantic with type-safe outputs and dependency injection. [GitHub](https://github.com/pydantic/pydantic-ai)
- [Mastra](https://mastra.ai/) — TypeScript framework for building AI applications and agent workflows. [GitHub](https://github.com/mastra-ai/mastra)
- [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/) — Lightweight SDK for building single and multi-agent systems. [GitHub](https://github.com/openai/openai-agents-python)
- [Semantic Kernel (Microsoft)](https://learn.microsoft.com/en-us/semantic-kernel/) — SDK for orchestrating AI agents with planners, memory, and connectors. [GitHub](https://github.com/microsoft/semantic-kernel)
- [Dify](https://dify.ai/) — LLM app development platform with visual workflow builder and agent capabilities. [GitHub](https://github.com/langgenius/dify)
- [Flowise](https://flowiseai.com/) — Low-code visual LLM flow builder with drag-and-drop interface. **Note: Acquired by Workday; repo archived (read-only) Aug 13, 2026.** [GitHub](https://github.com/FlowiseAI/Flowise)
- [Fazm](https://github.com/mediar-ai/fazm) — **Apr 2026.** Open-source local computer-use agent for macOS. Drives apps via accessibility APIs, model-agnostic, faster than screenshot-based agents.
- [Smolagents (Hugging Face)](https://github.com/huggingface/smolagents) — Minimalist agent library where agents "think in code." Lightweight, zero boilerplate. Supports code agents and tool-calling agents.
- [Swarms](https://github.com/kyegomez/swarms) — Enterprise-grade multi-agent orchestration framework. Scalable infrastructure for autonomous agent swarms. Highly modular. **Actively maintained (last push Aug 2026).**
- [Letta (MemGPT)](https://github.com/letta-ai/letta) — Framework for long-term agent memory. Virtual memory management that pages data in/out of context like an OS. Persistent agents.
- [Griptape](https://github.com/griptape-ai/griptape) — Enterprise agent framework with strictly typed Pipelines, Workflows, and Agents. Structure-first, production-ready.
- [Atomic Agents](https://github.com/Eigenwise/atomic-agents) — Framework inspired by Atomic Design. Compose agents from small, reusable, modular components. Testable and scalable.
- [PraisonAI](https://github.com/MervinPraison/PraisonAI) — Low-code multi-agent framework. Define agent roles, tasks, and flows via YAML configuration. Wraps underlying agent frameworks.
- [Cognee](https://github.com/topoteretes/cognee) — GraphRAG framework for agent knowledge management. Builds interconnected knowledge graphs from unstructured data.
- [MetaGPT](https://github.com/FoundationAgents/MetaGPT) — Multi-agent framework simulating a full software team. Assigns Agent, Product Manager, Engineer roles. Implements SOPs for end-to-end code generation. **Note: Active development (last push Jan 2026).**
- [ChatDev (OpenBMB)](https://github.com/OpenBMB/ChatDev) — Virtual software company driven by multi-agent collaboration. Follows waterfall model through design, coding, testing, and documentation.
- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) — The original autonomous agent experiment. Sets its own goals, iterates on tasks, and executes without continuous human input. Web browsing and file management.
- [Bee Agent Framework (IBM)](https://github.com/i-am-bee/beeai-framework) — Production-ready framework for building reliable AI agents in Python and TypeScript. Modular, with built-in observability and IBM research optimizations.
- [Eliza (elizaOS)](https://github.com/elizaOS/eliza) — Multi-platform agent framework for creating character-driven AI agents. Handles social media interaction, complex decision-making, and autonomous behavior across platforms.
- [Qwen-Agent (Alibaba)](https://github.com/QwenLM/Qwen-Agent) — Agent framework tightly integrated with the Qwen model family. Optimized for function calling, code execution, RAG, and tool use with Qwen models.
- [AGiXT](https://github.com/Josh-XT/AGiXT) — Extensible modular AI agent automation platform. Plugin system for swapping LLMs, memory backends, and tools. Highly customizable agent workflows.
- [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) — **12.9K★.** Production-grade multi-agent framework for Python and .NET. Graph-based workflows, streaming, human-in-the-loop. MIT.
- [GenericAgent](https://github.com/lsdefine/GenericAgent) — **13.8K★.** Minimal, self-evolving autonomous agent framework. ~3K lines core, 9 atomic tools. Self-crystallizing skill tree from every task. MIT.
- [Omnigent](https://github.com/omnigent-ai/omnigent) — **9K★.** Open-source meta-harness orchestrating Claude Code, Codex, Cursor, Pi, and custom agents. Real-time collaboration from any device. Apache 2.0.

---

## 🔧 MCP Servers & Tools

> 📅 Last checked: August 19, 2026

Model Context Protocol (MCP) servers that connect AI assistants to external tools, data sources, and APIs.

- [GitHub MCP Server](https://github.com/github/github-mcp-server) — **32.4K★.** Official GitHub MCP server by GitHub. Repository management, issue/PR automation, CI/CD intelligence, code analysis. OAuth or PAT auth. MIT license.
- [GitMCP](https://github.com/idosal/git-mcp) — **8.3K★.** Free, open-source, remote MCP server for any GitHub project. Zero-setup documentation and code access for AI assistants. Apache 2.0.
- [MCP Reference Servers (Anthropic)](https://github.com/modelcontextprotocol/servers) — **89.7K★.** Official reference implementations: Filesystem, Git, Fetch, Memory, Time, Sequential Thinking. Apache 2.0 / MIT.

---

## 🎛 Fine-tuning Tools

> 📅 Last checked: August 19, 2026

Tools to fine-tune free models on your own data — all free and open-source.

- [Unsloth](https://github.com/unslothai/unsloth) — Fast memory-efficient fine-tuning. 2x faster, 50% less memory. Supports QLoRA, LoRA, full fine-tune.
- [Axolotl](https://github.com/axolotl-ai-cloud/axolotl) — Streamlined fine-tuning framework supporting multiple model architectures and quantization methods.
- [LLaMA-Factory](https://github.com/hiyouga/LlamaFactory) — Easy-to-use fine-tuning with web UI. Supports 100+ models, multiple training methods.
- [Hugging Face TRL](https://github.com/huggingface/trl) — Transformer Reinforcement Learning library. SFT, PPO, DPOTrainer, GRPOTrainer for aligning models.
- [XTuner (InternLM)](https://github.com/InternLM/xtuner) — Efficient fine-tuning toolkit supporting QLoRA, LoRA, and full fine-tune with multiple model architectures.
- [Ludwig (Predibase)](https://ludwig.ai/) — Declarative ML framework. Fine-tune models with a simple config file. [GitHub](https://github.com/ludwig-ai/ludwig)

---

## ✨ Prompt Engineering Tools

> 📅 Last checked: August 19, 2026

Free tools for testing, managing, and optimizing prompts.

- [Promptfoo](https://www.promptfoo.dev/) — **Company acquired by OpenAI; repo actively maintained (last push Aug 2026).** Open-source tool for prompt testing and evaluation. Systematic A/B testing of prompts. [GitHub](https://github.com/promptfoo/promptfoo)
- [Fabric (Daniel Miessler)](https://github.com/danielmiessler/fabric) — Open-source framework for augmenting humans with AI. Library of curated prompts (patterns) for common tasks.
- [LangFuse](https://langfuse.com/docs) — Open-source LLM engineering platform with prompt management, versioning, and evaluation. [GitHub](https://github.com/langfuse/langfuse)
- [DSPy (Stanford)](https://dspy.ai/) — Framework for algorithmically optimizing LM prompts and weights. [GitHub](https://github.com/stanfordnlp/dspy)
- [Agenta](https://agenta.ai/) — Open-source LLM platform for prompt management, evaluation, and deployment. [GitHub](https://github.com/Agenta-AI/agenta)

---

## 📊 LLM Evaluation & Observability

> 📅 Last checked: August 19, 2026

Free, open-source tools for tracing, evaluating, and monitoring LLM applications in development and production.

- [Langfuse](https://langfuse.com/) — **33.4K★.** Full LLM engineering platform: tracing, evaluations, prompt management, playground, datasets. Self-hostable. MIT (core). [GitHub](https://github.com/langfuse/langfuse)
- [Opik (Comet)](https://github.com/comet-ml/opik) — **21.5K★.** Open-source LLM observability, evaluation, and agent tracing. Datasets, experiments, LLM-as-judge, guardrails, prompt management. Apache 2.0.
- [Phoenix (Arize AI)](https://github.com/Arize-AI/phoenix) — AI observability platform with OpenTelemetry-based tracing, evals, experiments, and prompt playground. Elastic License 2.0.
- [TruLens](https://github.com/TruEra/trulens) — **3.5K★.** Agent-specific evaluations (7 purpose-built evaluators). OpenTelemetry tracing, MCP support, batch and inline evaluation. MIT.
- [OpenLLMetry (Traceloop)](https://github.com/traceloop/openllmetry) — **7.4K★.** OpenTelemetry-based LLM observability. Send traces to any OTLP-compatible backend. Apache 2.0.

---

## 📊 Datasets

> 📅 Last checked: August 19, 2026

Free, open datasets for training, fine-tuning, and evaluating models.

- [Hugging Face Datasets](https://huggingface.co/datasets) — The standard hub for open datasets. 150,000+ datasets across all tasks.
- [Common Corpus](https://huggingface.co/datasets/PleIAs/Common-Corpus) — Massive open-source dataset for training large language models. **(May require Hugging Face login; HTTP 401 at check time).**
- [The Stack v2 (BigCode)](https://huggingface.co/datasets/bigcode/the-stack-v2) — Large-scale code dataset covering 619 programming languages. Permissive license.
- [FineWeb (Hugging Face)](https://huggingface.co/datasets/HuggingFaceFW/fineweb) — High-quality web dataset for LLM pre-training. 15T tokens.
- [Dolly (Databricks)](https://huggingface.co/datasets/databricks/databricks-dolly-15k) — 15k instruction-response pairs for fine-tuning. CC-BY-SA.
- [OpenAssistant Conversations](https://huggingface.co/datasets/OpenAssistant/oasst1) — 160k human-generated assistant conversations. Apache 2.0.
- [ShareGPT (RyokoAI)](https://huggingface.co/datasets/anon8231489123/ShareGPT_Vicuna_unfiltered) — Real user-ChatGPT conversations for fine-tuning.
- [UltraChat (Sean C.)](https://huggingface.co/datasets/HuggingFaceH4/ultrachat_200k) — 200k multi-turn conversations synthesized by ChatGPT.
- [No Robots (Hugging Face)](https://huggingface.co/datasets/HuggingFaceH4/no_robots) — 10k high-quality human-written instructions. Apache 2.0.
- [MMLU / GSM8K](https://huggingface.co/datasets) — Standard benchmarks for evaluation.
- [CodeAlchemy (IBM)](https://research.ibm.com/blog/code-alchemy-for-synthetic-code) — **Jul 2026.** ~1T tokens of synthetic code across 15 languages. Includes 1.3M code+execution-trace pairs. Permissive license.

---

## ☁ Model Hosting Platforms

> 📅 Last checked: August 19, 2026

Free platforms that host models — run inference without downloading anything.

- [Hugging Face Spaces](https://huggingface.co/spaces) — Free hosting for ML apps (Gradio, Streamlit). Thousands of community demos.
- [Hugging Face Inference Endpoints (Free Tier)](https://huggingface.co/inference-endpoints) — Deploy models with free trial credits.
- [Google Colab (Free Tier)](https://colab.research.google.com/) — Free GPU (T4, sometimes A100). Perfect for running models and fine-tuning.
- [Kaggle Notebooks](https://www.kaggle.com/code) — Free GPU (T4 x2). 30 hours/week. Good for heavier workloads.
- [Lightning AI Studio](https://lightning.ai/) — Free tier with GPU access for development and prototyping.
- [Modal](https://modal.com/) — Free monthly credits for serverless GPU compute.
- [Replicate (Free Tier)](https://replicate.com/) — Free credits for running community models.
- [Deepnote](https://deepnote.com/) — Free tier with GPU for data science and ML notebooks.
- [Zylora](https://zylora.dev/) — Deploy GPU functions from any language. Free tier: $5 GPU credits/month, no credit card. T4/L4 pool, sub-300ms cold starts.

---

## 📚 Learning Resources

> 📅 Last checked: August 19, 2026

Free courses, books, and tutorials for learning AI and LLMs.

- [Fast.ai](https://www.fast.ai/) — Code-first deep learning education. Practical, free courses from fundamentals to advanced.
- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course) — Comprehensive free course on transformers, tokenizers, datasets, and deployment. **Note: renamed from "NLP Course."**
- [DeepLearning.AI Short Courses](https://www.deeplearning.ai/courses) — Free short courses on LLMs, RAG, LangChain, and AI agents.
- [Full Stack Deep Learning](https://fullstackdeeplearning.com/) — Free course on ML engineering: training, deploying, and maintaining models.
- [Andrej Karpathy's Course](https://karpathy.ai/zero-to-hero.html) — From-scratch neural network implementation videos.
- [Neural Networks: Zero to Hero](https://www.youtube.com/watch?v=VMj-3S1tku0&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) — YouTube series building neural networks from scratch.
- [Prompt Engineering Guide (DAIR.AI)](https://www.promptingguide.ai/) — Comprehensive free guide on prompt engineering techniques.
- [Anthropic Cookbook](https://github.com/anthropics/claude-cookbooks) — Free recipes and patterns for working with Claude.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) — Free examples and guides for the OpenAI API.
- [LearnLLM.dev](https://learnllm.dev/) — Free AI engineering course with 110+ lessons, runnable code, in-browser playground. Covers fundamentals to production agents.
- [LLM Zoomcamp (DataTalksClub)](https://github.com/DataTalksClub/llm-zoomcamp) — Free 10-week course on building LLM applications with RAG, agents, vector search, and evaluation.
- [AI Engineering from Scratch](https://github.com/rohitg00/ai-engineering-from-scratch) — **2026.** 503 lessons across 20 phases. Build LLMs, agents, and MCP servers from scratch. MIT. 47K+ stars.

---

## 🏆 Resources & Leaderboards

> 📅 Last checked: August 19, 2026

- [Perplexity](https://www.perplexity.ai/) — Free AI search and research assistant with real-time answers and source citations. **(HTTP 403 at check time; may block automation).**
- [BenchLM.ai](https://benchlm.ai/) — **New.** LLM leaderboard with 281 models compared across 8 categories. Verified benchmark data updated weekly.
- [Hugging Face Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) — The primary benchmark for open-weight models. Updated regularly.
- [LMSYS Chatbot Arena](https://arena.ai/) — Human preference rankings of models. Best source for real-world quality comparisons.
- [Artificial Analysis](https://artificialanalysis.ai/) — Independent benchmarks for speed, pricing, and quality across providers.
- [Hugging Face Models](https://huggingface.co/models) — Search 1M+ models. Filter by license, task, framework.
- [OpenRouter Models](https://openrouter.ai/models) — Browse models available via API with pricing and free tiers.
- [Ollama Library](https://ollama.com/library) — Browse models available for one-command local setup.

---

## 👥 Communities

> 📅 Last checked: August 19, 2026

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