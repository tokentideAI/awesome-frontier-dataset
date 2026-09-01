# awesome-frontier-dataset

A curated collection of cutting-edge research, datasets, and benchmarks for long-horizon agents — empowering next-generation AI evaluation and training.

### Math & General Reasoning

### [NaturalReasoning](https://huggingface.co/datasets/facebook/natural_reasoning)

**NaturalReasoning: Reasoning in the Wild with 2.8M Challenging Questions** is a large-scale general reasoning dataset released by Meta for training and evaluating advanced reasoning models.

* 2.8M challenging reasoning questions in the full dataset
* 1.15M+ publicly released high-quality examples
* Covers mathematics, science, economics, social sciences, and other reasoning domains
* Questions are mined from natural pretraining corpora rather than relying only on existing benchmarks
* Includes reference answers and model-generated responses
* Deduplicated and decontaminated against major reasoning benchmarks
* Demonstrates strong scaling behavior for reasoning model post-training

NaturalReasoning is particularly useful as a large-scale source of diverse and naturally occurring reasoning problems for SFT, reasoning distillation, and synthetic post-training data generation.

### Computer Science

### [OpenAI Frontier Evals](https://github.com/openai/frontier-evals)

A collection of frontier capability evaluations released by OpenAI, including software engineering and other complex real-world tasks.

Notable evaluations include:

* **SWE-Lancer** — Real-world freelance software engineering tasks with executable evaluation and economic-value grounding.

* **PaperBench** — Evaluates AI agents on reproducing machine learning research papers.

* **EVMbench** — Evaluation tasks related to smart contracts and Ethereum Virtual Machine development.

### [BAAI-TACO](https://modelscope.cn/datasets/BAAI/TACO)

**TACO (Topics in Algorithmic Code Generation)** is a large-scale benchmark for competitive programming and algorithmic code generation.

* ~26K programming problems
* Multiple difficulty levels
* Rich algorithm and skill annotations
* Executable test-case-based verification
* Suitable for code reasoning, SFT, rejection sampling, and RLVR

TACO is also frequently used as a seed problem source for synthetic reasoning datasets.

### Optimization and Planning

### STEM

* [MMMU Reasoning Distill Validation](https://www.modelscope.cn/datasets/modelscope/MMMU-Reasoning-Distill-Validation) — A multimodal reasoning validation dataset built on MMMU and augmented with reasoning trajectories distilled from the full DeepSeek-R1 model.

