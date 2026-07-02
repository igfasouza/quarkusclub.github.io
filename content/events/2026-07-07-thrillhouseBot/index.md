---
title: "ThrillhouseBot: How I Built My Own AI PR Reviewer with Quarkus and LangChain4j"
layout: event
date: 2026-07-07 13:00:00 -0300
youtubeLive: https://www.youtube.com/watch?v=2A1cwVwEfnM
description: | 
    I got tired of watching AI code review prices climb while having less and less say over which model reviewed my code and where it ran, so I built my own. ThrillhouseBot is a self-hosted AI pull request reviewer written in Java 25 and Quarkus, wired to LLMs through LangChain4j and compiled to a GraalVM native image: you bring your own key, point it at your repos, and pick whatever model fits your budget. In this talk I walk through the whole thing, from the itch that started it to a tool I now use every day. I will cover why I picked Quarkus and LangChain4j over the obvious alternatives, how the bot runs a full review in a single LLM call, and the architecture trade-offs along the way, like choosing Postgres with pgvector to leave the door open for memory later. I will also be honest about how I leaned on AI to build the bot itself, where it helped and where it got in the way, and how I kept quality high with tests, dogfooding, and a healthy distrust of anything generated.
speakers: [thiagoGonzaga]
language: en-GB
draft: false
---