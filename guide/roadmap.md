# Roadmap

The journey is organized into twelve phases. Each phase starts from a guiding question or goal, then breaks the subject into concrete topics to study, implement, experiment with, and reflect on.

![Roadmap](../assets/roadmap.png)

## Phase 1 - Computer Fundamentals

**Priority:** High

**Goal:** Understand the machine before understanding machine intelligence.

### Topics

- **1.1 Binary & Number Representation**
- **1.2 Floating Point Numbers (IEEE 754 Basics)**
- **1.3 Memory Hierarchy**
  - Registers
  - Cache (L1/L2/L3)
  - RAM
  - Storage (SSD/HDD)
- **1.4 Memory Bandwidth & Latency**
- **1.5 CPU Architecture**
  - Cores
  - Threads
  - SIMD (High Level)
- **1.6 GPU Architecture**
  - CUDA Cores
  - Tensor Cores
  - GPU Memory
- **1.7 Parallel Computing**
  - Data Parallelism
  - Task Parallelism
- **1.8 Matrix Computation on Hardware**
- **1.9 Tensors**
- **1.10 Compute vs Memory Bound**
- **1.11 FLOPS (High Level)**
- **1.12 CPU vs GPU**
- **1.13 TPU, NPU & AI Accelerators (Overview)**
- **1.14 Why AI Needs GPUs**

## Phase 2 - Mathematical Language

**Goal:** Learn the language used to describe neural networks.

### Topics

- **2.1 Numbers & Functions**
- **2.2 Vectors**
- **2.3 Matrices**
- **2.4 Matrix Multiplication**
- **2.5 Dot Product**
- **2.6 Norm & Distance**
- **2.7 Linear Transformations**
- **2.8 Vector Spaces (High-Level Intuition)**
- **2.9 Probability**
- **2.10 Probability Distributions (Basic)**
- **2.11 Exponential Function (e^x)**
- **2.12 Softmax**
- **2.13 Derivatives (Intuition)**
- **2.14 Chain Rule (Intuition)**
- **2.15 Gradient**
- **2.16 Jacobian (High-Level Intuition)**

No proofs. No heavy calculus. Only intuition.

## Phase 3 - Information & Learning

**Question:** What is information and how can a machine learn from it?

### Information

- **3.1 What is Information?**
- **3.2 Information vs Data**
- **3.3 Information Theory (High-Level)**
- **3.4 Entropy**
- **3.5 Uncertainty**
- **3.6 Compression**
- **3.7 Prediction**
- **3.8 Signal vs Noise**

### Learning

- **3.9 What is Learning?**
- **3.10 Parameters**
- **3.11 Predictions**
- **3.12 Error (Loss)**
- **3.13 Cost Function**
- **3.14 Optimization**
- **3.15 Gradient Descent**
- **3.16 Learning Rate**
- **3.17 Backpropagation**
- **3.18 Bias vs Variance**
- **3.19 Overfitting**
- **3.20 Underfitting**
- **3.21 Generalization**
- **3.22 Training vs Validation vs Test**

## Phase 4 - Neural Networks

**Question:** Why aren't simple equations enough?

### Topics

- **4.1 Biological Inspiration (Why "Neural" Networks?)**
- **4.2 Perceptron**
- **4.3 Linear vs Non-Linear Problems**
- **4.4 Activation Functions**
- **4.5 Hidden Layers**
- **4.6 Multi-Layer Perceptron (MLP)**
- **4.7 Universal Approximation Theorem (High-Level Intuition)**
- **4.8 Forward Propagation**
- **4.9 Loss Propagation (Connecting to Backprop)**
- **4.10 Weight Initialization**
- **4.11 Vanishing & Exploding Gradients**
- **4.12 Normalization (High-Level)**
- **4.13 Model Capacity**
- **4.14 Underfitting vs Overfitting in Neural Networks**

## Phase 5 - Language Representation

