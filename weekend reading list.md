# AI & Tech Bookmarks Summary

**Source:** `TwitterBookmarks_2026-11-11-23-11_69_filtered.json` (50 of 69 original bookmarks — 19 non-AI/non-technical posts removed)
**Date range covered:** 2022-01-20 to 2026-11-10

## Overview

This set of bookmarks tracks a shift in how AI engineering is actually practiced: moving from one-off prompting toward durable **skills, context graphs, and agent harnesses** (Claude Code, prompt caching, context engineering), alongside a steady stream of **hands-on RAG/agent build tutorials**, **MCP server/agent tooling**, **LLM/ML fundamentals**, **AI-assisted coding tools** (Cursor, Windsurf), **industry news**, **career advice for engineers**, and **generative AI for creative work** (images, video, avatars).

---

## 1. Agentic Engineering, Context & Skills

The throughline across this set: prompting is being replaced by durable artifacts — skills, graphs, and cached context — as the real unit of agent engineering.

- **@godsystemsmd** — Garry Tan (YC CEO) on why he doesn't "prompt" Claude Code — skills *are* the prompts; thin harness, fat skills. [Link](https://twitter.com/godsystemsmd/status/2120157040081338509)
- **@FDavidsonT** — "OpenAI Acquires Odessia": founder's detailed account of building an AI travel-agent startup almost entirely with agent harnesses, voice prompts, and skills, before OpenAI acquired it. [Link](https://x.com/FDavidsonT/article/2120214953349263473)
- **@dkfromdk** — "Fixing Enterprise AI Pilots": the 7 real reasons enterprise agent pilots fail (no process map, no baseline, building sidekicks instead of background agents, no owner, no plan past month 7). [Link](https://x.com/dkfromdk/article/2116291363407044676)
- **@LunarResearcher** — Andrej Karpathy's thesis that prompting is going away in favor of graphs: Prompts → Agents → Loops → Graphs. [Link](https://twitter.com/LunarResearcher/status/2111806045429387749)
- **@iiiichigo_chan** — Google engineer claims 85% of PRs at Google now ship via AI agents, not manual prompting. [Link](https://twitter.com/iiiichigo_chan/status/2097405747999240408)
- **@alex_prompter** — Quote-tweet flagging a must-read on FDEs (Forward Deployed Engineers), the role embedding technical builders directly with AI agent deployments. [Link](https://twitter.com/alex_prompter/status/2093050477688558051)
- **@AndrewYNg** — A map of the most important skills in AI Engineering. [Link](https://twitter.com/AndrewYNg/status/2088302050706686198)
- **@akshay_pachaar** — "Prompt caching, clearly explained": how Claude Code gets a 92% cache hit-rate and ~81% cost cut via KV-caching and static/dynamic prompt structuring. [Link](https://x.com/akshay_pachaar/article/2031021906254766128)
- **@jainarvind** (Glean CEO) — "How do you build a context graph?": Glean's approach to modeling *how* work happens (not just what exists) so agents can automate real enterprise processes. [Link](https://x.com/jainarvind/article/2019553277571190821)

## 2. Building AI Agents, MCP Servers & Multi-Agent Systems

- **@santtiagom_** — Breakdown of Uber's published MCP infrastructure for connecting agents to thousands of internal services. [Link](https://twitter.com/santtiagom_/status/2106483024129147108)
- **@alex_verem** — GitHub repo "marketingskills" (46.8k stars) giving an AI agent 50 free marketing specialist skills as markdown files. [Link](https://twitter.com/alex_verem/status/2095920078231625991)
- **@jeffhollan** — Microsoft Foundry Agents preview: build/run/deploy agents with any model, framework, or harness in the cloud. [Link](https://twitter.com/jeffhollan/status/2047005443780964623)
- **@DailyDoseOfDS_** — Easiest way to build an MCP server: FastMCP + GitIngest + Factory generates production-ready code automatically. [Link](https://twitter.com/DailyDoseOfDS_/status/1959548779742601417)
- **@Saboo_Shubham_** — Built a multimodal AI coding agent team: 3 agents (coding via o3-mini, vision via Gemini, execution via E2B) working together, open source. [Link](https://twitter.com/Saboo_Shubham_/status/1887704636838322395)
- **@Saboo_Shubham_** — 4 open-source, free alternatives to OpenAI's $200/month Deep Research agent. [Link](https://twitter.com/Saboo_Shubham_/status/1886979815951229423)
- **@AlexReibman** — Recap of a 200+ hacker hackathon exploring Gemini's multimodal/generative video capabilities. [Link](https://twitter.com/AlexReibman/status/1886240357295497297)
- **@Saboo_Shubham_** — Curated GitHub repo of LLM apps built with AI agents and RAG. [Link](https://twitter.com/Saboo_Shubham_/status/1879007426780995917)
- **@gregisenberg** — 35 startup ideas for 2025, many built around AI agents/SaaS (e.g., agents that turn demo calls into microsites). [Link](https://twitter.com/gregisenberg/status/1874826863765307703)
- **@akshay_pachaar** — Step-by-step: build a real-time AI voice assistant. [Link](https://twitter.com/akshay_pachaar/status/1863928104441573847)
- **@akshay_pachaar** — Step-by-step: build a multi-agent internet research assistant with OpenAI Swarm & local Llama 3.2. [Link](https://twitter.com/akshay_pachaar/status/1851602459225108693)
- **@paulabartabajo_** — Step-by-step: build an AI coding assistant with Llama 3. [Link](https://twitter.com/paulabartabajo_/status/1788268662769557930)

## 3. RAG & LLM App Tutorials

- **@gkcs_** — Blog post on combining OpenAI with Postgres for software engineers. [Link](https://twitter.com/gkcs_/status/2111382216257441964)
- **@akshay_pachaar** — Step-by-step: build a fully local RAG app using Google DeepMind's Gemma 3. [Link](https://twitter.com/akshay_pachaar/status/1899800040266514793)
- **@rohanpaul_ai** — Crawl entire websites into LLM-ready markdown with Claude 3.5/GPT-4 + open-source Firecrawl. [Link](https://twitter.com/rohanpaul_ai/status/1842571646797811716)
- **@Sumanth_077** — Build a RAG app to chat with PDFs using Gemini Flash in 4 lines of Python. [Link](https://twitter.com/Sumanth_077/status/1805248692099645786)
- **@avthar** — pgai: open-source Postgres extension adding embeddings and model completion directly in the database. [Link](https://twitter.com/avthar/status/1800923522442625509)
- **@Saboo_Shubham_** — Build a RAG app to chat with a GitHub repo in 30 lines of Python. [Link](https://twitter.com/Saboo_Shubham_/status/1786957511599538402)

## 4. LLM/ML Fundamentals & Data

- **@divaagurlxw** — Why evals are the most underrated skill in AI engineering; a practical error-analysis-first workflow. [Link](https://twitter.com/divaagurlxw/status/2115418017891020888)
- **@quantscience_** — Free, open-source Python project for stock price prediction using ML/deep learning. [Link](https://twitter.com/quantscience_/status/1887852696088015179)
- **@philipvollet** — The Synthetic Data Vault (SDV): ecosystem for generating synthetic single/multi-table and time-series data. [Link](https://twitter.com/philipvollet/status/1484114778801033224)
- **@tunguz** — Python 3.14 ("Python π") release notes — Python's continued dominance in data science/ML. [Link](https://twitter.com/tunguz/status/1878800579813892354)
- **@virattt** — Trained a 124M-parameter LLM from scratch in ~26 seconds on Google Colab, with full training details. [Link](https://twitter.com/virattt/status/1799886089944957283)
- **@Sumanth_077** — 5 GitHub repos worth checking for Data Scientists/ML Engineers. [Link](https://twitter.com/Sumanth_077/status/1757412428571459790)

## 5. AI Coding Tools (Cursor, Windsurf, Dev Tooling)

- **@marklaunches** — Useful open-source dev-tool repos: Brag (product demo videos), Postiz (social scheduling), Agent Reach (customer research). [Link](https://twitter.com/marklaunches/status/2109594385448870350)
- **@kasuncfdo** — 5 UI component libraries to use instead of default shadcn for a more polished look. [Link](https://twitter.com/kasuncfdo/status/2103832013426004335)
- **@cjzafir** — Complete step-by-step guide to using Cursor. [Link](https://twitter.com/cjzafir/status/1874869482986029082)
- **@cjzafir** — Trick to cut Cursor/Windsurf hallucinations ~80% by maintaining a project "Documentation" folder. [Link](https://twitter.com/cjzafir/status/1871595879490330759)

## 6. AI Industry News & Research Curiosities

- **@ns123abc** — John Jumper (DeepMind director, AlphaFold co-creator, Nobel laureate) announces he's leaving Google DeepMind for Anthropic. [Link](https://twitter.com/ns123abc/status/2068023211904602418)
- **@koltregaskes** — Testing/failing a Gemini image-editing ("defog") task, reporting bugs back to Google. [Link](https://twitter.com/koltregaskes/status/1962206314093859287)
- **@VickyLovesAI** — Roundup of Gemini 2.0 Flash's native image generation update and its impact on other image-gen tools. [Link](https://twitter.com/VickyLovesAI/status/1900367589026779314)
- **@SebastianNehrd2** — Draws a parallel between modern LLM emergent capabilities and the ancient Māṇḍūkya Upaniṣad's claims about language and reality. [Link](https://twitter.com/SebastianNehrd2/status/1863244626884481321)
- **@dr_cintas** — Weekly AI news roundup: FLUX.1, Mistral's le Chat, Runner H, v0, Gemini Memory, HeyGen, DeepSeek, and more. [Link](https://twitter.com/dr_cintas/status/1859682938549567497)

## 7. Career & Engineering Skills

- **@GrahamHelton3** — ~34 personal engineering/career guidelines compiled while moving roles from Google to Snowflake. [Link](https://twitter.com/GrahamHelton3/status/1936462167751921698)
- **@Sumanth_077** — A Python learning roadmap, reflecting on 5 years of experience. [Link](https://twitter.com/Sumanth_077/status/1878799466930815056)
- **@ProgressiveCod2** — 6 case studies offering fresh perspective on software development practice. [Link](https://twitter.com/ProgressiveCod2/status/1758396140729610348)
- **@Franc0Fernand0** — The 9 soft skills that matter for getting a software engineer promoted. [Link](https://twitter.com/Franc0Fernand0/status/1758106433508315526)

## 8. Generative AI for Creative Work

- **@prompt_mastery** — Tutorial: designing logos with generative AI (Midjourney/Stable Diffusion), with a simplicity-first workflow. [Link](https://twitter.com/prompt_mastery/status/1692914112403996817)
- **@TheJasSingh** — 3-step guide to generating an AI avatar video using ChatGPT plugins. [Link](https://twitter.com/TheJasSingh/status/1665368050022105088)
- **@svpino** — Turn a photo gallery into unlimited AI-generated images with a few lines of Python. [Link](https://twitter.com/svpino/status/1663153246981201921)
- **@venturetwins** — Turn yourself into a Pixar character in under 15 minutes using Midjourney, ElevenLabs, and HeyGen. [Link](https://twitter.com/venturetwins/status/1662931945486180354)
