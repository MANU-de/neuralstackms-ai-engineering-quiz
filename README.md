# AI Engineering Quiz – How knowledgeable are you really?

*A quiz by NeuralStack | MS - Manuela Schrittwieser*

15 questions on LLM fundamentals, RAG, and agent architectures. At the end, you’ll find out where you stand—and which learning resources are the right fit for your next steps.

---

## Questions

### Question 1
**Category:** LLM Fundamentals | **Difficulty:** Easy

**Question:** What is the primary purpose of the attention mechanism in Transformer architectures?

- A) Reduction of model size
- B) Weighting the relevance of different tokens relative to one another in context
- C) Accelerating training through pruning
- D) Compression of embeddings

**Correct answer:** B

---

### Question 2
**Category:** LLM Fundamentals | **Difficulty:** Easy

**Question:** What does "tokenization" describe in the context of LLMs?

- A) Encryption of training data
- B) Assignment of API keys for model access
- C) Decomposition of text into processable basic units (sub-words, words, characters)
- D) Compression of the model output before output

**Correct answer:** C

---

### Question 3
**Category:** LLM Fundamentals | **Difficulty:** Intermediate

**Question:** Which sampling parameter primarily controls the randomness or "creativity" of text generation?

- A) Top-k
- B) Max Tokens
- C) Batch Size
- D) Temperature

**Correct answer:** D

---

### Question 4
**Category:** LLM Fundamentals | **Difficulty:** Intermediate

**Question:** What fundamentally distinguishes fine-tuning from prompt engineering?

- A) Fine-tuning modifies the model weights; prompt engineering does not.
- B) Fine-tuning is relevant exclusively for image models.
- C) Prompt engineering strictly requires GPU clusters, whereas fine-tuning does not.
- D) There is no technical difference, only a conceptual one.

**Correct answer:** A

---

### Question 5
**Category:** LLM Fundamentals | **Difficulty:** Easy

**Question:** What is meant by the "context window" of an LLM?

- A) The number of training epochs
- B) The latency of an API request
- C) The maximum amount of text (tokens) a model can process simultaneously
- D) The number of requests that can be processed in parallel

**Correct answer:** C

---

### Question 6
**Category:** RAG | **Difficulty:** Easy

**Question:** What is the primary purpose of Retrieval-Augmented Generation (RAG)?

- A) Acceleration of model training
- B) Augmenting LLM responses with external, up-to-date, or domain-specific knowledge to reduce hallucinations
- C) Alternative to fine-tuning for classification tasks
- D) Compression of vector databases

**Correct answer:** B

---

### Question 7
**Category:** RAG | **Difficulty:** Medium

**Question:** What role does "chunking" play in a RAG pipeline?

- A) Encryption of sensitive documents prior to storage
- B) Splitting of documents into processable segments for embedding and retrieval
- C) Reduction of model parameters at runtime
- D) Summary of the final LLM output

**Correct answer:** B

---

### Question 8
**Category:** RAG | **Difficulty:** Medium

**Question:** What does cosine similarity typically measure in a vector database?

- A) The file size of stored embeddings
- B) The load time of a request
- C) The semantic proximity between two vector representations
- D) The number of stored documents

**Correct answer:** C

---

### Question 9
**Category:** RAG | **Difficulty:** Hard

**Question:** What does "hybrid search" describe in the context of RAG?

- A) Combination of dense (semantic) and sparse (keyword-based, e.g., BM25) retrieval methods
- B) Parallel querying of multiple LLMs to reach a consensus
- C) Combination of cloud and on-premise models
- D) Mixture of training and test data

**Correct answer:** A

---

### Question 10
**Category:** RAG | **Difficulty:** Hard

**Question:** What is the purpose of a re-ranking step after the initial retrieval?

- A) Deletion of irrelevant documents from the vector database
- B) Acceleration of the embedding process
- C) Reduction of chunk size for subsequent requests
- D) Re-ranking of the retrieved candidates using a more precise model to improve the relevance order.

**Correct answer:** D

---

### Question 11
**Category:** Agents | **Difficulty:** Medium

**Question:** What characterizes an "agentic workflow" as opposed to a simple prompt-response cycle?