**Question:** Computers don't understand words. How do they represent language?

### Topics

- **5.1 What is Language Representation?**
- **5.2 Tokens**
- **5.3 Tokenization**
- **5.4 Vocabulary**
- **5.5 One-hot Encoding**
- **5.6 Why One-hot Encoding Fails**
- **5.7 Subword Tokenization**
- **5.8 BPE**
- **5.9 SentencePiece (High-Level)**
- **5.10 Embeddings**
- **5.11 Embedding Space**
- **5.12 Semantic Similarity**
- **5.13 Contextual vs Static Embeddings**
- **5.14 Positional Representation (Why Word Order Matters)**
- **5.15 Output Embeddings**
- **5.16 Representation vs Meaning**

## Phase 6 - Sequence Modeling

**Question:** Language depends on previous words. How did AI solve this before Transformers?

### Topics

- **6.1 Why Context Matters**
- **6.2 Fixed vs Variable-Length Input**
- **6.3 Markov Models**
- **6.4 N-gram Language Models**
- **6.5 Hidden State (Memory)**
- **6.6 Recurrent Neural Networks (RNN)**
- **6.7 Backpropagation Through Time (High-Level)**
- **6.8 Long Short-Term Memory (LSTM)**
- **6.9 Gated Recurrent Unit (GRU) (High-Level)**
- **6.10 Teacher Forcing**
- **6.11 Autoregressive Prediction**
- **6.12 Exposure Bias**
- **6.13 Long-Term Dependency Problem**
- **6.14 Sequential Computation Bottleneck**
- **6.15 Why RNNs & LSTMs Fail**
- **6.16 What Should the Next Architecture Solve?**

## Phase 7 - Attention

**Question:** Why was Attention invented, and how does it allow a model to focus on the most relevant information?

### Topics

- **7.1 The Attention Problem**
  - Why remembering everything equally doesn't work
- **7.2 Selective Attention**
  - Learning to focus on relevant information
- **7.3 Query, Key & Value**
  - The intuition behind the attention mechanism
- **7.4 Attention Score**
  - Similarity using Dot Product
- **7.5 Scaled Dot-Product Attention**
  - Why scaling is necessary
- **7.6 Attention Weights**
  - From scores to probabilities (Softmax)
- **7.7 Self-Attention**
  - Words attending to other words
- **7.8 Multi-Head Attention**
  - Learning multiple relationships simultaneously
- **7.9 Positional Encoding**
  - Understanding word order
- **7.10 Masked Attention**
  - Preventing access to future tokens
- **7.11 Computational Complexity**
  - Why Attention is O(n^2)
- **7.12 Limitations of Attention**
  - Long-context challenges

## Phase 8 - Transformer

**Question:** How does GPT actually process information and generate intelligence?

### Topics

- **8.1 The Transformer Idea**
  - Why replace recurrence with attention?
- **8.2 Transformer Block**
  - The fundamental building block
- **8.3 Residual Connections**
  - Why deep networks need shortcuts
- **8.4 Layer Normalization**
  - Stabilizing learning
- **8.5 Feed Forward Network (MLP)**
  - Transforming representations
- **8.6 Putting One Transformer Block Together**
  - Complete data flow inside a block
- **8.7 Stacking Transformer Blocks**
  - How intelligence emerges with depth
- **8.8 Decoder-only Transformer**
  - Why GPT uses only the decoder
- **8.9 GPT Architecture**
  - From input tokens to next-token prediction
- **8.10 Parameter Scaling**
  - Why larger models perform better

## Phase 9 - Training

**Question:** How does GPT become intelligent through learning?

### Topics

- **9.1 Training Data**
  - Why data is the foundation
- **9.2 Token Prediction**
  - Learning by predicting the next token
- **9.3 Forward Pass**
  - From input to prediction
- **9.4 Loss Function**
  - Measuring prediction error
- **9.5 Cross Entropy Loss**
  - Why it is used for language modeling
