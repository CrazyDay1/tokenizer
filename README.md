# minBPE
This work is inspired by [Andrej Kaprthy](https://github.com/karpathy).

Byte Paired Encoding (BPE) are a type of tokenizers, which purpose is to preprocess text to train LLMs, the architecture is first popularised in the [GPT-2 paper](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) and the associated [code release](https://github.com/openai/gpt-2) from OpenAI. Most LLMs (e.g. LLama2, Mistral) today use this architecture to train their tokenizers. 

General idea behind it is, it encodes natural language (e.g. English) into UTF-8 bytes format, then converts it into integer. You can have a go at it and test it out yourself in the tokenizer notebook.

This repo is still updating, you can expect more coming soon.
