# Level 5 Gateway Challenge — Deep Learning & AI

> **Beacon Innovation Hub — Data Scientist Learning Path**

**Level:** 5 — Deep Learning & AI  
**Challenge Type:** Level Advancement  
**Next Level:** Level 6 — MLOps

---

## Challenge Overview

You have completed the core learning material for **Deep Learning and AI**.

This gateway challenge evaluates whether you can move beyond following tutorials and independently design, train, evaluate and defend an AI solution.

The challenge focuses on four areas:

1. Neural Networks
2. Computer Vision & Transfer Learning
3. NLP & Transformers
4. Generative AI & Retrieval

You will complete four practical challenges followed by one **Level 5 Gateway Project**.

> The goal is not to build the most complicated AI system.
> The goal is to demonstrate that you understand when, why and how
> advanced AI methods should be used.

---

# Challenge 1 — Neural Network Investigation

## Scenario

Beacon Innovation Hub has access to structured historical project data.

Previous Data Scientists have already investigated the dataset using
classical Machine Learning.

BIH now wants to determine whether a neural network provides enough
improvement to justify its additional complexity.

---

## Your Task

Develop a neural network for an appropriate prediction problem.

You must demonstrate:

- [ ] Data preparation
- [ ] Conversion of data to tensors
- [ ] Dataset handling
- [ ] DataLoader usage
- [ ] Neural-network architecture
- [ ] Activation functions
- [ ] Appropriate loss function
- [ ] Optimizer selection
- [ ] Forward propagation
- [ ] Backpropagation
- [ ] Training loop
- [ ] Validation loop
- [ ] Learning curves
- [ ] Overfitting investigation
- [ ] Final test evaluation

---

## Required Comparison

Your investigation must compare:

```text
Simple Baseline
      ↓
Classical ML Model
      ↓
Neural Network
```

Use the **same prediction problem and comparable evaluation metrics**.

---

## Architecture Investigation

Experiment with at least two architectural or training choices.

For example:

- Number of hidden layers
- Number of neurons
- Learning rate
- Batch size
- Activation function
- Optimizer
- Dropout

Do not change everything simultaneously.

Document what was changed and why.

---

## Training Investigation

Plot:

- Training loss
- Validation loss

Where appropriate, also plot:

- Training metric
- Validation metric

Then investigate:

> Is the model learning, underfitting or overfitting?

---

## Questions

Answer:

1. Did the neural network outperform the baseline?
2. Did it outperform the classical ML model?
3. How did training and validation loss change?
4. Was there evidence of overfitting?
5. Which architecture performed best?
6. What computational cost was introduced?
7. Is the neural network justified for this problem?

---

## Required Evidence

```text
challenge-01-neural-network/
│
├── README.md
├── neural-network.ipynb
├── figures/
└── findings.md
```

---

# Challenge 2 — Computer Vision & Transfer Learning

## Scenario

Mr P.G. Marapira and Mr A.N.N. Sibisi are developing an intelligent
e-commerce system.

They want to investigate whether product images could automatically
be classified into appropriate product categories.

Possible categories might include:

```text
Clothing
Electronics
Footwear
Furniture
Accessories
```

You may use another suitable image dataset if necessary.

---

## Your Task

Develop an experimental image-classification system.

---

## Stage A — Explore the Images

Investigate:

- [ ] Number of images
- [ ] Image dimensions
- [ ] Number of classes
- [ ] Class distribution
- [ ] Image quality
- [ ] Incorrect/corrupted images
- [ ] Possible data leakage

Display representative examples from each class.

---

## Stage B — Prepare the Data

Create:

```text
Training Set
Validation Set
Test Set
```

Explain how you prevented the same or near-duplicate images from
appearing across different splits.

Apply appropriate preprocessing.

Investigate whether data augmentation is useful.

Possible transformations include:

- Resizing
- Cropping
- Flipping
- Rotation
- Normalization

Do not apply transformations without explaining why.

---

## Stage C — Build a CNN

Build a Convolutional Neural Network.

Demonstrate understanding of:

- [ ] Convolutional layers
- [ ] Kernels
- [ ] Feature maps
- [ ] Activation functions
- [ ] Pooling
- [ ] Fully connected layers
- [ ] Output layer
- [ ] Loss function

---

## Stage D — Train the CNN

Monitor:

```text
Training Loss
Validation Loss
Training Performance
Validation Performance
```

Investigate overfitting.

Experiment with at least two changes such as:

- Dropout
- Data augmentation
- Learning rate
- Network depth
- Batch size

Keep an experiment record.

---

# Transfer Learning Investigation

Training an image model from scratch may not always be necessary.

Select a suitable pretrained model.

