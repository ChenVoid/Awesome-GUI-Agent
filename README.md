<div align="center">

# Awesome GUI Agent

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Papers](https://img.shields.io/badge/Papers-200+-blue.svg)](#papers)

**A curated list of papers, benchmarks, datasets, and projects on GUI Agents powered by Large Language Models and Vision-Language Models.**

*Covering Computer Use / Mobile Use / Browser Use / Game Agents*

</div>

GUI Agents represent a rapidly evolving frontier where foundation models (LLMs/VLMs) learn to autonomously interact with graphical user interfaces — navigating PC softwares, mobile apps, web browsers, and even games — just like humans do. From [Anthropic Computer Use](https://docs.anthropic.com/en/docs/build-with-claude/computer-use) to [OpenAI Operator](https://openai.com/index/introducing-operator/) and [Google Mariner](https://deepmind.google/technologies/project-mariner/), major AI labs are racing to build agents that can see screens, understand UI elements, and take actions. This repository aims to provide the community with a comprehensive and timely collection of this exciting field.


---

## Table of Contents

- [Survey](#survey-)
- [Computer Use Agent](#computer-use--desktop-agent-)
- [Mobile Use Agent](#mobile-agent-)
- [Browser Use Agent](#web--browser-agent-)
- [Game Agent](#game-agent-)
- [Cross-Platform Agent](#cross-platform--unified-gui-agent-)
- [GUI Grounding & Understanding](#gui-grounding--understanding-)
- [Benchmarks & Datasets](#benchmarks--datasets-)
- [Projects & Toolkits](#projects--toolkits-)
- [Commercial Products](#commercial-products-)

---

## Survey 📖

* [2504] [Mobile GUI Agent] [A Survey on Mobile GUI Agents: from LLMs to Multimodal Models](https://arxiv.org/abs/2504.20635)

* [2504] [GUI Agent Survey] [A Survey on GUI Agents with Foundation Models: From LLMs to Multimodal Models](https://arxiv.org/abs/2504.10458)

* [2412] [GUI Agents] [GUI Agents: A Survey](https://arxiv.org/abs/2412.13501)

* [2411] [GUI Agents with FMs] [GUI Agents with Foundation Models: A Comprehensive Survey](https://arxiv.org/abs/2411.04890)

* [2411] [LLM-Brained GUI Agents] [Large Language Model-Brained GUI Agents: A Survey](https://arxiv.org/abs/2411.18279)

* [2410] [Autonomous Web Agents] [From Browsing to Playing: Bridging the Gap Between Vision and Action in the Visual World](https://arxiv.org/abs/2410.02907)

* [2403] [Game Playing Agents] [A Survey on Game Playing Agents and Large Models: Methods, Applications, and Challenges](https://arxiv.org/abs/2403.10249)

* [2401] [Personal LLM Agents] [Personal LLM Agents: Insights and Survey about the Capability, Efficiency and Security](https://arxiv.org/abs/2401.05459)

---

## Computer Use Agent 🖥️

* [2504] [Agent-S2] [Agent S2: A Compositional Generalist-Specialist Framework for Computer Use Agents](https://arxiv.org/abs/2504.00906) [[Code 💻](https://github.com/simular-ai/Agent-S)] [[Project 🌐](https://www.simular.ai/agent-s2)]

* [2504] [GUI-Bee] [GUI-Bee: Align GUI Action Grounding to Novel Environments via Autonomous Exploration](https://arxiv.org/abs/2504.15810)

* [2502] [PC-Agent] [PC-Agent: A Hierarchical Multi-Agent Collaboration Framework for Complex Task Automation on PC](https://arxiv.org/abs/2502.14538) [[Code 💻](https://github.com/GAIR-NLP/PC-Agent)]

* [2502] [OSCAR] [OSCAR: Operating System Control via State-Aware Reasoning and Re-Planning](https://arxiv.org/abs/2502.07463)

* [2412] [PC Agent] [PC Agent: While You Sleep, AI Works — A Cognitive Journey into Digital World](https://arxiv.org/abs/2412.17589)

* [2412] [Iris] [Iris: Breaking GUI Complexity with Adaptive Focus and Self-Refining](https://arxiv.org/abs/2412.10342)

* [2412] [OS-Genesis] [OS-Genesis: Automating GUI Agent Trajectory Construction via Reverse Task Synthesis](https://arxiv.org/abs/2412.19723)

* [2411] [AutoGLM] [AutoGLM: Autonomous Foundation Agents for GUIs](https://arxiv.org/abs/2411.00820)

* [2410] [Agent-S] [Agent S: An Open Agentic Framework that Uses Computers Like a Human](https://arxiv.org/abs/2410.08164) [[Code 💻](https://github.com/simular-ai/Agent-S)]

* [2409] [Windows Agent Arena] [Windows Agent Arena: Evaluating Multi-Modal OS Agents at Scale](https://arxiv.org/abs/2409.08264) [[Code 💻](https://github.com/microsoft/WindowsAgentArena)] [[Project 🌐](https://microsoft.github.io/WindowsAgentArena/)]

* [2404] [OSWorld] [OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments](https://arxiv.org/abs/2404.07972) [[Code 💻](https://github.com/xlang-ai/OSWorld)] [[Project 🌐](https://os-world.github.io/)]

* [2403] [Cradle] [Cradle: Empowering Foundation Agents Towards General Computer Control](https://arxiv.org/abs/2403.03186) [[Code 💻](https://github.com/BAAI-Agents/Cradle)] [[Project 🌐](https://baai-agents.github.io/Cradle/)]

* [2403] [AgentStudio] [AgentStudio: A Toolkit for Building General Virtual Agents](https://arxiv.org/abs/2403.17918) [[Code 💻](https://github.com/SkyworkAI/agent-studio)] [[Project 🌐](https://skyworkai.github.io/agent-studio/)]

* [2402] [UFO] [UFO: A UI-Focused Agent for Windows OS Interaction](https://arxiv.org/abs/2402.07939) [[Code 💻](https://github.com/microsoft/UFO)]

* [2402] [OS-Copilot] [OS-Copilot: Towards Generalist Computer Agents with Self-Improvement](https://arxiv.org/abs/2402.07456) [[Code 💻](https://github.com/OS-Copilot/OS-Copilot)] [[Project 🌐](https://os-copilot.github.io/)]

* [2402] [ScreenAgent] [ScreenAgent: A Computer Control Agent Driven by Visual Language Large Model](https://arxiv.org/abs/2402.07945) [[Code 💻](https://github.com/niuzaisheng/ScreenAgent)]

* [2312] [AssistGUI] [AssistGUI: Task-Oriented Desktop Graphical User Interface Automation](https://arxiv.org/abs/2312.13108) [[Project 🌐](https://showlab.github.io/assistgui/)]

---

## Mobile Use Agent 📱

* [2503] [Mobile-Agent-E] [Mobile-Agent-E: Self-Evolving Mobile Assistant for Complex Tasks](https://arxiv.org/abs/2503.02732) [[Code 💻](https://github.com/X-PLUG/MobileAgent)]

* [2501] [UI-TARS] [UI-TARS: Pioneering Automated GUI Interaction with Native Agents](https://arxiv.org/abs/2501.12326) [[Code 💻](https://github.com/bytedance/UI-TARS)] [[Models 🤗](https://huggingface.co/bytedance-research/UI-TARS-7B-DPO)]

* [2412] [Aguvis] [Aguvis: Unified Pure Vision Agents for Autonomous GUI Interaction](https://arxiv.org/abs/2412.04454) [[Project 🌐](https://aguvis-project.github.io/)] [[Models 🤗](https://huggingface.co/xlang-ai/aguvis-7b)]

* [2411] [GUI Odyssey] [GUI Odyssey: A Comprehensive Dataset for Cross-App GUI Navigation on Mobile Devices](https://arxiv.org/abs/2411.10349)

* [2410] [Ferret-UI 2] [Ferret-UI 2: Mastering Universal User Interface Understanding Across Platforms](https://arxiv.org/abs/2410.18967)

* [2408] [AppAgent v2] [AppAgent v2: Advanced Agent for Flexible Mobile Interactions](https://arxiv.org/abs/2408.11824) [[Project 🌐](https://appagent-official.github.io/)]

* [2407] [AMEX] [AMEX: Android Multi-annotation Expo Dataset for Mobile GUI Agents](https://arxiv.org/abs/2407.17490)

* [2407] [MobileFlow] [MobileFlow: A Multimodal LLM for Mobile GUI Agent](https://arxiv.org/abs/2407.04346)

* [2406] [Mobile-Agent v2] [Mobile-Agent v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration](https://arxiv.org/abs/2406.01014) [[Code 💻](https://github.com/X-PLUG/MobileAgent)]

* [2406] [DigiRL] [DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement Learning](https://arxiv.org/abs/2406.11896) [[Code 💻](https://github.com/DigiRL-agent/digirl)]

* [2406] [MobileAgentBench] [MobileAgentBench: An Efficient and User-Friendly Benchmark for Mobile LLM Agents](https://arxiv.org/abs/2406.08184)

* [2406] [Octo-planner] [Octo-planner: On-device Language Model for Planner-Action Agents](https://arxiv.org/abs/2406.18082)

* [2405] [AndroidWorld] [AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents](https://arxiv.org/abs/2405.14573) [[Code 💻](https://github.com/google-research/android_world)]

* [2404] [Ferret-UI] [Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs](https://arxiv.org/abs/2404.05719)

* [2404] [AndroidControl] [AndroidControl: Enabling Device Control with Various LLMs](https://arxiv.org/abs/2410.14573)

* [2404] [Mobile-Bench] [Mobile-Bench: An Evaluation Benchmark for LLM-based Mobile Agents](https://arxiv.org/abs/2404.16660)

* [2404] [B-MoCA] [B-MoCA: Benchmarking Mobile Device Control Agents across Diverse Configurations](https://arxiv.org/abs/2404.06647) [[Code 💻](https://github.com/b-moca/b-moca)]

* [2404] [LlamaTouch] [LlamaTouch: A Faithful and Scalable Testbed for Mobile UI Automation Task Evaluation](https://arxiv.org/abs/2404.16054) [[Code 💻](https://github.com/AnyDeviceLab/LlamaTouch)]

* [2401] [Mobile-Agent] [Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception](https://arxiv.org/abs/2401.16158) [[Code 💻](https://github.com/X-PLUG/MobileAgent)]

* [2401] [Auto-UI] [You Only Look at Screens: Multimodal Chain-of-Action Agents](https://arxiv.org/abs/2309.11436) [[Code 💻](https://github.com/cooelf/Auto-UI)]

* [2312] [AppAgent] [AppAgent: Multimodal Agents as Smartphone Users](https://arxiv.org/abs/2312.13771) [[Code 💻](https://github.com/mnotgod96/AppAgent)]

* [2312] [CogAgent] [CogAgent: A Visual Language Model for GUI Agents](https://arxiv.org/abs/2312.08914) [[Code 💻](https://github.com/THUDM/CogVLM)] [[Models 🤗](https://huggingface.co/THUDM/CogAgent-9B-20241220)]

* [2311] [MM-Navigator] [GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone GUI Navigation](https://arxiv.org/abs/2311.07562)

* [2308] [AutoDroid] [AutoDroid: LLM-powered Task Automation in Android](https://arxiv.org/abs/2308.15272)

* [2307] [AITW] [Android in the Wild: A Large-Scale Dataset for Android Device Control](https://arxiv.org/abs/2307.10088)

* [2306] [AdbGPT] [AdbGPT: Leveraging Large Language Models for Android Bug Replay](https://arxiv.org/abs/2306.17882)

* [2304] [DroidBot-GPT] [DroidBot-GPT: GPT-powered UI Exploration for Android](https://arxiv.org/abs/2304.07061) [[Code 💻](https://github.com/MobileLLM/DroidBot-GPT)]

* [2105] [AndroidEnv] [AndroidEnv: A Reinforcement Learning Platform for Android](https://arxiv.org/abs/2105.13231) [[Code 💻](https://github.com/google-deepmind/android_env)]

---

## Browser Use Agent 🌐

* [2504] [Steward] [Steward: Natural Language Web Automation](https://arxiv.org/abs/2504.16208)

* [2504] [WebThinker] [WebThinker: Empowering Large Reasoning Models with Deep Research Capability](https://arxiv.org/abs/2504.21776) [[Code 💻](https://github.com/RUC-NLPIR/WebThinker)]

* [2503] [Search-Agent] [Search-Agent: Reinforcement Learning Driven Autonomous Web Search](https://arxiv.org/abs/2503.11387)

* [2501] [Search-o1] [Search-o1: Agentic Search-Enhanced Large Reasoning Models](https://arxiv.org/abs/2501.05366) [[Code 💻](https://github.com/sunnynexus/Search-o1)]

* [2501] [WebWalkerQA] [WebWalkerQA: A Multi-Website Question Answering Benchmark for Web Agents](https://arxiv.org/abs/2501.07572) [[Code 💻](https://github.com/WebWalkerQA/WebWalker)]

* [2412] [AgentTrek] [AgentTrek: Agent Trajectory Synthesis via Guiding Replay with Web Tutorials](https://arxiv.org/abs/2412.09605)

* [2412] [Ponder & Press] [Ponder & Press: Advancing Visual GUI Agent towards General Computer Control](https://arxiv.org/abs/2412.01268)

* [2412] [BrowserGym] [BrowserGym: A Gym-like Environment for Web Agent Research](https://arxiv.org/abs/2412.05467) [[Code 💻](https://github.com/ServiceNow/BrowserGym)]

* [2411] [WebRL] [WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning](https://arxiv.org/abs/2411.02337) [[Code 💻](https://github.com/THUDM/WebRL)]

* [2411] [WebDreamer] [Is Your LLM Secretly a World Model of the Internet? Model-Based Planning for Web Agents](https://arxiv.org/abs/2411.06559) [[Code 💻](https://github.com/OSU-NLP-Group/WebDreamer)]

* [2410] [OpenWebVoyager] [OpenWebVoyager: Building Multimodal Web Agents via Iterative Real-World Exploration, Feedback and Optimization](https://arxiv.org/abs/2410.19012) [[Code 💻](https://github.com/MinorJerry/OpenWebVoyager)]

* [2410] [AgentOccam] [AgentOccam: A Simple Yet Strong Baseline for LLM-Based Web Agents](https://arxiv.org/abs/2410.13825)

* [2409] [AWM] [Agent Workflow Memory](https://arxiv.org/abs/2409.07429) [[Code 💻](https://github.com/zorazrw/agent-workflow-memory)]

* [2408] [AgentQ] [AgentQ: Advanced Reasoning and Learning for Autonomous AI Agents](https://arxiv.org/abs/2408.07199)

* [2408] [WebPilot] [WebPilot: A Versatile and Autonomous Multi-Agent System for Web Task Execution](https://arxiv.org/abs/2408.15978) [[Code 💻](https://github.com/WebPilot)]

* [2407] [Agent-E] [Agent-E: From Autonomous Web Navigation to Foundational Design Principles in Agentic Systems](https://arxiv.org/abs/2407.13032) [[Code 💻](https://github.com/EmergenceAI/Agent-E)]

* [2407] [Tree Search for LM Agents] [Tree Search for Language Model Agents](https://arxiv.org/abs/2407.01476) [[Code 💻](https://github.com/jykoh/tree-search-lm-agents)]

* [2407] [WorkArena++] [WorkArena++: Towards Compositional Planning and Reasoning-based Common Computer Tasks](https://arxiv.org/abs/2407.05291)

* [2407] [AssistantBench] [AssistantBench: Can Web Agents Solve Realistic and Time-Consuming Tasks?](https://arxiv.org/abs/2407.15711) [[Code 💻](https://github.com/oriyor/AssistantBench)]

* [2406] [WebCanvas] [WebCanvas: Benchmarking Web Agents in Online Environments](https://arxiv.org/abs/2406.12373) [[Code 💻](https://github.com/iMeanAI/WebCanvas)]

* [2404] [AutoWebGLM] [AutoWebGLM: A Large Language Model-based Web Navigating Agent](https://arxiv.org/abs/2404.03648) [[Code 💻](https://github.com/THUDM/AutoWebGLM)]

* [2404] [LASER] [LASER: LLM Agent with State-Space Exploration for Web Navigation](https://arxiv.org/abs/2404.13246) [[Code 💻](https://github.com/Mayer123/LASER)]

* [2403] [WorkArena] [WorkArena: How Capable Are Web Agents at Solving Common Knowledge Work Tasks?](https://arxiv.org/abs/2403.07718) [[Code 💻](https://github.com/ServiceNow/WorkArena)]

* [2403] [TurkingBench] [TurkingBench: A Challenge Benchmark for Web Agents](https://arxiv.org/abs/2403.11905)

* [2402] [WebLINX] [WebLINX: Real-World Website Navigation with Multi-Turn Dialogue](https://arxiv.org/abs/2402.05930) [[Code 💻](https://github.com/McGill-NLP/weblinx)] [[Datasets 🤗](https://huggingface.co/datasets/McGill-NLP/WebLINX)]

* [2401] [SeeAct] [GPT-4V(ision) is a Generalist Web Agent, if Grounded](https://arxiv.org/abs/2401.01614) [[Code 💻](https://github.com/OSU-NLP-Group/SeeAct)]

* [2401] [VisualWebArena] [VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks](https://arxiv.org/abs/2401.13649) [[Code 💻](https://github.com/web-arena-x/visualwebarena)]

* [2401] [WebVoyager] [WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models](https://arxiv.org/abs/2401.13919) [[Code 💻](https://github.com/MinorJerry/WebVoyager)]

* [2310] [SteP] [SteP: Stacked LLM Policies for Web Actions](https://arxiv.org/abs/2310.03720) [[Code 💻](https://github.com/asappresearch/webagents-step)]

* [2307] [WebArena] [WebArena: A Realistic Web Environment for Building Autonomous Agents](https://arxiv.org/abs/2307.13854) [[Code 💻](https://github.com/web-arena-x/webarena)] [[Project 🌐](https://webarena.dev/)]

* [2307] [WebAgent] [A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis](https://arxiv.org/abs/2307.12856)

* [2306] [Mind2Web] [Mind2Web: Towards a Generalist Agent for the Web](https://arxiv.org/abs/2306.06070) [[Code 💻](https://github.com/OSU-NLP-Group/Mind2Web)] [[Project 🌐](https://osu-nlp-group.github.io/Mind2Web/)]

* [2306] [Pix2Act] [From Pixels to UI Actions: Learning to Follow Instructions via Graphical User Interfaces](https://arxiv.org/abs/2306.00003) [[Code 💻](https://github.com/google-deepmind/pix2act)]

* [2305] [WebGUM] [WebGUM: Instruction-Finetuned Multimodal Agent for Web Navigation](https://arxiv.org/abs/2305.11854)

* [2207] [WebShop] [WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents](https://arxiv.org/abs/2207.01206) [[Code 💻](https://github.com/princeton-nlp/WebShop)]

---

## Game Agent 🎮

### Minecraft

* [2407] [Odyssey] [Odyssey: Empowering Agents with Open-World Skills](https://arxiv.org/abs/2407.15325)

* [2403] [MineDreamer] [MineDreamer: Learning to Follow Instructions via Chain-of-Imagination and Video Diffusion](https://arxiv.org/abs/2403.12037)

* [2311] [JARVIS-1] [JARVIS-1: Open-World Multi-task Agents with Memory-Augmented Multimodal Language Models](https://arxiv.org/abs/2311.05997) [[Code 💻](https://github.com/CraftJarvis/JARVIS-1)] [[Project 🌐](https://craftjarvis.github.io/JARVIS-1/)]

* [2310] [GROOT] [GROOT: Learning to Follow Instructions by Watching Gameplay Videos](https://arxiv.org/abs/2310.08235)

* [2310] [MCU] [MCU: A Task-centric Framework for Open-ended Agent Evaluation in Minecraft](https://arxiv.org/abs/2310.08367)

* [2305] [Voyager] [Voyager: An Open-Ended Embodied Agent with Large Language Models](https://arxiv.org/abs/2305.16291)

* [2305] [GITM] [Ghost in the Minecraft: Generally Capable Agents for Open-World Environments via LLMs with Text-based Knowledge and Memory](https://arxiv.org/abs/2305.17144) [[Code 💻](https://github.com/OpenGVLab/GITM)]

* [2303] [Plan4MC] [Plan4MC: Skill Reinforcement Learning and Planning for Open-World Minecraft Tasks](https://arxiv.org/abs/2303.16563)

* [2302] [DEPS] [Describe, Explain, Plan and Select: Interactive Planning with LLMs Enables Open-World Multi-Task Agents](https://arxiv.org/abs/2302.01560)

* [2306] [STEVE-1] [STEVE-1: A Generative Model for Text-to-Behavior in Minecraft](https://arxiv.org/abs/2306.00349)

* [2206] [MineDojo] [MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge](https://arxiv.org/abs/2206.08853)

### General Game Agents

* [2503] [CombatVLA] [CombatVLA: An Efficient Vision-Language-Action Model for Combat Tasks in 3D Action Role-Playing Games](https://openaccess.thecvf.com/content/ICCV2025/papers/Chen_CombatVLA_An_Efficient_Vision-Language-Action_Model_for_Combat_Tasks_in_3D_ICCV_2025_paper.pdf) [[Code 💻](https://github.com/ChenVoid/CombatVLA)] [[Project 🌐](https://combatvla.github.io/)]

* [2411] [BALROG] [BALROG: Benchmarking Agentic LLM and VLM Reasoning On Games](https://arxiv.org/abs/2411.13543) [[Project 🌐](https://balrog-benchmark.github.io/)]

* [2403] [Cradle] [Cradle: Empowering Foundation Agents Towards General Computer Control](https://arxiv.org/abs/2403.03186) [[Code 💻](https://github.com/BAAI-Agents/Cradle)] [[Project 🌐](https://baai-agents.github.io/Cradle/)]

* [2402] [PokeLLMon] [PokéLLMon: A Human-Parity Agent for Pokémon Battles with Large Language Models](https://arxiv.org/abs/2402.01118)

* [2312] [LLM StarCraft II] [Large Language Models Play StarCraft II: Benchmarks and A Chain of Summarization Approach](https://arxiv.org/abs/2312.11865)

* [2312] [Creative Agents] [Creative Agents: Empowering Agents with Imagination for Creative Tasks](https://arxiv.org/abs/2312.02519)

* [2310] [SmartPlay] [SmartPlay: A Benchmark for LLMs as Intelligent Agents](https://arxiv.org/abs/2310.01557)

* [2305] [SPRING] [SPRING: Studying the Paper and Reasoning to Play Games](https://arxiv.org/abs/2305.15486)


---

## Cross-Platform Agent 🔄

* [2504] [GUI-R1] [GUI-R1: A Generalist R1-Style Vision-Language Action Model For GUI Agents](https://arxiv.org/abs/2504.10147)

* [2503] [SpiritSight] [SpiritSight Agent: Advanced GUI Agent with One Look](https://arxiv.org/abs/2503.03196) [[Code 💻](https://github.com/FudanDISC/SpiritSight)]

* [2501] [UI-TARS] [UI-TARS: Pioneering Automated GUI Interaction with Native Agents](https://arxiv.org/abs/2501.12326) [[Code 💻](https://github.com/bytedance/UI-TARS)] [[Models 🤗](https://huggingface.co/bytedance-research/UI-TARS-7B-DPO)]

* [2412] [Aguvis] [Aguvis: Unified Pure Vision Agents for Autonomous GUI Interaction](https://arxiv.org/abs/2412.04454) [[Project 🌐](https://aguvis-project.github.io/)] [[Models 🤗](https://huggingface.co/xlang-ai/aguvis-7b)]

* [2411] [ShowUI] [ShowUI: One Vision-Language-Action Model for GUI Visual Agent](https://arxiv.org/abs/2411.17465) [[Code 💻](https://github.com/showlab/ShowUI)] [[Models 🤗](https://huggingface.co/showlab/ShowUI-2B)]

* [2411] [AutoGLM] [AutoGLM: Autonomous Foundation Agents for GUIs](https://arxiv.org/abs/2411.00820)

* [2411] [OS-Atlas] [OS-Atlas: A Foundation Action Model for Generalist GUI Agents](https://arxiv.org/abs/2410.23218) [[Code 💻](https://github.com/OS-Copilot/OS-Atlas)] [[Models 🤗](https://huggingface.co/OS-Copilot/OS-Atlas-Pro-7B)] [[Project 🌐](https://osatlas.github.io/)]

* [2410] [Ferret-UI 2] [Ferret-UI 2: Mastering Universal User Interface Understanding Across Platforms](https://arxiv.org/abs/2410.18967)

* [2410] [UGround] [Navigating the Digital World as Humans Do: Universal Visual Grounding for GUI Agents](https://arxiv.org/abs/2410.05243)

* [2404] [Ferret-UI] [Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs](https://arxiv.org/abs/2404.05719)

* [2402] [ScreenAI] [ScreenAI: A Vision-Language Model for UI and Infographics Understanding](https://arxiv.org/abs/2402.04615)

* [2401] [SeeClick] [SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents](https://arxiv.org/abs/2401.10935) [[Code 💻](https://github.com/njucckevin/SeeClick)] [[Models 🤗](https://huggingface.co/cckevinn/SeeClick)]

* [2312] [CogAgent] [CogAgent: A Visual Language Model for GUI Agents](https://arxiv.org/abs/2312.08914) [[Code 💻](https://github.com/THUDM/CogVLM)] [[Models 🤗](https://huggingface.co/THUDM/CogAgent-9B-20241220)]

---

## GUI Grounding & Understanding 🎯

* [2504] [ScreenSpot-Pro] [ScreenSpot-Pro: GUI Grounding for Professional High-Resolution Computer Use](https://arxiv.org/abs/2504.07981) [[Code 💻](https://github.com/likaixin2000/ScreenSpot-Pro)]

* [2408] [OmniParser] [OmniParser for Pure Vision Based GUI Agent](https://arxiv.org/abs/2408.00203) [[Code 💻](https://github.com/microsoft/OmniParser)]

* [2406] [GUICourse] [GUICourse: From General Vision Language Models to Versatile GUI Agents](https://arxiv.org/abs/2406.11317) [[Code 💻](https://github.com/yiye3/GUICourse)]

* [2406] [GUI Action Narrator] [GUI Action Narrator: Where and When Did That Action Take Place?](https://arxiv.org/abs/2406.13719)

* [2402] [OmniACT] [OmniACT: A Dataset and Benchmark for Enabling Multimodal Generalist Autonomous Agents for Desktop and Web](https://arxiv.org/abs/2402.17553)

* [2310] [Set-of-Mark] [Set-of-Mark Prompting Unleashes Extraordinary Visual Grounding in GPT-4V](https://arxiv.org/abs/2310.11441) [[Project 🌐](https://som-gpt4v.github.io/)]

* [2310] [ILuvUI] [ILuvUI: Instruction-tuned Language-Vision Modeling of UIs from Machine Conversations](https://arxiv.org/abs/2310.04869)

* [2209] [Spotlight] [Spotlight: Mobile UI Understanding using Vision-Language Models with a Focus](https://arxiv.org/abs/2209.14927)

---


## Benchmarks & Datasets 📊

### Multi-Platform Benchmarks

| Benchmark | Platform | Paper | Code |
|-----------|----------|-------|------|
| **ScreenSpot** | Mobile/Desktop/Web | [2401.10935](https://arxiv.org/abs/2401.10935) | [Code](https://github.com/njucckevin/SeeClick) |
| **ScreenSpot-Pro** | Desktop (Professional) | [2504.07981](https://arxiv.org/abs/2504.07981) | [Code](https://github.com/likaixin2000/ScreenSpot-Pro) |
| **OmniACT** | Desktop/Web | [2402.17553](https://arxiv.org/abs/2402.17553) | — |
| **GUI-World** | Desktop/Mobile/Web/Video | [2406.10819](https://arxiv.org/abs/2406.10819) | [Project](https://gui-world.github.io/) |
| **GUICourse** | Multi-Platform | [2406.11317](https://arxiv.org/abs/2406.11317) | [Code](https://github.com/yiye3/GUICourse) |
| **VisualAgentBench** | Web/Android/Embodied | [2408.06327](https://arxiv.org/abs/2408.06327) | — |
| **AgentBench** | OS/DB/Web/Game | [2308.03688](https://arxiv.org/abs/2308.03688) | — |

### Computer Use Benchmarks

| Benchmark | Platform | Paper | Code |
|-----------|----------|-------|------|
| **OSWorld** | Ubuntu/Windows/macOS | [2404.07972](https://arxiv.org/abs/2404.07972) | [Code](https://github.com/xlang-ai/OSWorld) |
| **Windows Agent Arena** | Windows | [2409.08264](https://arxiv.org/abs/2409.08264) | [Code](https://github.com/microsoft/WindowsAgentArena) |
| **MacOSArena** | MacOS | [2507.19478](https://arxiv.org/pdf/2507.19478) | [Code](https://github.com/open-compass/MMBench-GUI) |

### Mobile Use Benchmarks

| Benchmark | Platform | Paper | Code |
|-----------|----------|-------|------|
| **AITW** | Android | [2307.10088](https://arxiv.org/abs/2307.10088) | — |
| **AndroidWorld** | Android | [2405.14573](https://arxiv.org/abs/2405.14573) | [Code](https://github.com/google-research/android_world) |
| **AndroidControl** | Android | [2410.14573](https://arxiv.org/abs/2410.14573) | — |
| **AndroidEnv** | Android | [2105.13231](https://arxiv.org/abs/2105.13231) | [Code](https://github.com/google-deepmind/android_env) |
| **GUI Odyssey** | Mobile Cross-App | [2411.10349](https://arxiv.org/abs/2411.10349) | — |
| **AMEX** | Mobile | [2407.17490](https://arxiv.org/abs/2407.17490) | — |
| **Mobile-Bench** | Mobile | [2404.16660](https://arxiv.org/abs/2404.16660) | — |
| **MobileAgentBench** | Mobile | [2406.08184](https://arxiv.org/abs/2406.08184) | — |
| **B-MoCA** | Mobile | [2404.06647](https://arxiv.org/abs/2404.06647) | [Code](https://github.com/b-moca/b-moca) |
| **LlamaTouch** | Mobile | [2404.16054](https://arxiv.org/abs/2404.16054) | [Code](https://github.com/AnyDeviceLab/LlamaTouch) |
| **Rico** | Mobile UI | [UIST'17](https://dl.acm.org/doi/10.1145/3126594.3126651) | [Project](http://interactionmining.org/rico) |
| **ScreenQA** | Mobile Screenshots | [2209.08199](https://arxiv.org/abs/2209.08199) | — |
| **Widget Captioning** | Mobile UI | [2010.04295](https://arxiv.org/abs/2010.04295) | — |

### Browser Use Benchmarks

| Benchmark | Platform | Paper | Code |
|-----------|----------|-------|------|
| **WebArena** | Web | [2307.13854](https://arxiv.org/abs/2307.13854) | [Code](https://github.com/web-arena-x/webarena) |
| **VisualWebArena** | Web | [2401.13649](https://arxiv.org/abs/2401.13649) | [Code](https://github.com/web-arena-x/visualwebarena) |
| **Mind2Web** | Web | [2306.06070](https://arxiv.org/abs/2306.06070) | [Code](https://github.com/OSU-NLP-Group/Mind2Web) |
| **WebLINX** | Web | [2402.05930](https://arxiv.org/abs/2402.05930) | [Code](https://github.com/McGill-NLP/weblinx) |
| **WorkArena** | Web (Enterprise) | [2403.07718](https://arxiv.org/abs/2403.07718) | [Code](https://github.com/ServiceNow/WorkArena) |
| **WorkArena++** | Web (Enterprise) | [2407.05291](https://arxiv.org/abs/2407.05291) | — |
| **WebCanvas** | Web | [2406.12373](https://arxiv.org/abs/2406.12373) | [Code](https://github.com/iMeanAI/WebCanvas) |
| **WebShop** | Web (E-commerce) | [2207.01206](https://arxiv.org/abs/2207.01206) | [Code](https://github.com/princeton-nlp/WebShop) |
| **AssistantBench** | Web | [2407.15711](https://arxiv.org/abs/2407.15711) | [Code](https://github.com/oriyor/AssistantBench) |
| **BrowserGym** | Web | [2412.05467](https://arxiv.org/abs/2412.05467) | [Code](https://github.com/ServiceNow/BrowserGym) |
| **MiniWoB++** | Web (Simplified) | [Liu et al., 2018](http://proceedings.mlr.press/v80/liu18b.html) | — |
| **TurkingBench** | Web | [2403.11905](https://arxiv.org/abs/2403.11905) | — |
| **WebWalkerQA** | Web | [2501.07572](https://arxiv.org/abs/2501.07572) | [Code](https://github.com/WebWalkerQA/WebWalker) |

### Game Benchmarks

| Benchmark | Platform | Paper | Code |
|-----------|----------|-------|------|
| **MineDojo** | Minecraft | [2206.08853](https://arxiv.org/abs/2206.08853) | — |
| **MCU** | Minecraft | [2310.08367](https://arxiv.org/abs/2310.08367) | — |
| **BALROG** | Multi-Game | [2411.13543](https://arxiv.org/abs/2411.13543) | [Project](https://balrog-benchmark.github.io/) |
| **SmartPlay** | Multi-Game | [2310.01557](https://arxiv.org/abs/2310.01557) | — |

---

## Projects & Toolkits 🛠️

| Project | Description | Links |
|---------|-------------|-------|
| **BrowserGym** | Gym-like environment for web agent research | [GitHub](https://github.com/ServiceNow/BrowserGym) |
| **AgentStudio** | Toolkit for building general virtual agents | [GitHub](https://github.com/SkyworkAI/agent-studio) |
| **OSWorld** | Real computer environment for multimodal agents | [GitHub](https://github.com/xlang-ai/OSWorld) |
| **UFO** | UI-focused agent for Windows OS | [GitHub](https://github.com/microsoft/UFO) |
| **OmniParser** | Pure vision-based GUI parsing | [GitHub](https://github.com/microsoft/OmniParser) |
| **WebArena** | Realistic web environment for agents | [GitHub](https://github.com/web-arena-x/webarena) |
| **AndroidEnv** | RL platform for Android | [GitHub](https://github.com/google-deepmind/android_env) |
| **AndroidWorld** | Dynamic benchmarking for Android agents | [GitHub](https://github.com/google-research/android_world) |
| **Mobile-Agent** | Multi-modal mobile device agent series | [GitHub](https://github.com/X-PLUG/MobileAgent) |
| **Cradle** | General computer control framework | [GitHub](https://github.com/BAAI-Agents/Cradle) |
| **OS-Copilot** | Generalist computer agent with self-improvement | [GitHub](https://github.com/OS-Copilot/OS-Copilot) |
| **Agent-S** | Open agentic framework for computer use | [GitHub](https://github.com/simular-ai/Agent-S) |
| **ShowUI** | Vision-language-action model for GUI | [GitHub](https://github.com/showlab/ShowUI) |
| **SeeClick** | GUI grounding visual agent | [GitHub](https://github.com/njucckevin/SeeClick) |
| **UI-TARS** | Automated GUI interaction native agent | [GitHub](https://github.com/bytedance/UI-TARS) |
| **WebRL** | Self-evolving curriculum RL for web agents | [GitHub](https://github.com/THUDM/WebRL) |
| **DigiRL** | Autonomous RL for device control | [GitHub](https://github.com/DigiRL-agent/digirl) |

---

## Commercial Products 🏢

| Product | Company | Description | Links |
|---------|---------|-------------|-------|
| **Computer Use** | Anthropic | Claude-powered computer control via screenshots | [Docs](https://docs.anthropic.com/en/docs/build-with-claude/computer-use) |
| **Operator (CUA)** | OpenAI | Computer-Using Agent for browser-based tasks | [Blog](https://openai.com/index/introducing-operator/) |
| **Project Mariner** | Google DeepMind | AI agent for web browser navigation | [Blog](https://deepmind.google/technologies/project-mariner/) |
| **AutoGLM** | Zhipu AI | Autonomous foundation agent for GUIs | [Paper](https://arxiv.org/abs/2411.00820) |
| **UI-TARS** | ByteDance | Native GUI interaction agent | [Paper](https://arxiv.org/abs/2501.12326) |

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ChenVoid/Awesome-GUI-Agent&type=Date)](https://star-history.com/#ChenVoid/Awesome-GUI-Agent&Date)

---


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

---

<div align="center">

**If you find this repository useful, please give it a ⭐!**

</div>
