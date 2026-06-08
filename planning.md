# Project 1 Planning: The Unofficial Guide

> Write this document before you write any pipeline code.
- Data Structures and Algorithms. Rate Data Structure and Algorthms to passing coding interviews for Software Engineering graduates
- Identify at least 10 specific source documents
> Your spec and architecture diagram are what you'll use to direct AI tools (Claude, Copilot, etc.) to generate your implementation — the more specific they are, the more useful the generated code will be.
> Update the Retrieval Approach and Chunking Strategy sections if you change your approach during implementation.
> Update this file before starting any stretch features.

---

## Domain

<!-- What domain did you choose? Why is this knowledge valuable and hard to find through official channels? -->
- Data Structures and Algorithms. Rate Data Structure and Algorthms to passing coding interviews for Software Engineering graduates
- There is no specific guide on applicable Data structures and algorithms to pass coding interviews.
---

## Documents

<!-- List your specific sources: URLs, subreddit names, forum threads, or file descriptions.
     Aim for at least 10 sources that together cover different subtopics or perspectives within your domain. -->

| # | Source | Description | URL or location |
|---|--------|-------------|-----------------|
| 1 |LeetCode — Top Interview Questions |curated list of high-frequency interview problems | https://leetcode.com/problemset/top-interview-questions/ |
| 2 |Introduction to Algorithms (CLRS) — MIT Press book page |canonical, deep textbook for theory and proofs (use selectively for interviews) | https://mitpress.mit.edu/9780262046305/introduction-to-algorithms/|
| 3 | Princeton Algorithms, 4th Ed. (Sedgewick & Wayne) — algs4 site| clear implementations, visualizations, and exercises | https://algs4.cs.princeton.edu/|
| 4 | HackerRank — Interview Preparation Kit| structured practice tracks with company-style problems| https://www.hackerrank.com/interview/interview-preparation-kit |
| 5 | GeeksforGeeks — Top 50 Dynamic Programming Problems | targeted practice for a common interview weak spot | https://www.geeksforgeeks.org/top-50-dynamic-programming-problems/ |
| 6 | GeeksforGeeks — Data Structures overview | extensive discrete-topic articles | https://www.geeksforgeeks.org/data-structures/|
| 7 | TopCoder — Competitive Programming Tutorials | algorithm techniques and practice useful for hard interview problems | https://www.topcoder.com/community/competitive-programming/tutorials/|
| 8 | Stack Overflow thread - Best way to prepare for technical interviews | community strategies and real-world tips; good for meta-prep| https://stackoverflow.com/questions/12451835/best-way-to-prepare-for-technical-interviews |
| 9 | Cracking the Coding Interview | interview-focused book with curated questions and behavioral advice| https://www.crackingthecodinginterview.com/ |
| 10 | Elements of Programming Interviews (EPI) |problem sets and solutions styled for interview difficulty | https://elementsofprogramminginterviews.com/|

---

## Chunking Strategy

<!-- How will you split documents into chunks?
     State your chunk size (in tokens or characters), overlap size, and explain why those
     numbers fit the structure of your documents.
     A review-heavy corpus warrants different chunking than a long FAQ. -->

**Chunk size:** tokens

**Overlap:**

**Reasoning:** Because it is one focused domain ** Recursive strategy

---

## Retrieval Approach

<!-- Which embedding model are you using (e.g., all-MiniLM-L6-v2 via sentence-transformers)?
     How many chunks will you retrieve per query (top-k)?
     If you were deploying this for real users and cost wasn't a constraint, what tradeoffs
     would you weigh in choosing a different embedding model — context length, multilingual
     support, accuracy on domain-specific text, latency? -->

**Embedding model:**  accuracy on domain-specific text **ChromaDB

**Top-k:** 5

**Production tradeoff reflection:** 

---

## Evaluation Plan

<!-- List your 5 test questions with their expected correct answers.
     Questions should be specific enough that you can judge whether the system's response
     is right or wrong. "What are good dining halls?" is too vague.
     "What do students say about wait times at [dining hall name] during lunch?" is testable. -->

| # | Question | Expected answer |
|---|----------|-----------------|
| 1 | | |
| 2 | | |
| 3 | | |
| 4 | | |
| 5 | | |

---

## Anticipated Challenges

<!-- What could go wrong? Name at least two specific risks with reasoning.
     Consider: noisy or inconsistent documents, missing source attribution, off-topic
     retrieval, chunks that split key information across boundaries. -->

1.

2.

---

## Architecture

<!-- Draw a diagram of your pipeline showing the five stages:
     Document Ingestion → Chunking → Embedding + Vector Store → Retrieval → Generation
     Label each stage with the tool or library you're using.
     You can use ASCII art, a Mermaid diagram, or embed a sketch as an image.
     You'll use this diagram as context when prompting AI tools to implement each stage. -->

---

## AI Tool Plan

<!-- For each part of the pipeline below, describe:
     - Which AI tool you plan to use (Claude, Copilot, ChatGPT, etc.)
     - What you'll give it as input (which sections of this planning.md, which requirements)
     - What you expect it to produce
     - How you'll verify the output matches your spec

     "I'll use AI to help me code" is not a plan.
     "I'll give Claude my Chunking Strategy section and ask it to implement chunk_text()
     with my specified chunk size and overlap" is a plan. -->

**Milestone 3 — Ingestion and chunking:**

**Milestone 4 — Embedding and retrieval:**

**Milestone 5 — Generation and interface:**
