# AI + Math Roadmap (2026)
## Goal: Build Deep Understanding of AI & Eventually Create LLM Systems

---

# Who This Roadmap Is For

This roadmap is designed for someone who:

- Already has programming experience
- Knows JavaScript well
- Has some Python experience
- Enjoys math
- Wants to deeply understand AI
- Wants to eventually build systems similar to ChatGPT

---

# Core Philosophy

Do NOT learn only theory.

The ideal loop is:

```text
Learn concept → Implement from scratch → Build project → Debug → Repeat
```

Understanding comes from:
- writing code
- seeing failures
- fixing models
- visualizing math

---

# BIG PICTURE ROADMAP

| Phase | Focus | Duration |
|---|---|---|
| 1 | Math Foundations | 1–2 months |
| 2 | ML From Scratch | 1 month |
| 3 | Deep Learning | 1 month |
| 4 | Transformers & NLP | 1–2 months |
| 5 | Tiny GPT Projects | 1 month |
| 6 | AI Apps & Systems | Ongoing |
| 7 | Advanced AI Research Topics | Long-term |

---

# PHASE 1 — Math Foundations

## Priority Order

1. Linear Algebra
2. Calculus
3. Probability & Statistics
4. Optimization

---

# 1. Linear Algebra (MOST IMPORTANT)

## Learn

- vectors
- matrices
- matrix multiplication
- dot products
- projections
- linear transformations
- eigenvectors/eigenvalues
- tensors

## Why It Matters

Neural networks and transformers are mostly giant matrix operations.

Embeddings, attention, image tensors, token representations — all are linear algebra.

## Resources

### Visual Intuition
https://www.3blue1brown.com/topics/linear-algebra

### Full Course
https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/

## Implement Yourself

Build using NumPy:

- matrix multiplication
- cosine similarity
- vector search
- simple embeddings search

---

# 2. Calculus for AI

## Learn

- derivatives
- partial derivatives
- gradients
- chain rule
- multivariable calculus basics

## Why It Matters

Training neural networks = optimization.

Backpropagation uses gradients.

## Resources

### Visual
https://www.3blue1brown.com/topics/calculus

### Practice
https://www.khanacademy.org/math/calculus-1

## Implement Yourself

- gradient descent manually
- optimize simple functions
- linear regression from scratch

---

# 3. Probability & Statistics

## Learn

- probability
- conditional probability
- expectation
- variance
- normal distribution
- softmax intuition
- entropy
- likelihood

## Why It Matters

LLMs predict probability distributions over tokens.

Machine learning fundamentally deals with uncertainty.

## Resources

https://www.youtube.com/@statquest

## Implement Yourself

- softmax
- cross entropy loss
- random sampling
- Bayesian intuition experiments

---

# 4. Optimization

## Learn

- gradient descent
- SGD
- Adam optimizer
- learning rates
- loss functions
- convexity basics

## Why It Matters

Optimization is how models improve.

---

# PHASE 2 — Machine Learning From Scratch

## Goal

Understand what frameworks automate.

Use ONLY:
- Python
- NumPy

NO PyTorch yet.

---

# Build These From Scratch

## Core Projects

- Linear Regression
- Logistic Regression
- Neural Network
- Backpropagation
- Gradient Descent

## Important Concepts

- train/test split
- overfitting
- regularization
- activation functions
- loss functions

---

# Resources

## Course
https://www.coursera.org/specializations/machine-learning-introduction

## Visualization
https://playground.tensorflow.org/

---

# PHASE 3 — Deep Learning Properly

## Learn PyTorch

Topics:

- tensors
- autograd
- nn.Module
- training loops
- optimizers
- datasets
- GPU training

---

# Resources

## Official Tutorials
https://pytorch.org/tutorials/

## Practical DL
https://course.fast.ai/

---

# Build Projects

## Computer Vision

- MNIST digit classifier
- image classifier

## NLP

- sentiment analyzer
- text classifier

## General

- recommendation system

---

