# Generative AI Applications Repository

Welcome to my **Generative AI Applications Repository**. This repository showcases cutting-edge **generative AI** models and their practical implementations for a variety of tasks. Leveraging state-of-the-art large language modles, the repository demonstrates how large language models (LLMs) and other generative architectures can be applied effectively across different use cases such as language translation, summarization, and chatbot development.

## Current Applications

### 1. English-German Machine Translation
This application uses a fine-tuned version of the **Falcon-1B** model from **TII (Dubai)** for English-to-German translation. The model is optimized using **Low-Rank Adaptation (LoRA)** to enable efficient parameter tuning while keeping resource requirements minimal.

**Task**: Text-to-Text

## Technical Stack
- **Core Frameworks**: PyTorch, Hugging Face Transformers
- **Efficient Training**: **LoRA** for efficient parameter adaptation and **8-bit quantization** (via bitsandbytes) for memory optimization.
- **Model Architectures**: Falcon, LLaMA, Mistral (depending on the application requirements).
- **Evaluation Metrics**: **BLEU**, **ROUGE**, and qualitative human assessment.

## Future Applications
Currently I am working on several other application, the projects will be available soon: 
- **Text Summarization**: Generate concise summaries from long documents.
- **Creative Writing Assistant**: Assist in generating creative writing content like stories or poetry.
- **Code Generation**: Automatically generate code snippets from natural language descriptions.
- **Multimodal Generation**: Develop a text-to-image system to generate visuals from textual descriptions.
- **Domain-Specific Chatbot**: Build intelligent chatbots specialized in specific industries like healthcare, finance, and more.

## Getting Started

### Installation

To get started with this project, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/Dang1994/Large_Language_Model_Gen_AI
cd Large_Language_Model_Gen_AI
pip install -r requirements.txt
```

## Contribution Guidelines

I welcome contributions to this project. If you'd like to contribute, please follow the steps below:
1. **Fork** the repository.
2. **Create** a new branch for your feature or fix.
3. **Implement** your changes and document them clearly.
4. **Submit** a pull request for review. Ensure all code is well-documented.

## Contact Information

- **Author**: Subrat Kumar Dang
- **Email**: [w.subrat@gmail.com](mailto:w.subrat@gmail.com)
- **Website**: [Connect with me](sites.google.com/view/subratdang/home)

## License

This repository is licensed under the **Apache 2.0 License**. See the LICENSE file for more details.
