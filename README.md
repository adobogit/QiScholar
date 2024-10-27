# QiScholar (LLM X Quantum Computing)
Smarter Paper Discovery with Quantum Computing 
(Better than Google Scholar)

## Overview ##

Finding the right academic paper for research can be challenging. Unlike traditional search engines that rank content based on traffic and recency, academic papers require a more sophisticated approach. Citation counts can indicate relevance, but for newer papers, it’s often not enough. QiScholar addresses these limitations by combining Large Language Models (LLMs) with the processing power of Quantum Computing.

## Key Features ##
Contextual Query Analysis with LLM
QiScholar uses an LLM to understand the context of search queries, identifying related terms and synonyms to capture the full meaning. This allows for a broader, more inclusive search, ensuring relevant papers aren’t missed due to slight variations in phrasing.

### Quantum-Enhanced Search with Grover’s Algorithm
The search process then passes to the Quantum Computer, where Grover’s Algorithm performs an efficient search through the database, amplifying the probability of the most relevant papers:

### Oracle Marking: Grover’s Oracle marks specific states representing papers that align with the LLM-processed query.
Amplitude Amplification: Grover’s Diffusion Operator amplifies these marked states, making them more likely to appear as results, significantly improving search efficiency.

## Team Member
Faye Simon

## Disclaimer: This repository contains two versions of the code:
QiScholar – A version focused on demonstrating optimization concepts using quantum computing.
(In Progress) Database x LLM x Qiskit – An incomplete version aimed at integrating a paper database with LLM (via oLlama API) and Qiskit.
