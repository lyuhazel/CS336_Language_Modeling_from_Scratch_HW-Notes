### CS336_Language_Modeling_from_Scratch_HW-Notes 
##### Instructor: Prof. Tatsunori Hashimoto, Prof. Percy Liang | Spring 2026
Self-paced study on CS336 Language Modeling from Scratch, consisting of reading notes and homework practices on Transformer, and Supervised Finetuning and Reinforcement Learning.


##### Content
###### What is this course about?

Language models serve as the cornerstone of modern natural language processing (NLP) applications and open up a new paradigm of having a single general purpose system address a range of downstream tasks. As the field of artificial intelligence (AI), machine learning (ML), and NLP continues to grow, possessing a deep understanding of language models becomes essential for scientists and engineers alike. This course is designed to provide students with a comprehensive understanding of language models by walking them through the entire process of developing their own. Drawing inspiration from operating systems courses that create an entire operating system from scratch, we will lead students through every aspect of language model creation, including data collection and cleaning for pre-training, transformer model construction, model training, and evaluation before deployment.

##### Coursework Assignments

###### Assignment 1: Basics
Implement all of the components (tokenizer, model architecture, optimizer) necessary to train a standard Transformer language model.
Train a minimal language model.
###### Assignment 2: Systems
Profile and benchmark the model and layers from Assignment 1 using advanced tools, optimize Attention with your own Triton implementation of FlashAttention2.
Build a memory-efficient, distributed version of the Assignment 1 model training code.
###### Assignment 3: Scaling
Understand the function of each component of the Transformer.
Query a training API to fit a scaling law to project model scaling.
###### Assignment 4: Data
Convert raw Common Crawl dumps into usable pretraining data.
Perform filtering and deduplication to improve model performance.
###### Assignment 5: Alignment and Reasoning RL
Apply supervised finetuning and reinforcement learning to train LMs to reason when solving math problems.
Optional Part 2: implement and apply safety alignment methods such as DPO.


Credits to Prof. Percy Liang, Tatsunori Hashimoto and CAs.