Investigate:

- [ ] Pretrained weights
- [ ] Feature extraction
- [ ] Frozen layers
- [ ] Replacement classification head
- [ ] Fine-tuning
- [ ] Learning-rate selection

---

## Required Comparison

Compare:

```text
Simple Baseline
       ↓
CNN From Scratch
       ↓
Pretrained Model
       ↓
Transfer Learning / Fine-Tuning
```

Report appropriate metrics.

---

## Error Analysis

Investigate:

```text
Correct Predictions
Incorrect Predictions
High-Confidence Errors
Low-Confidence Predictions
```

Display examples.

For incorrect predictions, ask:

> What characteristics of the image may have contributed to the error?

---

## Final Question

Answer:

> Should the proposed e-commerce platform train its own image model
> from scratch or use transfer learning?

Support your recommendation using evidence.

---

# Challenge 3 — NLP & Transformer Investigation

## Scenario

Customers using the proposed e-commerce platform leave product reviews.

Examples might include:

> "The laptop works perfectly and delivery was fast."

> "The product is fine but delivery took too long."

> "The item arrived damaged and support did not help."

Mr Marapira and Mr Sibisi want to investigate whether AI can
automatically analyse this feedback.

---

## Your Task

Develop a system capable of classifying customer sentiment.

Possible output:

```text
Positive
Neutral
Negative
```

---

# Stage A — Explore the Text

Investigate:

- [ ] Number of reviews
- [ ] Missing reviews
- [ ] Review lengths
- [ ] Class distribution
- [ ] Duplicate reviews
- [ ] Unusual text
- [ ] Potential leakage

---

# Stage B — Establish a Baseline

Create a simple baseline before using deep learning.

Then develop a classical NLP pipeline.

For example:

```text
Customer Review
      ↓
Text Processing
      ↓
TF-IDF
      ↓
Classical Classifier
      ↓
Sentiment
```

Evaluate the system.

---

# Stage C — Transformer Approach

Investigate a pretrained transformer-based approach.

You must demonstrate conceptual understanding of:

- [ ] Tokenization
- [ ] Tokens
- [ ] Embeddings
- [ ] Query
- [ ] Key
- [ ] Value
- [ ] Self-attention
- [ ] Multi-head attention
- [ ] Positional information
- [ ] Transformer representations
- [ ] Pretraining
- [ ] Fine-tuning

> You are not required to train a transformer from scratch.

---

# Stage D — Model Comparison

Compare:

| Approach | Performance | Training Cost | Inference Cost | Complexity |
|---|---:|---:|---:|---|
| Simple Baseline | | | | |
| TF-IDF + ML | | | | |
| Transformer | | | | |

Do not select a model purely because it is more advanced.

---

# Stage E — Error Analysis

Find examples involving:

- Negation
- Long reviews
- Short reviews
- Ambiguous reviews
- Mixed sentiment
- Unusual vocabulary
- High-confidence errors

Explain why the models may struggle with these examples.

---

## Final Question

Answer:

> Does the transformer provide enough improvement over classical NLP
> to justify its additional complexity?

---

# Challenge 4 — Generative AI & Retrieval

## Scenario

Mr P.G. Marapira and Mr A.N.N. Sibisi are considering an AI shopping
assistant for the e-commerce platform.

Customers should be able to ask questions such as:

> "What is your return policy?"

> "Which laptops have at least 16 GB RAM?"

> "How long does delivery take?"

> "What warranty comes with this product?"

The assistant must answer using information supplied by the platform.

It should **not invent store policies, product specifications or
delivery information**.

---

# Stage A — Explain the Architecture

Before implementing anything, explain:

- [ ] Large Language Models
- [ ] Embeddings
- [ ] Vector representations
- [ ] Semantic similarity
- [ ] Retrieval
- [ ] Context
- [ ] Prompt construction
- [ ] Generation
- [ ] Hallucination
- [ ] Grounding

Then answer:

> Why could an unrestricted LLM be unsafe or unreliable as an
> e-commerce information system?

---

# Stage B — Build the Knowledge Base

Create a small e-commerce knowledge base.

It should contain information such as:

```text
Product descriptions
Product specifications
Store policies
Frequently asked questions
Delivery information
Return information
Warranty information
```

The information must be clearly structured.

---

# Stage C — Semantic Retrieval

Create embeddings for appropriate content.

Develop:

```text
Customer Question
       ↓
Question Embedding
       ↓
Similarity Search
       ↓
Relevant Documents
```

Test whether the retrieval system finds the correct information.

---

# Stage D — Retrieval-Augmented Generation

Extend the system:

