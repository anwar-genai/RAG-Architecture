# RAG Architecture Canvas

An interactive, zoomable diagram of a production-grade RAG (Retrieval-Augmented Generation) 
pipeline — from ingestion through hybrid retrieval, reranking, generation, and the eval 
feedback loop that retunes chunking and retrieval config.

**[Live demo →](https://anwar-genai.github.io/RAG-Architecture/)**

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
