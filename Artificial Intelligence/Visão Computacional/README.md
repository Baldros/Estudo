# Visão Computacional

Visão computacional estuda como representar, processar e interpretar imagens e vídeos. O objetivo desta trilha é priorizar material com **definições matemáticas explícitas + implementação**, evitando cursos muito discursivos.

## Núcleo atual

- **Foundations of Computer Vision** — Antonio Torralba, Phillip Isola e William T. Freeman (MIT Press, 2024). Minha referência principal para uma visão moderna da área: formação de imagem, geometria, aprendizado, CNNs, transformers, modelos generativos/diffusion, visão 3D e outros fundamentos. O livro é aberto e o projeto possui repositório com o texto-fonte, demos e código.
  - Livro: https://visionbook.mit.edu/
  - Código/fonte: https://github.com/Foundations-of-Computer-Vision/visionbook

- **Computer Vision: Algorithms and Applications, 2nd ed.** — Richard Szeliski (2022). Referência ampla e matemática para algoritmos clássicos e modernos: formação de imagem, features, matching, movimento, stitching, reconhecimento, segmentação, reconstrução 3D e deep learning.
  - Livro: https://szeliski.org/Book/

- **Understanding Deep Learning** — Simon J. D. Prince (MIT Press, 2023; versão online continuamente atualizada). Não é específico de visão, mas é um excelente complemento para a parte moderna: CNNs, ResNets, transformers, GANs, VAEs e diffusion. Tem equações e dezenas de notebooks Python.
  - Livro/notebooks: https://udlbook.github.io/udlbook/
  - Repositório: https://github.com/udlbook/udlbook

- **Modern Computer Vision with PyTorch, 2nd ed.** — V. Kishore Ayyadevara e Yeshwanth Reddy (2024). Material mais voltado à implementação. Útil para transformar a teoria em código PyTorch e revisar classificação, detecção, segmentação, CLIP, multimodalidade e Stable Diffusion.
  - Código: https://github.com/PacktPublishing/Modern-Computer-Vision-with-PyTorch-2E

## Clássicos que continuam úteis

- **Multiple View Geometry in Computer Vision, 2nd ed.** — Richard Hartley e Andrew Zisserman (2004). Antigo, mas ainda uma referência central para geometria projetiva, modelos de câmera, geometria epipolar, matriz fundamental, tensor trifocal e reconstrução 3D.
  - Material oficial e código MATLAB: https://www.robots.ox.ac.uk/~vgg/hzbook/

- **Digital Image Processing, 4th ed.** — Rafael C. Gonzalez e Richard E. Woods (2018). Útil para processamento de imagens clássico: filtragem, Fourier, restauração, morfologia, segmentação e representação. Não deve ser usado como referência principal para deep learning moderno.

## Como estudar

Para evitar material excessivamente discursivo:

1. **Definição/equações:** começar por *Foundations of Computer Vision* ou Szeliski.
2. **Implementação:** reproduzir a ideia em PyTorch ou usar o código/notebook associado.
3. **Tópicos modernos:** depois da base, ir direto ao paper original + implementação oficial.
4. **Geometria 3D:** usar Hartley–Zisserman como referência matemática, não como leitura linear.

Para a fronteira atual (ViT, DINO, SAM, CLIP, JEPA, diffusion, modelos de vídeo etc.), livros envelhecem rápido; o material principal deve ser **paper + código oficial**, usando os livros acima apenas para a base matemática.
