# Youtube_Title_Gen_LLM
YouTube Title Generator with DPO Fine-tuning

A machine learning project that fine-tunes a language model using Direct Preference Optimization (DPO) to generate engaging YouTube video titles. The model learns to create compelling titles that are optimized for click-through rates and viewer engagement.

**Project Overview**
This project demonstrates how to:
- Fine-tune a pre-trained language model (Qwen2.5-0.5B-Instruct) using DPO
- Train the model to generate YouTube titles that follow specific guidelines (30-75 characters)
- Use preference learning to improve title quality based on human feedback data

**Key Features**
- Direct Preference Optimization (DPO): Uses preference learning to train the model on better vs. worse title examples
- Optimized for Engagement: Generates titles designed to maximize click-through rates
- Length Control: Ensures titles stay within YouTube's optimal character range (30-75 characters)
- Ready-to-use Pipeline: Includes text generation pipeline for immediate title generation

**Dataset**
- The project uses the shawhin/youtube-titles-dpo dataset, which contains:

**Video ideas/topics as prompts**
- Preferred and rejected title examples
- Training split: 1,026 examples
- Validation split: 114 examples

**Technical Stack**
- Framework: Hugging Face Transformers + TRL (Transformer Reinforcement Learning)
- Base Model: Qwen/Qwen2.5-0.5B-Instruct
- Training Method: Direct Preference Optimization (DPO)
- Hardware: GPU-accelerated training (CUDA)
- Monitoring: Weights & Biases integration

**Training Results**
- The model was trained for 3 epochs.
