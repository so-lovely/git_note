### AI_Evaluating methods
**MMLU(Massive Multitask Language Understanding)**
MMLU is a new benchmark designed to measure knowledge acquired during pretraining by evaluating models exclusively in zero-shot and few-shot settings.

*Massive* : large and heavy or solid.
*exclusively* : to the exclusion of others; only; solely.

**Winogrande**
WinoGrande, a large-scale dataset of 44k problems, inspired by the original WSC(Warehouse-Sacle Computer) design.

**BIG_Bench**
BIG-Bench (Srivastava et al., 2022) is a diverse evaluation suite that focuses on tasks believed to be beyond the capabilities of current language models

*suite* : a set of rooms designated for one person's or family's use or for a particular purpose.

**ARC**
The Abstraction and Reasoning Challenge

*Abstraction*
the quality of dealing with ideas rather than events.

**Hallucinate**
experience an apparent sensory perception of something that is not actually present.

*apparent* : clearly visible or understood; obvious.

**prompt engineering**
Prompt engineering refers to the science of designing effective prompts to get desired responses

**In-context Learning**
 * In-context learning - specific method of prompt engineering where demonstration of task are provided as part of prompt.
  1. Zero-shot learning - model is performing tasks without any
input examples.
  2. Few or “N-Shot” Learning - model is performing and behaving based on input examples in user's prompt.

**semantic space**
high dimensional vector space

**project**
Verb
1. estimate or forecast (something) on the basis of present trends or data.
2. extend outward beyond something else; protrude.

**chunk_overlap**
1. Sentence structuring: chunk overlap can help identify sentence boundaries and improve sentence segmentation.
2. Text summarization: chunk overlap can aid in determining the most relevant sentences or phrases to summarize a text.
3. Question answering: chunk overlap can be used to identify relevant answer-bearing sentences or phrases.
4. Information retrieval: chunk overlap can improve search relevance and ranking by considering the cohesiveness of search results.
5. Language modeling: chunk overlap can inform language model architectures and improve their ability to capture contextual relationships.

**1. PEFT (Perturbated Embeddings for Fine-tuning)**

PEFT is a technique used to fine-tune pre-trained language models for specific downstream NLP tasks. The key idea is to perturb the input embeddings of the pre-trained model by adding a small amount of noise or perturbation. This perturbation helps the model learn task-specific features and adapt to the target task.

PEFT is particularly effective for tasks like sentiment analysis, spam detection, and text classification. By perturbing the input embeddings, PEFT helps the model learn to focus on task-relevant features and ignore noisy or irrelevant information.

**2. LoRA (Low-Rank Additive Model)**

LoRA is a simple yet powerful technique used to adapt pre-trained language models to specific tasks. The idea is to add a low-rank matrix to the pre-trained model's token-wise attention weights. This modification enables the model to learn task-specific features and adapt to the target task.

LoRA is particularly effective for tasks like machine translation, text classification, and question answering. By adding a low-rank matrix to the attention weights, LoRA helps the model focus on relevant features and ignore noisy or irrelevant information.

**3. QLoRA (Quantized LoRA)**

QLoRA is an extension of the LoRA technique that uses quantization to reduce the complexity of the added matrix. Quantization helps reduce the memory usage and computational requirements of the model, making it more suitable for deployment on resource-constrained devices.

QLoRA is particularly effective for tasks like low-latency speech recognition, text-to-speech synthesis, and language translation. By using quantization, QLoRA helps reduce the computational complexity of the model while maintaining its performance.

**VLLM**
V-LLM stands for Vision-and-Language Multimodal Transformer

**Rank**
1. **Rank of a tensor**: In linear algebra and tensor analysis, the rank of a tensor is a measure of the number of dimensions or modes in which the tensor is dense. The rank of a tensor is equivalent to the number of non-zero values

**supervisory**
having or relating to the role of observing and directing an activity or a person.