- A) The LLM makes decisions iteratively, uses tools, and autonomously plans multi-step actions.
- B) Only a larger model is used.
- C) No user input is required.
- D) A prompt is no longer required.

**Correct answer:** A

---

### Question 12
**Category:** Agents | **Difficulty:** Easy

**Question:** What is "function calling" or "tool use" in the context of LLMs?

- A) An internal debugging mechanism
- B) The model's ability to generate structured calls to external functions/APIs
- C) Recursion within a prompt
- D) A method for model compression

**Correct answer:** B

---

### Question 13
**Category:** Agents | **Difficulty:** Medium

**Question:** What does the ReAct pattern (Reasoning + Acting) describe in agent architectures?

- A) A training method for reinforcement learning
- B) Alternating chaining of reasoning steps and actions (tool calls) with observation of the results
- C) A method for image generation
- D) A caching strategy for API responses

**Correct answer:** B

---

### Question 14
**Category:** Agents | **Difficulty:** Hard

**Question:** What challenge is typical for multi-agent systems?

- A) Lack of text generation capability
- B) Impossibility of using external APIs
- C) Coordination, context sharing, and avoidance of redundant or contradictory actions between agents
- D) Lack of support for natural language

**Correct answer:** C

---

### Question 15
**Category:** Agents | **Difficulty:** Hard

**Question:** What is the purpose of MCP (Model Context Protocol) in the agent ecosystem?

- A) A protocol for compressing model weights
- B) An encryption standard for training data
- C) Standardized interface through which LLMs/agents can access external tools, data, and services in a structured manner
- D) A method for token counting

**Correct answer:** C

---

## Evaluation logic

**Basic principle:** 1 point per correct answer, max. 15 points.

Additionally, **tracking by category** (5 questions each on LLM fundamentals, RAG, and agents) is recommended to determine not only the overall proficiency level but also the specific category where an individual is weakest. This enables a second, more targeted recommendation to complement the general level assessment.

```
score_total = number of correct answers (0–15)
score_llm   = correct answers from questions 1–5
score_rag   = correct answers from questions 6–10
score_agent = correct answers from questions 11–15

weakest_category = min(score_llm, score_rag, score_agent)
```

### Score Bands (score_total)

| Points | Level | Brief description |
|---|---|---|
| 0–5 | **Beginner** | Understanding of basic concepts is still patchy; a solid foundation is partially lacking. |
| 6–10 | **Advanced** | Core concepts are solid; detailed knowledge in specific areas could be further developed. |
| 11–15 | **Expert** | Broad, robust understanding across all three categories |

---

## Result Texts & Resource Mapping

### 0–5 points — Beginner

You are at the beginning of your AI engineering journey—this is the best time to build a solid foundation before venturing into advanced topics like RAG pipelines or agents.

**Recommended starting point:** `To start learning AI engineering as a beginner, focus on core interactive courses and guides including the Prompt Engineering Guide, DeepLearning.AI short courses, and Microsoft's AI for Beginners curriculum.`

**Personalized support (optional):** "Want a shortcut?
For a one-time donation, I'll put together a
personalized learning pack tailored to exactly where
you're starting from. → [GitHub Sponsors profile]( https://github.com/sponsors/MANU-de)

### 6–10 points — Advanced

You’ve got the fundamentals down. Now it’s worth looking at the weakest of your three categories—that’s where you’ll make the quickest leap in knowledge.

**Recommended area of ​​focus:** `To master advanced AI engineering, focus on core production strategies: prioritize implementation over theory, build robust evaluation loops, and optimize system scalability.`

**Personalized support (optional):** "Want to skip the
trial-and-error? Book a short 1:1 session and we'll
work through your weakest category together. →
[GitHub Sponsors profile]( https://github.com/sponsors/MANU-de)

### 11–15 points — Expert

Strong result—you have a solid grasp of the fundamentals of LLMs, RAG, and agents. The logical next step is to look at the security aspects of these systems: how are RAG pipelines and agents attacked, and how can they be hardened?

**Recommended next step:** `AI security content, e.g., an introduction to red teaming`

**Personalized support (optional):** "Building something
real? I offer project consulting—code reviews,
architecture discussions, and testing support for
production AI systems. → [GitHub Sponsors profile]( https://github.com/sponsors/MANU-de)

---