```text
Customer Question
       ↓
Embedding
       ↓
Retrieval
       ↓
Relevant Store Information
       ↓
Prompt + Retrieved Context
       ↓
Language Model
       ↓
Answer
```

The generated answer should be grounded in retrieved information.

---

# Stage E — Failure Behaviour

Your system must handle situations where the knowledge base does not
contain enough information.

Test questions such as:

```text
"What is your international shipping policy?"
```

when no international shipping policy exists in the supplied
knowledge base.

The system should prefer:

> "The available information does not provide an answer to this question."

over inventing an answer.

---

# Stage F — Evaluation

Create an evaluation dataset containing:

- [ ] Direct questions
- [ ] Paraphrased questions
- [ ] Ambiguous questions
- [ ] Questions whose answers exist
- [ ] Questions whose answers do not exist
- [ ] Questions containing irrelevant information
- [ ] Similar products with different specifications

---

## Evaluate

Investigate:

| Area | Question |
|---|---|
| Retrieval | Was the correct information retrieved? |
| Relevance | Was the retrieved information relevant? |
| Answer correctness | Was the final answer correct? |
| Grounding | Was the answer supported by the retrieved information? |
| Unsupported claims | Did the system invent information? |
| Failure behaviour | Did it refuse appropriately when evidence was insufficient? |

---

## Critical Question

Answer:

> What should the AI shopping assistant do when the retrieved
> documents do not contain enough evidence to answer the customer's
> question?

---

# Level 5 Gateway Challenge

# BIH Intelligent E-Commerce Prototype

This is the final challenge for Level 5.

---

## Scenario

Mr P.G. Marapira and Mr A.N.N. Sibisi have reviewed the Machine
Learning work completed during the previous levels.

They now want to investigate whether a modern AI feature should be
integrated into their proposed e-commerce platform.

You have been assigned as the Data Scientist responsible for
developing and evaluating an experimental prototype.

---

# Choose ONE Primary System

## Option A — Product Image Intelligence

Build an image-classification system capable of identifying product
categories.

Your system should investigate:

```text
CNN
 ↓
Transfer Learning
 ↓
Fine-Tuning
 ↓
Evaluation
```

---

## Option B — Customer Review Intelligence

Build an NLP system for analysing customer feedback.

Investigate:

```text
Simple Baseline
      ↓
Classical NLP
      ↓
Transformer Approach
      ↓
Evaluation
```

---

## Option C — AI Shopping Assistant

Build a retrieval-supported question-answering prototype using
e-commerce product and policy information.

Investigate:

```text
Knowledge Base
      ↓
Embeddings
      ↓
Retrieval
      ↓
Retrieved Context
      ↓
Language Model
      ↓
Grounded Answer
```

---

# Mandatory Baseline

Regardless of which option you select, you must establish a simpler
baseline.

Your investigation must follow:

```text
Business Problem
       ↓
Define Success
       ↓
Simple Baseline
       ↓
Deep Learning / AI Approach
       ↓
Controlled Evaluation
       ↓
Error Analysis
       ↓
Cost Analysis
       ↓
Risk Analysis
       ↓
Recommendation
```

---

# Experiment Tracking

Maintain an experiment table.

| Experiment | Change | Training Result | Validation Result | Observation |
|---|---|---:|---:|---|
| Baseline | Initial system | | | |
| Experiment 1 | | | | |
| Experiment 2 | | | | |
| Experiment 3 | | | | |

The exact metrics will depend on the selected project.

---

# Error Analysis

Do not report only the best metric.

Investigate where the system fails.

Select representative:

```text
Successful Prediction
Typical Error
High-Confidence Error
Difficult Example
Unexpected Failure
```

Explain each one.

---

# Computational Cost

Discuss:

- Training time
- Inference time
- Memory requirements
- Model size
- Hardware requirements
- Storage requirements
- Scalability

Answer:

> Is the performance improvement worth the additional computational
> cost?

---

# Responsible AI Review

Investigate risks relevant to your chosen system.

Consider:

- [ ] Customer privacy
- [ ] Data protection
- [ ] Bias
- [ ] Unfair outcomes
- [ ] Hallucination
- [ ] Incorrect predictions
- [ ] Model confidence
- [ ] Transparency
- [ ] Human oversight
- [ ] Misuse
- [ ] Security considerations

Do not claim that a model is safe simply because it has high accuracy.

---

# Final Technical Report

Prepare a technical recommendation for:

**Mr P.G. Marapira and Mr A.N.N. Sibisi**

Your report must answer:

