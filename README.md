# RankGemma3
A novel dual-stage training paradigm for transformer-based document reranking that combines explanation-driven pre-training with efficient listwise optimization.
![explanation_generation_visual](https://github.com/user-attachments/assets/20588879-c0f5-4e1d-80ff-2b7ba6e12d66)

🚀 What Makes This Special?
This project introduces a groundbreaking approach to information retrieval by training transformer models to not just rank documents, but to understand and explain why they are relevant. The system achieves state-of-the-art performance while maintaining computational efficiency and providing interpretable results.
✨ Key Innovations
🧠 Explainable AI Integration - First reranking system to generate natural language explanations during training
⚡ Efficient Listwise Ranking - Single forward pass ranking using first-token logits
🎯 Dual-Objective Learning - Combines ranking accuracy with semantic representation quality
📊 Parameter Efficiency - 70% reduction in trainable parameters without performance loss

![two_stage_reranking_diagram](https://github.com/user-attachments/assets/87cb60c2-4d6f-4cb4-b99b-fbfee31a584d)

CPT Model 
https://huggingface.co/neelbanodiya/gemmaCPT

Our Synthetic Dataset 
https://huggingface.co/datasets/neelbanodiya/sft_dataset
