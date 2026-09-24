# Artigos fundamentais de aprendizado por reforço

Esta coleção acompanha a evolução dos métodos de gradiente de política, de REINFORCE a formulações modernas com aproximação de funções e atualizações proximais.

## Artigos

- *Simple Statistical Gradient-Following Algorithms for Connectionist Reinforcement Learning* - Williams - trabalho fundador do algoritmo REINFORCE, que estima gradientes de desempenho a partir de retornos amostrados.
- *Policy Gradient Methods for Reinforcement Learning with Function Approximation* - estabelece o teorema do gradiente de política e uma forma estimável compatível com aproximação de funções.
- *Proximal Policy Optimization Algorithms* - propõe PPO, que reutiliza minibatches por meio de um objetivo substituto controlado e oferece implementação mais simples que TRPO.
- Artigo **2010.11364v2** - analisa convergência global de métodos clássicos de gradiente de política com trajetórias únicas ou minibatches de tamanho fixo.
- Artigo **2310.05000v1** - revisita REINFORCE e propõe estimar o gradiente com perturbações de parâmetros e técnicas de busca aleatória.
