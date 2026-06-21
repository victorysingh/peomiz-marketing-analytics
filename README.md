# GEO/AIO Search Analytics Engine

## Overview

The GEO/AIO Search Analytics Engine is a platform designed to measure and analyze brand visibility across AI-powered search and recommendation systems such as ChatGPT, Gemini, and Claude.

As AI-driven discovery becomes increasingly important, businesses need new analytics frameworks to understand how often they are recommended, how they compare against competitors, and how their visibility changes over time.

This project helps organizations track AI-generated brand mentions, benchmark competitors, calculate visibility scores, and generate actionable Generative Engine Optimization (GEO) insights.

---

## Problem Statement

Traditional SEO tools focus on search engines like Google and Bing but do not provide visibility into Large Language Models (LLMs).

Organizations currently lack the ability to:

* Track AI-generated brand mentions
* Compare visibility against competitors
* Monitor recommendation frequency
* Measure AI discovery performance
* Generate GEO optimization insights

---

## Objectives

* Measure brand visibility across AI platforms
* Benchmark competitors
* Track recommendation frequency
* Analyze mention positions
* Generate visibility scores
* Provide GEO-focused recommendations

---

## Core Features

### Prompt Management System

Organize and manage prompts by category:

* Service-Based Prompts
* Hyperlocal Prompts
* Competitive Prompts

Stored fields include:

* Prompt ID
* Category
* Service Type
* Location

---

### Automated LLM Query Pipeline

Supported Models:

* ChatGPT
* Google Gemini
* Anthropic Claude

Functions:

* Prompt execution
* Response collection
* Execution logging
* Retry handling
* API monitoring

---

### Mention Detection Engine

Detect:

* Peomiz mentions
* Competitor mentions

Output:

* Mention Status
* Competitor Presence
* Recommendation Position

---

### Sentiment Analysis

MVP uses a lightweight rule-based sentiment model.

Categories:

* Positive
* Neutral
* Negative

---

### Visibility Scoring System

Visibility Score is calculated using:

Visibility Score =
Mention Weight × Position Weight × Sentiment Weight

Factors:

* Mention occurrence
* Ranking position
* Sentiment polarity

---

### Analytics Dashboard

Provides:

* Mention Rate
* Visibility Score
* Competitor Benchmarking
* Daily Trends
* Weekly Trends
* GEO Insights

---

## Technical Architecture

Prompt Management
↓
LLM Query Pipeline
↓
Response Collection
↓
Mention Detection
↓
Visibility Scoring
↓
Analytics Dashboard

---

## Technology Stack

### Backend

* Python
* FastAPI

### Database

* PostgreSQL

### Processing

* Pandas
* Regex
* NLP Utilities

### Dashboard

* Streamlit

### AI Integrations

* OpenAI API
* Google Gemini API
* Anthropic Claude API

---

## Project Structure

```text
geo-aio-search-analytics/
│
├── prompts/
├── pipeline/
├── mention_detection/
├── scoring/
├── database/
├── dashboard/
├── reports/
├── docs/
└── README.md
```

## Success Metrics

### Business Metrics

* Daily AI visibility tracking
* Competitor benchmarking
* Historical reporting
* GEO recommendations

### Operational Metrics

* 90%+ successful pipeline execution
* 95%+ response collection rate
* Automated visibility monitoring

---

## Future Enhancements

* Advanced NLP analysis
* ML-based sentiment analysis
* Additional LLM integrations
* Real-time monitoring
* Enterprise dashboard
* Multi-brand support

---

## Author

**Jaipreet Singh**

Project: Programmatic SEO & Micro-Market Analytics

Internship Project – GEO/AIO Search Analytics Engine
