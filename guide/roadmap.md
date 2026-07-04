# Roadmap

The journey is organized into thirteen phases. Each phase starts from a guiding question or goal, then breaks the subject into concrete topics to study, implement, experiment with, and reflect on.

![Roadmap](../assets/roadmap.png)

## Phase 1 - Information Foundations

**Priority:** Highest

**Goal:** Understand what information is before learning how machines represent and manipulate it.

### Topics

- **0.1 What is Information?**
- **0.2 Representation**
- **0.3 Encoding**
- **0.4 Compression**
- **0.5 Entropy (Intuition)**
- **0.6 Computation as Information Transformation**

## Phase 2 - Computer Fundamentals

**Priority:** High

**Goal:** Understand the machine before understanding machine intelligence.

### Topics

- **2.1 Binary & Number Representation**
- **2.2 Floating Point Numbers (IEEE 754 Basics)**
- **2.3 Memory Hierarchy**
  - Registers
  - Cache (L1/L2/L3)
  - RAM
  - Storage (SSD/HDD)
- **2.4 Memory Bandwidth & Latency**
- **2.5 CPU Architecture**
  - Cores
  - Threads
  - SIMD (High Level)
- **2.6 GPU Architecture**
  - CUDA Cores
  - Tensor Cores
  - GPU Memory
- **2.7 Parallel Computing**
  - Data Parallelism
  - Task Parallelism
- **2.8 Matrix Computation on Hardware**
- **2.9 Tensors**
- **2.10 Compute vs Memory Bound**
- **2.11 FLOPS (High Level)**
- **2.12 CPU vs GPU**
- **2.13 TPU, NPU & AI Accelerators (Overview)**
- **2.14 Why AI Needs GPUs**

## Phase 3 - Mathematical Language

**Goal:** Learn the language used to describe neural networks.

### Topics

- **3.1 Numbers & Functions**
- **3.2 Vectors**
- **3.3 Matrices**
- **3.4 Matrix Multiplication**
- **3.5 Dot Product**
- **3.6 Norm & Distance**
- **3.7 Linear Transformations**
- **3.8 Vector Spaces (High-Level Intuition)**
- **3.9 Probability**
- **3.10 Probability Distributions (Basic)**
- **3.11 Exponential Function (e^x)**
- **3.12 Softmax**
- **3.13 Derivatives (Intuition)**
- **3.14 Chain Rule (Intuition)**
- **3.15 Gradient**
- **3.16 Jacobian (High-Level Intuition)**

No proofs. No heavy calculus. Only intuition.

## Phase 4 - Information & Learning

**Question:** What is information and how can a machine learn from it?

### Information

- **4.1 What is Information?**
- **4.2 Information vs Data**
- **4.3 Information Theory (High-Level)**
- **4.4 Entropy**
- **4.5 Uncertainty**
- **4.6 Compression**
- **4.7 Prediction**
- **4.8 Signal vs Noise**

### Learning

- **4.9 What is Learning?**
- **4.10 Parameters**
- **4.11 Predictions**
- **4.12 Error (Loss)**
- **4.13 Cost Function**
- **4.14 Optimization**
- **4.15 Gradient Descent**
- **4.16 Learning Rate**
- **4.17 Backpropagation**
- **4.18 Bias vs Variance**
- **4.19 Overfitting**
- **4.20 Underfitting**
- **4.21 Generalization**
- **4.22 Training vs Validation vs Test**

## Phase 5 - Neural Networks

**Question:** Why aren't simple equations enough?

### Topics

- **5.1 Biological Inspiration (Why "Neural" Networks?)**
- **5.2 Perceptron**
- **5.3 Linear vs Non-Linear Problems**
- **5.4 Activation Functions**
- **5.5 Hidden Layers**
- **5.6 Multi-Layer Perceptron (MLP)**
- **5.7 Universal Approximation Theorem (High-Level Intuition)**
- **5.8 Forward Propagation**
- **5.9 Loss Propagation (Connecting to Backprop)**
- **5.10 Weight Initialization**
- **5.11 Vanishing & Exploding Gradients**
- **5.12 Normalization (High-Level)**
- **5.13 Model Capacity**
- **5.14 Underfitting vs Overfitting in Neural Networks**

