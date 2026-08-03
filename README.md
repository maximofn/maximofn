# Máximo Fernández Núñez - I build LLM agents that reach production

**AI Engineer · Madrid · 13+ years shipping systems that run in the real world**

> "The best model is the one running in production."

[![Website](https://img.shields.io/badge/maximofn.com-2b55bc?style=flat-square&logo=google-chrome&logoColor=white)](https://www.maximofn.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/MaximoFN/)
[![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=000)](https://huggingface.co/Maximofn)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/Maximo_fn)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://kaggle.com/maximofn)

---

## About Me

I build LLM agents that make it into production: architecture, tool design, observability, deployment.

The last one was the agent behind an inspection assistant for **Spain's national grid operator**. Millions of high-voltage pylon photos with their defects, which technicians had to review tower by tower. Now they query by region and defect type, and repair crews get prioritised from that.

I redesigned it from single intent-to-tool routing into a **multi-step ReAct loop over ~10 tools**, added multi-provider failover, guardrails, step limits, prompt caching and per-user memory, and introduced **LangSmith tracing**, which turned "it doesn't fail for me" into failures we could reproduce exactly, in seconds instead of weeks.

Before agents, a decade in **computer vision and embedded systems**: perception stacks running on NVIDIA AGX Orin, UAV platforms, PCB and firmware design. That combination, agents plus knowing what it takes to run on real hardware, is where I'm most useful.

## GitHub Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/maximofn/maximofn/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/maximofn/maximofn/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/maximofn/maximofn/output/github-contribution-grid-snake.svg" />
</picture>

## 🤖 Agents

| Repository | What it is |
| --- | --- |
| [**gymnasia**](https://github.com/maximofn/gymnasia) | Fitness app with **two agents running fully on-device, no backend**, user data never leaves the phone. BYOK conversational coach (OpenAI / Anthropic / Google adapters, 12 local tools, streaming tool-use loop) plus a vision sub-agent estimating macros from meal photos. [**Architecture write-up →**](https://gymnasia-sable.vercel.app/) |
| [**langgraph_deepresearcher**](https://github.com/maximofn/langgraph_deepresearcher) | Deep research implementation with LangGraph: multi-agent supervisor, researchers and writer. [**Try it →**](https://deepresearcher.maximofn.com/) |
| [**alfred**](https://github.com/maximofn/alfred) | Terminal assistant powered by LLMs, for any OS and language |
| [**all_to_markdown**](https://github.com/maximofn/all_to_markdown) | Convert any documentation into markdown for LLM consumption |

## 🎙️ Writing & speaking

- **[Welcome to la secta](https://www.youtube.com/@Welcometolasecta)**, Weekly AI podcast, 800 subscribers, ~500 views per episode. The whole post-production pipeline is automated with generative AI: rendering, YouTube upload, clip and short generation, social distribution, voice cloning and lip-sync.
- **[maximofn.com](https://www.maximofn.com/)**, 60+ technical posts on AI. Recent: [Deep Research with LangGraph](https://www.maximofn.com/deepresearcher/), [MCP Elicitation](https://www.maximofn.com/mcp-elicitation/), [MCP Durability](https://www.maximofn.com/durability-mcp/).
- **Talks**, [Tomorrow's Agents: planning, UX and memory](https://www.youtube.com/watch?v=GHYkrxV8EPA) · [Build your own Apple Intelligence](https://www.youtube.com/watch?v=7b4v2tGHPBM)

## ⚙️ Systems & tooling

| Repository | What it is |
| --- | --- |
| [**gpu_monitor**](https://github.com/maximofn/gpu_monitor) | Real-time NVIDIA GPU monitor for Linux and macOS. Rust workspace splitting an NVML sampling daemon (HTTP + SSE API) from the tray frontends, so any machine on the LAN can consume the same metrics. Rewriting it from Python cut memory from 181 MB to ~24 MB and CPU from 176% to ~1.6% on the same two RTX 3090s. Includes a native Swift menubar app and a Home Assistant integration. |
| [**all_to_markdown**](https://github.com/maximofn/all_to_markdown) | LLM-driven crawler that walks documentation sites and converts every page, plus PDFs, YouTube videos and Office files, into markdown for LLM consumption |
| [**subtify**](https://github.com/maximofn/subtify) | Multilingual subtitle generation for YouTube and Twitch video, with per-speaker colour coding: vocal separation, transcription, translation and burn-in |
| [**open-cameras-viewer**](https://github.com/maximofn/open-cameras-viewer) | Multi-camera RTSP viewer over go2rtc, with persisted layout preferences |

<details>
<summary><b>🐳 25+ AI Docker containers</b>, state-of-the-art models packaged to <code>docker run</code> and go</summary>

Video generation, voice cloning, image editing, VLMs, TTS, human mesh recovery and more. Built so a broken or deleted Hugging Face Space never blocks anyone.

[marker_api_docker](https://github.com/maximofn/marker_api_docker) · [DynamiCrafter_docker](https://github.com/maximofn/DynamiCrafter_docker) · [idm_vton_docker](https://github.com/maximofn/idm_vton_docker) · [openVoiceV2_docker](https://github.com/maximofn/openVoiceV2_docker) · [FLUX.1-RealismLora-docker](https://github.com/maximofn/FLUX.1-RealismLora-docker) · [sadTalker_docker](https://github.com/maximofn/sadTalker_docker) · [moondream2_docker](https://github.com/maximofn/moondream2_docker) · [FLUX.1-schnell-docker](https://github.com/maximofn/FLUX.1-schnell-docker) · [flow_edit_docker](https://github.com/maximofn/flow_edit_docker) · [tokenHMR_docker](https://github.com/maximofn/tokenHMR_docker) · [tooncrafter_docker](https://github.com/maximofn/tooncrafter_docker) · [openDevin_docker](https://github.com/maximofn/openDevin_docker) · [brushnet_docker](https://github.com/maximofn/brushnet_docker) · [ml_mgie_docker](https://github.com/maximofn/ml_mgie_docker) · [cosxl_docker](https://github.com/maximofn/cosxl_docker) · [zeST_docker](https://github.com/maximofn/zeST_docker) · [singing_songstarter_docker](https://github.com/maximofn/singing_songstarter_docker) · [ai_jukebox_docker](https://github.com/maximofn/ai_jukebox_docker) · [idefics_8b_docker](https://github.com/maximofn/idefics_8b_docker) · [tango2_docker](https://github.com/maximofn/tango2_docker) · [ranni_docker](https://github.com/maximofn/ranni_docker) · [face-to-all-docker](https://github.com/maximofn/face-to-all-docker) · [voiceCraft_docker](https://github.com/maximofn/voiceCraft_docker) · [aniPortrait_docker](https://github.com/maximofn/aniPortrait_docker) · [coqui_TTS_docker](https://github.com/maximofn/coqui_TTS_docker)

</details>

---

## Tech Stack

**Agents & LLMs**
LangGraph · LangChain · LangSmith · MCP / FastMCP · OpenAI Agents SDK · ReAct architectures · RAG · vector databases · guardrails · multi-provider failover

**ML & vision**
PyTorch · Hugging Face · TensorRT · YOLO · segmentation · detection · depth estimation · fine-tuning · dataset creation

**Engineering**
Python · SQL · Docker · Kubernetes · Git · CI/CD · Bash · Linux · FastAPI · React

**Cloud & edge**
Azure (ML, Functions) · AWS S3 · Railway · Vercel · Cloudflare · NVIDIA Jetson / AGX Orin · embedded firmware · PCB design

---

## Get in Touch

[![Email](https://img.shields.io/badge/maximofn@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:maximofn@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/MaximoFN/)
[![Website](https://img.shields.io/badge/maximofn.com-2b55bc?style=flat-square&logo=google-chrome&logoColor=white)](https://www.maximofn.com/)

If you find something here useful, a ⭐ is always welcome.
