# IULM AI Lab — Agentic Editorial System

An experimental agentic editorial workflow for the IULM AI Lab.

The project explores how AI agents, automation and retrieval systems can support an editorial team in discovering, filtering and evaluating relevant AI-related content while keeping humans in control of editorial decisions.

## Current MVP

The first version focuses on content ingestion and normalization:

RSS sources → n8n → normalized content

Each content item is converted into a common schema:

- title
- url
- source
- published_at
- content

## Planned architecture

n8n → LangGraph → RAG → Human Review

The system will progressively include content discovery, relevance evaluation, duplicate detection, retrieval, agent memory, research, verification and human-in-the-loop editorial review.

## Stack

n8n Community Edition  
Docker  
LangGraph / LangChain  
Python / FastAPI  
Ollama  
Chroma  
SQLite

## Status

Work in progress.
