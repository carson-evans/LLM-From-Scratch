# LLM from Scratch

## Dependencies (assuming Windows)
To install the required dependencies for this project, run the following command in your terminal:
```sh
pip install pylzma numpy ipykernel jupyter torch --index-url https://download.pytorch.org/whl/cu118
```

## OpenWebText Download
Access the OpenWebText Corpus [here](https://skylion007.github.io/OpenWebTextCorpus/).

## Research Papers
Explore the foundational papers that have influenced this project:
- [Attention is All You Need](https://arxiv.org/pdf/1706.03762.pdf) introduces the Transformer architecture, revolutionizing sequence modeling.
- [A Survey of LLMs](https://arxiv.org/pdf/2303.18223.pdf) provides an extensive overview of the landscape of large language models.
- [QLoRA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/pdf/2305.14314.pdf) explores techniques for efficient finetuning of quantized language models.

Note: If you don't have an NVIDIA GPU, the device parameter will default to 'cpu' since `device = 'cuda' if torch.cuda.is_available() else 'cpu'`. Running on CPU is supported but expect slower runtimes.