- **9.6 Backward Pass**
  - Propagating error through the network
- **9.7 Gradient Descent**
  - Updating parameters
- **9.8 Adam Optimizer**
  - Adaptive optimization
- **9.9 Learning Rate & Scheduling**
  - Controlling the learning process
- **9.10 Batch & Mini-Batch Training**
- **9.11 Epochs**
- **9.12 Validation**
  - Measuring generalization during training
- **9.13 Mixed Precision Training**
- **9.14 Distributed Training**
- **9.15 Scaling Laws**
  - Data, Parameters and Compute

## Phase 10 - Inference

**Question:** How does GPT generate text one token at a time?

### Topics

- **10.1 The Inference Pipeline**
  - From prompt to generated text
- **10.2 Forward Pass**
  - Computing the next-token prediction
- **10.3 Logits**
  - Raw prediction scores
- **10.4 Softmax**
  - Converting scores into probabilities
- **10.5 Sampling vs Greedy Decoding**
  - Choosing the next token
- **10.6 Temperature**
  - Controlling randomness
- **10.7 Top-k Sampling**
- **10.8 Top-p (Nucleus) Sampling**
- **10.9 Beam Search**
  - When and why it is used
- **10.10 KV Cache**
  - Reusing previous computations
- **10.11 Quantization**
  - Faster inference with smaller models
- **10.12 Speculative Decoding**
  - Accelerating generation
- **10.13 Flash Attention**
  - Optimizing attention computation
- **10.14 Inference Trade-offs**
  - Speed vs Memory vs Quality

## Phase 11 - Modern LLM Systems

**Question:** How do modern LLMs become intelligent, interactive, and production-ready systems?

### Topics

- **11.1 Base Model vs Assistant**
  - Why a trained GPT is not yet a chatbot
- **11.2 Instruction Tuning**
  - Teaching models to follow instructions
- **11.3 RLHF**
  - Aligning models with human preferences
- **11.4 Retrieval-Augmented Generation (RAG)**
  - Learning vs Retrieving knowledge
- **11.5 Embedding Models**
  - Representing knowledge for retrieval
- **11.6 Vector Databases**
  - Efficient semantic search
- **11.7 Tool Calling**
  - Extending the model beyond language
- **11.8 AI Agents**
  - Planning, reasoning and executing tasks
- **11.9 Memory Systems**
  - Short-term vs Long-term memory
- **11.10 Long Context**
  - Scaling context windows
- **11.11 Mixture of Experts (MoE)**
  - Sparse computation at scale
- **11.12 Multimodal Models**
  - Text, Image, Audio and Video
- **11.13 Model Context Protocol (MCP)**
  - Standardizing tool and context integration
- **11.14 LLM System Architecture**
  - How all components work together

## Phase 12 - Build

**Goal:** Build a complete LLM and AI Assistant from scratch, one component at a time.

### Projects

- **12.1 Build a Tokenizer**
  - From raw text to tokens
- **12.2 Build an Embedding Layer**
  - Convert tokens into vectors
- **12.3 Build Self-Attention**
  - Implement Q, K, V from scratch
- **12.4 Build a Transformer Block**
  - Attention + MLP + Residual + LayerNorm
- **12.5 Build a Tiny Transformer**
  - Stack multiple transformer blocks
- **12.6 Build a Tiny GPT**
  - Complete autoregressive language model
- **12.7 Train Tiny GPT**
  - Train on a small custom dataset
- **12.8 Build an Inference Engine**
  - Token generation, sampling, KV Cache
- **12.9 Build an Instruction-Tuned Assistant**
  - Fine-tune for instruction following
- **12.10 Build a Tiny RAG System**
  - Embeddings + Vector DB + Retrieval
- **12.11 Build a Tiny AI Agent**
  - Memory + Tool Calling + Planning
- **12.12 Build a Production-Ready AI Assistant**
  - End-to-end capstone project
