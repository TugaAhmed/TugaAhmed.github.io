---
title: "GNN-CB: A Graph Neural Network Competition Benchmark for Human and LLM Evaluation"
collection: publications
category: conferences
permalink: /publication/gnn_bench
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2026-10-25 
venue: 'EMNLP' 
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
<a href="https://aclanthology.org/2026.emnlp-main.1762/" target="_blank" style="display: inline-block; padding: 6px 12px; background-color: #566883; color: white; text-decoration: none; border-radius: 4px;">LINK</a>



**Abstract**  
Large language models (LLMs) have demonstrated strong performance on coding and reasoning benchmarks; however, their ability to solve graph-structured machine learning problems remains largely unexplored. In particular, no benchmark currently evaluates whether LLMs can autonomously solve end-to-end Graph Neural Network (GNN) coding tasks under realistic competition settings. To address this gap, this paper introduces GNNCB, the first competition-based benchmark for evaluating both humans and LLMs on GNN coding tasks. GNN-CB consists of 18 curated competitions spanning node-, edge-, and graph-level prediction across diverse graph categories, domains, and difficulty tiers. All submissions are evaluated through a unified automated pipeline with hidden test sets and standardized scoring. Human participants solve tasks under controlled competition constraints, while LLMs are evaluated using a frozen zero-shot prompting protocol based on a planthen-code paradigm with bounded execute-andrepair loops. The benchmark additionally supports both non-agent and autonomous agentbased evaluation within the same protocol. Under our evaluated protocol, LLMs rarely match Human Top performance and show less stable performance across competitions. No single model dominates: a few competitions are won by LLMs, yet humans still hold the top score on most tasks. We release GNN-CB as a living benchmark with automated evaluation infrastructure, dynamic leaderboards, and reproducible execution pipelines. Beyond benchmarking, GNN-CB provides a practiceoriented resource for studying GNN implementation across progressively diverse graphlearning tasks. The benchmark and evaluation framework are publicly available at [https://basiralab.github.io/GNN-CB/](https://basiralab.github.io/GNN-CB/).