## Phase 6 - Language Representation

**Question:** Computers don't understand words. How do they represent language?

### Topics

- **6.1 What is Language Representation?**
- **6.2 Tokens**
- **6.3 Tokenization**
- **6.4 Vocabulary**
- **6.5 One-hot Encoding**
- **6.6 Why One-hot Encoding Fails**
- **6.7 Subword Tokenization**
- **6.8 BPE**
- **6.9 SentencePiece (High-Level)**
- **6.10 Embeddings**
- **6.11 Embedding Space**
- **6.12 Semantic Similarity**
- **6.13 Contextual vs Static Embeddings**
- **6.14 Positional Representation (Why Word Order Matters)**
- **6.15 Output Embeddings**
- **6.16 Representation vs Meaning**

## Phase 7 - Sequence Modeling

**Question:** Language depends on previous words. How did AI solve this before Transformers?

### Topics

- **7.1 Why Context Matters**
- **7.2 Fixed vs Variable-Length Input**
- **7.3 Markov Models**
- **7.4 N-gram Language Models**
- **7.5 Hidden State (Memory)**
- **7.6 Recurrent Neural Networks (RNN)**
- **7.7 Backpropagation Through Time (High-Level)**
- **7.8 Long Short-Term Memory (LSTM)**
- **7.9 Gated Recurrent Unit (GRU) (High-Level)**
- **7.10 Teacher Forcing**
- **7.11 Autoregressive Prediction**
- **7.12 Exposure Bias**
- **7.13 Long-Term Dependency Problem**
- **7.14 Sequential Computation Bottleneck**
- **7.15 Why RNNs & LSTMs Fail**
- **7.16 What Should the Next Architecture Solve?**

## Phase 8 - Attention

**Question:** Why was Attention invented, and how does it allow a model to focus on the most relevant information?

### Topics

- **8.1 The Attention Problem**
  - Why remembering everything equally doesn't work
- **8.2 Selective Attention**
  - Learning to focus on relevant information
- **8.3 Query, Key & Value**
  - The intuition behind the attention mechanism
- **8.4 Attention Score**
  - Similarity using Dot Product
- **8.5 Scaled Dot-Product Attention**
  - Why scaling is necessary
- **8.6 Attention Weights**
  - From scores to probabilities (Softmax)
- **8.7 Self-Attention**
  - Words attending to other words
- **8.8 Multi-Head Attention**
  - Learning multiple relationships simultaneously
- **8.9 Positional Encoding**
  - Understanding word order
- **8.10 Masked Attention**
  - Preventing access to future tokens
- **8.11 Computational Complexity**
  - Why Attention is O(n^2)
- **8.12 Limitations of Attention**
  - Long-context challenges

## Phase 9 - Transformer

**Question:** How does GPT actually process information and generate intelligence?

### Topics

- **9.1 The Transformer Idea**
  - Why replace recurrence with attention?
- **9.2 Transformer Block**
  - The fundamental building block
- **9.3 Residual Connections**
  - Why deep networks need shortcuts
- **9.4 Layer Normalization**
  - Stabilizing learning
- **9.5 Feed Forward Network (MLP)**
  - Transforming representations
- **9.6 Putting One Transformer Block Together**
  - Complete data flow inside a block
- **9.7 Stacking Transformer Blocks**
  - How intelligence emerges with depth
- **9.8 Decoder-only Transformer**
  - Why GPT uses only the decoder
- **9.9 GPT Architecture**
  - From input tokens to next-token prediction
- **9.10 Parameter Scaling**
  - Why larger models perform better

## Phase 10 - Training

**Question:** How does GPT become intelligent through learning?

### Topics

- **10.1 Training Data**
  - Why data is the foundation
- **10.2 Token Prediction**
  - Learning by predicting the next token
- **10.3 Forward Pass**
  - From input to prediction
