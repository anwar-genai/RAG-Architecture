# RAG Architecture Canvas

![License](https://img.shields.io/badge/license-MIT-blue)
![Status](https://img.shields.io/badge/status-live-brightgreen)

An interactive, zoomable diagram of a production-grade RAG (Retrieval-Augmented Generation) 
pipeline — from ingestion through hybrid retrieval, reranking, generation, and the eval 
feedback loop that retunes chunking and retrieval config.

<!-- Replace the line below with the image GitHub generates when you drag-drop your screenshot/GIF -->
![RAG Architecture Canvas demo]
<img width="1912" height="972" alt="Screenshot 2026-09-15 152633" src="https://github.com/user-attachments/assets/e11a729c-b966-4cd9-ac9a-a5069ec37601" />

### 🔗 [Live Demo →](https://anwar-genai.github.io/RAG-Architecture/)

## What's inside
- Click any block to see what it does, typical stack, metrics to watch, and common failure modes
- Latency waterfall showing where time actually goes across the pipeline
- Dark/light theme toggle, zoomable canvas
- Built from patterns used across real RAG deployments (docs Q&A, customer support, code search)

## Why I built this
Most RAG explainers are static diagrams. This one is meant to be explored — the eval loop 
feeding back into chunking/embedding config is often the part people skip, and it's usually 
the difference between a demo and something that survives production.

## Stack
Single-file HTML/CSS/vanilla JS — no build step, no dependencies. Works anywhere static 
HTML can be hosted.