# PHASE 4 — NLP + Transformers

This is the core step toward LLMs.

---

# Learn These Concepts Deeply

## NLP Basics

- tokenization
- embeddings
- sequence modeling

## Transformer Concepts

- attention
- self-attention
- Q/K/V matrices
- positional encoding
- multi-head attention
- transformer blocks

---

# MOST IMPORTANT RESOURCES

## Transformer Visualization
https://jalammar.github.io/illustrated-transformer/

## Original Transformer Paper
https://arxiv.org/abs/1706.03762

---

# PHASE 5 — Build a Tiny GPT

## Goal

Train and understand your own mini language model.

---

# Learn

- tokenizers
- embeddings
- transformer decoder architecture
- text generation
- sampling
- temperature
- inference

---

# BEST PROJECT

## nanoGPT
https://github.com/karpathy/nanoGPT

## Karpathy YouTube
https://www.youtube.com/@AndrejKarpathy

---

# PHASE 6 — Build AI Applications

Since you know JavaScript, this is a major advantage.

You can build:

- chatbots
- AI coding tools
- RAG systems
- document assistants
- browser AI apps
- voice AI systems

---

# Learn

## Backend

- FastAPI
- model serving
- embeddings APIs
- vector databases

## Frontend

- Next.js
- streaming UI
- AI chat interfaces

---

# Useful Tools

## Frontend / Fullstack

https://nextjs.org/
https://sdk.vercel.ai/

## AI Frameworks

https://www.langchain.com/
https://huggingface.co/learn

---

# Build These Projects

## Beginner

- PDF chatbot
- summarizer
- AI search app

## Intermediate

- coding assistant
- AI tutor
- research assistant

## Advanced

- multi-agent systems
- local LLM app
- voice assistant

---

# PHASE 7 — Advanced AI Topics

Long-term topics:

- distributed training
- CUDA basics
- quantization
- RLHF
- scaling laws
- diffusion models
- multimodal models
- inference optimization

---

# Learn to Read Papers

## Start Here
https://arxiv.org/list/cs.AI/recent

## Read Slowly

You do NOT need to understand everything immediately.

Focus on:
- architecture
- intuition
- diagrams
- experiments

---

# Recommended People to Learn From

## Andrej Karpathy
Focus:
- transformers
- GPTs
- implementation intuition

## Andrew Ng
Focus:
- ML foundations

## Grant Sanderson (3Blue1Brown)
Focus:
- math intuition

## Jeremy Howard
Focus:
- practical deep learning

---

# Daily Study Structure

## If Studying 3–4 Hours Daily

### 1 hour
Math

### 1 hour
Implementation

### 1 hour
Projects

### 30 mins
Reading papers/videos

---

# Weekly Goals

Every week:

- finish one mini-project
- implement one concept manually
- read one technical article/paper
- push code to GitHub

---

# Important Mindset Rules

## 1. Implement Everything Once

Even if frameworks already exist.

---

## 2. Build Continuously

Projects create intuition.

---

## 3. Debugging Is Learning

Training instability teaches a lot.

---

## 4. Don’t Wait Until “Ready”

Build early.

---

# Suggested 6-Month Focus Plan

## Month 1
- Linear algebra
- NumPy
- vectors/matrices

## Month 2
- calculus
- probability
- optimization

## Month 3
- neural nets from scratch
- backpropagation

## Month 4
- PyTorch
- train image/text models

## Month 5
- transformers
- attention math
- embeddings

## Month 6
- nanoGPT
- chatbot app
- RAG systems

---

# End Goal

After ~1 year of consistent work, you should be able to:

- understand transformers
- train neural networks
- fine-tune LLMs
- build AI products
- read AI papers
- implement architectures yourself
- contribute to advanced AI projects

---

# Final Advice

The strongest AI engineers usually combine:

- math intuition
- systems thinking
- coding ability
- experimentation
- persistence

The real learning loop is:

```text
Learn → Build → Fail → Debug → Understand → Repeat
```