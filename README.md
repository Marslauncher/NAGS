# 🗞️ News Aggregator Skill

[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/cclank/news-aggregator-skill.svg?style=social&label=Star)](https://github.com/cclank/news-aggregator-skill)
[![GitHub forks](https://img.shields.io/github/forks/cclank/news-aggregator-skill.svg?style=social&label=Fork)](https://github.com/cclank/news-aggregator-skill/network)

News Aggregator Skill
Python Version License: MIT GitHub stars GitHub forks

A comprehensive news aggregation assistant covering technology, finance, and AI, and a highly efficient information engine designed specifically for intelligent agents.

✨ Core Features
🌍 Multi-source aggregation across the entire network : One-stop coverage of 28+ high-value sources spanning Silicon Valley technology, Chinese venture capital, open source communities, financial markets, and top AI podcasts/hardcore tweets.
🚀 Perfect support for OpenClaw : Deeply customized for native large-model agent platforms (such as OpenClaw and Code Agent), plug and play, immersive information flow experience.
🆓 Ready to use out of the box (Zero-Config) : Clean scraping, no need to configure any third-party API keys , say goodbye to cumbersome environment variables and quota anxiety.
🧠 AI Intelligent Deep Fetch : Intelligently penetrates anti-crawler mechanisms (built-in Playwright bypasses Cloudflare), captures complete text content and hands it over to a large model for filtering, extraction and summarization.
📰 Scenario-based Daily Briefings : Built-in multiple scenario presets (Comprehensive Daily Briefing, Financial Daily Briefing, Tech Daily Briefing, Gossip Daily Briefing, AI In-depth Daily Briefing), generate magazine-level formatted Markdown Chinese reports with one click.
🪄 Magic Interactive Menu : Supports activating the global interactive menu with a unique password, say goodbye to tedious and complicated sentences, simply enter the number to point and select.
📚 Aggregated Source Map
The system now covers 28 mainstream high-value information channels worldwide, available for immediate use:

🎯 Core News Source
Global Tech : 🦄 Hacker News ( hackernews), 🐱 Product Hunt ( producthunt)
Open source updates : 🐙 GitHub Trending ( github), 🤓 V2EX ( v2ex)
Domestic risk control : 🚀 36Kr ( 36kr), 🐧 Tencent Technology ( tencent)
Social Finance : 🔴 Weibo Trending Topics ( weibo), 📈 Wall Street News ( wallstreetcn)
AI Paper : 🤗 Hugging Face Papers ( huggingface)
📧 AI Industry Insider (Newsletters & Creators)
🧪 Latent Space AINews ( latentspace_ainews) - (Recently Added)
ChinAI (Jeffrey Ding) ( chinai)
Memia (Ben Reid) ( memia)
Ben's Bites ( bensbites)
One Useful Thing (Ethan Mollick) (oneusefulthing)
Interconnects (Nathan Lambert) (interconnects)
AI to ROI & KDnuggets, etc...
✍️ Deep Thinking & Podcast
Industry Leaders Column : Paul Graham, James Clear, Wait But Why, Scott Young...
Top-tier hardcore podcast : Lex Fridman Podcast, Latent Space (swyx), 80,000 Hours...
📥 Installation Guide
Step 1: Install to Code Agent
Choose one of the following methods to add the Skill to your Agent:

Method A: Using Openskills CLI (Recommended)
It will automatically handle path dependencies and configuration synchronization.

# 安装 skill
openskills install git@github.com:cclank/news-aggregator-skill.git

# 同步配置到 Agent
openskills sync
Method B: Using NPX
Add directly from the remote repository.

npx skills add https://github.com/cclank/news-aggregator-skill
Method C: Manual Integration
git clone git@github.com:cclank/news-aggregator-skill.git YourProject/.claude/skills/news-aggregator-skill
Step 2: Install Python dependencies
Navigate to the directory where Skill is installed and perform the dependency installation (if your Agent is smart enough, you can request it to configure automatically):

cd YourProject/.claude/skills/news-aggregator-skill
pip install -r requirements.txt
playwright install chromium
🚀 How to use
1. 🔮 Wake up the interactive menu (Recommended)
The simplest and most engaging way to use it comes from a unique interactive easter egg: directly summon the smart command menu.

"news-aggregator-skill Ruyi Ruyi"

The system will immediately display a beautifully designed list of up to 35 function options. Simply reply with the number to generate today's market overview in perfect format!

2. 🗣️ Natural Language Trigger
You can also specify your requirements directly through the chat:

Scene Daily Report : "Could you get me a financial newsletter for today, to see what's happening in the market?"
Deep Fetch : "Scrape 5 of the latest GitHub trends, and remember to enable Deep Fetch to read their READMEs in detail."
Hardcore Scientific Research : "Let's see what amazing new papers HuggingFace has published today!"
Free combination : "Help me combine the top ten trending topics from Hacker News, Wall Street Journal, and Weibo today into a morning newsletter."
💡 Development and Expansion
We welcome pull requests to connect the framework with new, high-quality global information sources. Our goal is to jointly build a clean, efficient, and interference -resistant information acquisition platform.

📝 License : MIT License