- **10.4 Loss Function**
  - Measuring prediction error
- **10.5 Cross Entropy Loss**
  - Why it is used for language modeling
- **10.6 Backward Pass**
  - Propagating error through the network
- **10.7 Gradient Descent**
  - Updating parameters
- **10.8 Adam Optimizer**
  - Adaptive optimization
- **10.9 Learning Rate & Scheduling**
  - Controlling the learning process
- **10.10 Batch & Mini-Batch Training**
- **10.11 Epochs**
- **10.12 Validation**
  - Measuring generalization during training
- **10.13 Mixed Precision Training**
- **10.14 Distributed Training**
- **10.15 Scaling Laws**
  - Data, Parameters and Compute

## Phase 11 - Inference

**Question:** How does GPT generate text one token at a time?

### Topics

- **11.1 The Inference Pipeline**
  - From prompt to generated text
- **11.2 Forward Pass**
  - Computing the next-token prediction
- **11.3 Logits**
  - Raw prediction scores
- **11.4 Softmax**
  - Converting scores into probabilities
- **11.5 Sampling vs Greedy Decoding**
  - Choosing the next token
- **11.6 Temperature**
  - Controlling randomness
- **11.7 Top-k Sampling**
- **11.8 Top-p (Nucleus) Sampling**
- **11.9 Beam Search**
  - When and why it is used
- **11.10 KV Cache**
  - Reusing previous computations
- **11.11 Quantization**
  - Faster inference with smaller models
- **11.12 Speculative Decoding**
  - Accelerating generation
- **11.13 Flash Attention**
  - Optimizing attention computation
- **11.14 Inference Trade-offs**
  - Speed vs Memory vs Quality

## Phase 12 - Modern LLM Systems

**Question:** How do modern LLMs become intelligent, interactive, and production-ready systems?

### Topics

- **12.1 Base Model vs Assistant**
  - Why a trained GPT is not yet a chatbot
- **12.2 Instruction Tuning**
  - Teaching models to follow instructions
- **12.3 RLHF**
  - Aligning models with human preferences
- **12.4 Retrieval-Augmented Generation (RAG)**
  - Learning vs Retrieving knowledge
- **12.5 Embedding Models**
  - Representing knowledge for retrieval
- **12.6 Vector Databases**
  - Efficient semantic search
- **12.7 Tool Calling**
  - Extending the model beyond language
- **12.8 AI Agents**
  - Planning, reasoning and executing tasks
- **12.9 Memory Systems**
  - Short-term vs Long-term memory
- **12.10 Long Context**
  - Scaling context windows
- **12.11 Mixture of Experts (MoE)**
  - Sparse computation at scale
- **12.12 Multimodal Models**
  - Text, Image, Audio and Video
- **12.13 Model Context Protocol (MCP)**
  - Standardizing tool and context integration
- **12.14 LLM System Architecture**
  - How all components work together

## Phase 13 - Build

**Goal:** Build a complete LLM and AI Assistant from scratch, one component at a time.

### Projects

- **13.1 Build a Tokenizer**
  - From raw text to tokens
- **13.2 Build an Embedding Layer**
  - Convert tokens into vectors
- **13.3 Build Self-Attention**
  - Implement Q, K, V from scratch
- **13.4 Build a Transformer Block**
  - Attention + MLP + Residual + LayerNorm
- **13.5 Build a Tiny Transformer**
  - Stack multiple transformer blocks
- **13.6 Build a Tiny GPT**
  - Complete autoregressive language model
- **13.7 Train Tiny GPT**
  - Train on a small custom dataset
- **13.8 Build an Inference Engine**
  - Token generation, sampling, KV Cache
- **13.9 Build an Instruction-Tuned Assistant**
  - Fine-tune for instruction following
- **13.10 Build a Tiny RAG System**
  - Embeddings + Vector DB + Retrieval
- **13.11 Build a Tiny AI Agent**
  - Memory + Tool Calling + Planning
- **13.12 Build a Production-Ready AI Assistant**
  - End-to-end capstone project
