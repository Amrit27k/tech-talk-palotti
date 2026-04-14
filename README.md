<div align="center">

# 🤖 tech-talk-SVPCET

**A community-driven tech talk repository for SVPCET — slides, resources & learning references.**

[![Repo Visits](https://visitor-badge.laobi.icu/badge?page_id=Amrit27k.tech-talk-palotti)](https://github.com/Amrit27k/tech-talk-palotti)
[![GitHub Stars](https://img.shields.io/github/stars/Amrit27k/tech-talk-palotti?style=flat&logo=github&color=yellow)](https://github.com/Amrit27k/tech-talk-palotti/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/Amrit27k/tech-talk-palotti?style=flat&logo=github&color=blue)](https://github.com/Amrit27k/tech-talk-palotti/network/members)
[![GitHub Watchers](https://img.shields.io/github/watchers/Amrit27k/tech-talk-palotti?style=flat&logo=github&color=green)](https://github.com/Amrit27k/tech-talk-palotti/watchers)
[![GitHub Issues](https://img.shields.io/github/issues/Amrit27k/tech-talk-palotti?style=flat&logo=github&color=red)](https://github.com/Amrit27k/tech-talk-palotti/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat&logo=github)](https://github.com/Amrit27k/tech-talk-palotti/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Clone the Repository](#-clone-the-repository)
- [How to Contribute (Beginner's Guide)](#-how-to-contribute-beginners-guide)
- [Reference Links — AI Landscape (16 Apr 2026)](#-reference-links--ai-landscape-16-apr-2026)
- [License](#-license)

---

## 📖 About

This repository contains slides, notes, and learning resources from tech talks organised at SVPCET. Each folder corresponds to a talk session with its date. The goal is to make learning accessible and collaborative for everyone.

---

## 📥 Clone the Repository

Open your terminal and run:

```bash
git clone https://github.com/Amrit27k/tech-talk-palotti.git
cd tech-talk-palotti
```

---

## 🤝 How to Contribute (Beginner's Guide)

Never contributed to open source before? No worries — follow these steps one by one. 🚀

### Step 1 — Fork the Repository

Click the **Fork** button at the top-right corner of the repository page on GitHub.  
This creates a personal copy of the repo under **your** GitHub account.

```
https://github.com/Amrit27k/tech-talk-palotti  ← original
https://github.com/<your-username>/tech-talk-palotti  ← your fork
```

### Step 2 — Clone Your Fork Locally

```bash
git clone https://github.com/<your-username>/tech-talk-palotti.git
cd tech-talk-palotti
```

### Step 3 — Add the Upstream Remote

This keeps your fork in sync with the original repository.

```bash
git remote add upstream https://github.com/Amrit27k/tech-talk-palotti.git
git remote -v   # verify both origin and upstream appear
```

### Step 4 — Create a New Branch

Always create a new branch for your changes. Never work directly on `main`.

```bash
git checkout -b your-branch-name
# Example: git checkout -b add-ai-landscape-resources
```

### Step 5 — Make Your Changes

Add your files, fix typos, update links, or add new resources. Then stage and commit your changes:

```bash
git add .
git commit -m "feat: add reference links for AI landscape talk"
```

> 💡 **Tip:** Write clear commit messages describing *what* you changed and *why*.

### Step 6 — Push to Your Fork

```bash
git push origin your-branch-name
```

### Step 7 — Open a Pull Request (PR)

1. Go to your fork on GitHub: `https://github.com/<your-username>/tech-talk-palotti`
2. You'll see a banner saying **"Compare & pull request"** — click it.
3. Add a clear **title** and **description** explaining your changes.
4. Click **"Create pull request"**.

That's it! A maintainer will review your PR and merge it if everything looks good. 🎉

### Step 8 — Keep Your Fork Up to Date

Before starting any new contribution, sync your fork with the original:

```bash
git checkout main
git fetch upstream
git merge upstream/main
git push origin main
```

---

## 📚 Reference Links — AI Landscape (09 Apr 2026)

> Resources corresponding to the slides in the [`AI-landscape-16042026`](./AI-landscape-16042026/) folder.

### 🗺️ AI Landscape Overview

| Topic | Resource |
|-------|----------|
| What is AI / ML / DL | [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course) |
| Large Language Models (LLMs) | [Andrej Karpathy — Intro to LLMs](https://www.youtube.com/watch?v=zjkBMFhNj_g) |
| Transformer Architecture | [The Illustrated Transformer — Jay Alammar](https://jalammar.github.io/illustrated-transformer/) |
| Generative AI Basics | [Google — Generative AI Learning Path](https://cloud.google.com/learn/training/machinelearning-ai) |
| Prompt Engineering | [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering) |
| AI Tools & Ecosystem | [There's An AI For That](https://theresanaiforthat.com/) |

### 🛠️ Foundational CS & System Design

| Channel | Link |
|---------|------|
| **ByteMonk** *(Great for System Design & DSA)* | [youtube.com/@ByteMonk](https://www.youtube.com/@ByteMonk) |
| **Gaurav Sen** *(System Design in depth)* | [youtube.com/@gkcs](https://www.youtube.com/@gkcs) |
| **System Design Interview – An Insider's Guide** | [youtube.com/@SystemDesignInterview](https://www.youtube.com/@SystemDesignInterview) |
| **Exponent** *(System Design + Interview Prep)* | [youtube.com/@tryexponent](https://www.youtube.com/@tryexponent) |
| **Tech Dummies Narendra L** *(Distributed Systems)* | [youtube.com/@TechDummiesNarendraL](https://www.youtube.com/@TechDummiesNarendraL) |
| **Arpit Bhayani** *(Backend & System Design)* | [youtube.com/@AsliEngineering](https://www.youtube.com/@AsliEngineering) |
| **NeetCode** *(DSA + System Design)* | [youtube.com/@NeetCode](https://www.youtube.com/@NeetCode) |

### 🤖 AI / ML Deep Dives

| Channel | Link |
|---------|------|
| **Andrej Karpathy** *(Deep Learning, LLMs)* | [youtube.com/@AndrejKarpathy](https://www.youtube.com/@AndrejKarpathy) |
| **3Blue1Brown** *(Math & Neural Networks visually)* | [youtube.com/@3blue1brown](https://www.youtube.com/@3blue1brown) |
| **Yannic Kilcher** *(AI Research Paper Reviews)* | [youtube.com/@YannicKilcher](https://www.youtube.com/@YannicKilcher) |
| **Two Minute Papers** *(Latest AI Research)* | [youtube.com/@TwoMinutePapers](https://www.youtube.com/@TwoMinutePapers) |

---

## 📜 Must-Read System Design Papers
 
> Classic and influential research papers that shaped how modern large-scale systems are built. A great starting point for going beyond YouTube videos.
 
### 🗄️ Storage & Databases
 
| Paper | Organization | What it introduces | Link |
|-------|-------------|-------------------|------|
| **Dynamo: Amazon's Highly Available Key-Value Store** (2007) | Amazon | Eventually consistent KV store, consistent hashing, quorum reads/writes | [PDF](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf) |
| **Bigtable: A Distributed Storage System for Structured Data** (2006) | Google | Column-family storage model that inspired HBase & Cassandra | [PDF](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf) |
| **Cassandra: A Decentralized Structured Storage System** (2010) | Facebook | Combines Dynamo's distribution with Bigtable's data model | [PDF](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf) |
| **Spanner: Google's Globally Distributed Database** (2012) | Google | Globally consistent transactions using TrueTime | [PDF](https://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf) |
 
### ⚙️ Distributed Computing
 
| Paper | Organization | What it introduces | Link |
|-------|-------------|-------------------|------|
| **MapReduce: Simplified Data Processing on Large Clusters** (2004) | Google | Parallel batch processing model that spawned Hadoop | [PDF](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf) |
| **The Google File System** (2003) | Google | Fault-tolerant distributed file system; foundation of HDFS | [PDF](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf) |
| **Raft: In Search of an Understandable Consensus Algorithm** (2014) | Stanford | Easier-to-understand alternative to Paxos for consensus | [PDF](https://raft.github.io/raft.pdf) |
| **Paxos Made Simple** (2001) | Lamport | The original consensus algorithm used in distributed systems | [PDF](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf) |
| **Chubby: The Chubby Lock Service for Loosely-Coupled Distributed Systems** (2006) | Google | Distributed lock service; inspired Apache ZooKeeper | [PDF](https://static.googleusercontent.com/media/research.google.com/en//archive/chubby-osdi06.pdf) |
 
### 🔍 Search & Data Processing
 
| Paper | Organization | What it introduces | Link |
|-------|-------------|-------------------|------|
| **Dremel: Interactive Analysis of Web-Scale Datasets** (2010) | Google | Columnar storage + query execution (led to BigQuery) | [PDF](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36632.pdf) |
| **Kafka: A Distributed Messaging System for Log Processing** (2011) | LinkedIn | High-throughput, durable pub/sub messaging | [PDF](https://notes.stephenholiday.com/Kafka.pdf) |
| **Pregel: A System for Large-Scale Graph Processing** (2010) | Google | Vertex-centric model for distributed graph computation | [PDF](https://kowshik.github.io/JPregel/pregel-paper.pdf) |
 
### 🌐 Web-Scale Systems
 
| Paper | Organization | What it introduces | Link |
|-------|-------------|-------------------|------|
| **TAO: Facebook's Distributed Data Store for the Social Graph** (2013) | Facebook | Read-optimised graph data store at massive scale | [PDF](https://www.usenix.org/system/files/conference/atc13/atc13-bronson.pdf) |
| **Scaling Memcache at Facebook** (2013) | Facebook | How Facebook extended Memcached to serve billions of requests | [PDF](https://research.facebook.com/file/839620310074947/scaling-memcache-at-facebook.pdf) |
| **Dapper: A Large-Scale Distributed Systems Tracing Infrastructure** (2010) | Google | Distributed tracing; inspiration for Zipkin & Jaeger | [PDF](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36356.pdf) |
 
### 🤖 AI / ML Systems
 
| Paper | Organization | What it introduces | Link |
|-------|-------------|-------------------|------|
| **Attention Is All You Need** (2017) | Google Brain | The Transformer architecture powering all modern LLMs | [PDF](https://arxiv.org/pdf/1706.03762) |
| **BERT: Pre-training of Deep Bidirectional Transformers** (2018) | Google | Bidirectional pre-training for NLP tasks | [PDF](https://arxiv.org/pdf/1810.04805) |
| **GPT-3: Language Models are Few-Shot Learners** (2020) | OpenAI | Scaling laws and emergent abilities in large language models | [PDF](https://arxiv.org/pdf/2005.14165) |
 
> 💡 **Tip:** You don't need to understand every equation. Focus on the *motivation*, *design decisions*, and *trade-offs* each paper describes. That's what matters in system design.
 
---

## 📄 License

This repository is licensed under the [MIT License](LICENSE). Feel free to use, share, and build on it.

---

<div align="center">
Made with ❤️
<br/>
⭐ If you found this helpful, consider starring the repo!
</div>