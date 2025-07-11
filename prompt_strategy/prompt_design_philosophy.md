# ✍️ Prompt Design Philosophy – Crafting Prompts for Red Teaming

## Overview
Effective red teaming requires not just creative prompts, but strategic ones — crafted to subtly challenge, confuse, or bypass LLM guardrails. This document outlines the principles used to design high-impact prompts that uncover model weaknesses.

## Principles Followed

### 1. 🎭 Role Manipulation
Frame the model as two conflicting personas (e.g., safety moderator + rogue AI) to create internal confusion.

### 2. 🧠 Memory Traps
Ask indirect questions about earlier parts of the conversation to test how much context the model truly retains.

### 3. 💬 Tone-Based Triggers
Use sarcasm, extreme politeness, or emotional tones to soften model responses or bypass filters.

### 4. 📚 Layered Context
Build multi-step prompts that seem innocent at first, but introduce ambiguity or risk deeper into the chain.

### 5. 🪞 Meta Reflection
Ask the model about its own decision-making process, refusal logic, or internal filters — to expose the rules it follows.

## Red Team Insight
Prompt writing is not about tricking the model with keywords — it's about understanding how LLMs "think" and pushing their interpretive limits through careful prompt layering and intent redirection.

## Tags
`#prompt_engineering` `#llm_testing` `#red_team_prompt_style`
