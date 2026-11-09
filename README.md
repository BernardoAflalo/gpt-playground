# GPT, peça por peça

Playground interativo e didático da arquitetura **GPT** (decoder-only), seguindo GPT-1 (Radford et al., 2018),
GPT-2 (Radford et al., 2019) e GPT-3 (Brown et al., 2020).

**Acesse:** https://bernardoaflalo.github.io/gpt-playground/

13 passos: BPE (treinado ao vivo num corpus pequeno), embeddings de token e posição, atenção causal, bloco Pre-LN e fluxo residual,
pilha + LayerNorm final, previsão do próximo token, temperatura/top-k/top-p, geração com KV cache,
escala (calculadora de parâmetros e lei de escala), do fine-tuning ao few-shot, jornada de um token e quiz.

O modelo é uma miniatura (d_model = 8, 2 cabeças, 2 blocos) com **pesos aleatórios**: não foi treinado, mas executa as operações do GPT-2.

Série: [Transformer](https://bernardoaflalo.github.io/transformer-playground/) · [BERT](https://bernardoaflalo.github.io/bert-playground/) · GPT