1. What problem was investigated?
2. Why could the proposed feature be useful?
3. What data was used?
4. How was the data prepared?
5. What baseline was established?
6. What advanced AI approach was implemented?
7. Why was that approach selected?
8. How was the system evaluated?
9. What were the results?
10. Where does the system perform well?
11. Where does the system fail?
12. What computational cost was introduced?
13. What risks were identified?
14. Is the advanced approach better than the baseline?
15. Is the improvement practically meaningful?
16. Should development continue?

---

# Final Recommendation

Your conclusion does not have to recommend deployment.

Valid recommendations include:

```text
Proceed to MLOps Development

Run a Controlled Pilot

Improve the Model

Collect More Data

Improve the Dataset

Redesign the AI System

Use the Simpler Baseline

Do Not Continue Development
```

Your recommendation must follow from your evidence.

---

# Required Repository

```text
BIH-level-5-gateway/
│
├── README.md
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01-exploration.ipynb
│   ├── 02-baseline.ipynb
│   ├── 03-deep-learning-ai.ipynb
│   └── 04-evaluation.ipynb
│
├── src/
│   ├── data.py
│   ├── model.py
│   ├── train.py
│   └── evaluate.py
│
├── models/
│
├── figures/
│
├── reports/
│   └── technical-report.md
│
└── requirements.txt
```

---

# Assessment Structure

The Level 5 Gateway is assessed using three components:

| Assessment | Weight |
|---|---:|
| GitHub Project | 70% |
| Technical Defence | 20% |
| Live Modification | 10% |
| **Total** | **100%** |

---

# Part A — GitHub Project Assessment

## 70 Marks

| Competency | Weight |
|---|---:|
| Problem Formulation & Baseline | 8% |
| Data Preparation | 8% |
| Deep Learning Implementation | 12% |
| Training & Validation | 10% |
| Evaluation & Error Analysis | 12% |
| Advanced AI Technique | 8% |
| Comparison Against Baseline | 5% |
| Reproducibility & Repository Quality | 3% |
| Responsible AI & Limitations | 4% |
| **Total** | **70%** |

---

# Part B — Technical Defence

## 20 Marks

After submission, the learner must complete a short technical defence.

The assessor will ask questions about the learner's **own project**.

Possible questions include:

> Why did you choose this architecture?

> Why did you select this loss function?

> What does the optimizer do?

> Explain what happens during backpropagation.

> Why did validation loss increase?

> How did you detect overfitting?

> Why did you freeze these layers?

> Why did you select this evaluation metric?

> What happens if this preprocessing step is removed?

> What is the weakest part of your system?

> Why should BIH trust this result?

The learner should be able to explain important parts of their
implementation without relying entirely on documentation or AI tools.

---

# Part C — Live Modification

## 10 Marks

The assessor will request a reasonable modification to the learner's
own project.

The exact modification should not be announced before the assessment.

Examples include:

### Neural Network

```text
Change the learning rate and explain the resulting training behaviour.
```

### Computer Vision

```text
Freeze an additional layer and investigate what changes.
```

### NLP

```text
Add several new customer reviews and demonstrate how the pipeline
processes them.
```

### Classification

```text
Change the decision threshold and explain how precision and recall
change.
```

### RAG

```text
Add a new store-policy document and demonstrate whether the system
can retrieve the new information.
```

The learner must:

1. Locate the relevant code.
2. Make the modification.
3. Run the system.
4. Inspect the result.
5. Explain what happened.

---

# Gateway Requirements

To successfully complete Level 5:

```text
Overall Score ≥ 70%
```

AND the learner must demonstrate acceptable competence in:

- Deep Learning implementation
- Training and validation
- Evaluation
- Error analysis
- Technical defence
- Live modification

A high overall score should not compensate for an inability to
understand or modify the submitted system.

---

# Academic & AI Use

AI tools may support learning and development, but they do not replace
understanding.

The learner must be able to:

- Explain submitted code
- Explain model decisions
- Reproduce important results
- Modify the implementation
- Defend methodological choices

Submitting AI-generated code that the learner cannot explain does not
demonstrate competence.

---

# Gateway Decision

Successful completion demonstrates readiness for:

# Level 6 — MLOps

The learner should now be capable of moving through:

```text
Problem
   ↓
Baseline
   ↓
Data
   ↓
Deep Learning / AI System
   ↓
Training
   ↓
Validation
   ↓
Evaluation
   ↓
Error Analysis
   ↓
Responsible AI Review
   ↓
Evidence-Based Recommendation
```

---

# Final Transition Question

Mr P.G. Marapira and Mr A.N.N. Sibisi approve the experimental AI
prototype for further development.

They now ask:

> **How can this experimental model be packaged, deployed, monitored,
> versioned and maintained reliably as part of a real production
> system?**

Do not solve this problem yet.

This becomes the starting point for:

## Level 6 — MLOps
