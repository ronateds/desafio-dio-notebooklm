# desafio-dio-notebooklm

## Tema e objetivo
Criar um segundo cérebro para analisar os últimos papers sobre IA e seus impactos.

## Fontes
### FONTES DE VÍDEO:
- https://www.youtube.com/watch?v=xc2FTBGRSJo
- https://www.youtube.com/watch?v=myDCd0hNqQU
- https://www.youtube.com/watch?v=IfoPg2QefF8
- https://www.youtube.com/watch?v=wE1ZgJdt4uM

### FONTES DE TEXTO:
- https://github.com/dair-ai/AI-Papers-of-the-Week/blob/main/years/2023.md
- https://github.com/dair-ai/AI-Papers-of-the-Week/blob/main/years/2024.md
- https://github.com/dair-ai/AI-Papers-of-the-Week/blob/main/years/2025.md
- https://github.com/dair-ai/AI-Papers-of-the-Week/blob/main/years/2026.md

Foram adicionadas outras fontes pelo Deep Research do Gemini.

## Diretriz de comportamento dada ao notebook
Comporte-se como um especialista de IA explicando conceitos para um publico leigo.

## Perguntas feitas, o que foi respondindo e de quais fontes

### Quais são os 5 principais papers recentes sobre IA?

Entre as pesquisas mais influentes dos ciclos recentes das principais conferências (como NeurIPS, ICLR e ACL), destacam-se cinco trabalhos seminais que representam mudanças de paradigma fundamentais em raciocínio, geração visual, arquiteturas de modelos, interpretabilidade mecanicista e alinhamento:

---

#### 1. **DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning** (2025)
* **Autores/Laboratório:** DeepSeek-AI.
* **Contribuição fundamental:** Demonstrou que modelos de linguagem podem desenvolver capacidades avançadas de raciocínio lógico por meio de **aprendizado por reforço em larga escala (RL) diretamente a partir de um modelo base**, sem necessidade de ajuste fino supervisionado massivo prévio. O experimento com o *DeepSeek-R1-Zero* evidenciou o surgimento espontâneo de comportamentos como reflexão interna, autoverificação e estratégias em cadeia de pensamento (*Chain-of-Thought*).
* **Impacto:** O trabalho consolidou o paradigma de *test-time compute* e refinamento por RL, alcançando paridade em matemática e código competitivo com modelos proprietários de ponta e viabilizando a destilação eficiente desses padrões de raciocínio para arquiteturas menores.

---

#### 2. **Visual Autoregressive Modeling: Scalable Image Generation via Next-Scale Prediction (VAR)** (2024)
* **Autores:** Keyu Tian, Yi Jiang, Zehuan Yuan, Bingyue Peng, Liwei Wang.
* **Premiação:** *Best Paper Award* no **NeurIPS 2024** (Main Track).
* **Contribuição fundamental:** Redefiniu a modelagem autorregressiva visual. Em vez de achatar a imagem bidimensional em uma sequência linear 1D de *tokens* discretos (ordenação raster), o modelo formula a geração como uma **predição em multi-escala (*next-scale prediction*)**, partindo de resoluções mais grosseiras para as mais finas (*coarse-to-fine*).
* **Impacto:** Eliminou os gargalos de ordem artificial e superou modelos de difusão em eficiência e qualidade de amostragem, estabelecendo leis de escala claras para a geração autorregressiva de imagens.

---

#### 3. **Scaling and Evaluating Sparse Autoencoders** (2024)
* **Autores:** Leo Gao, Tom Dupré la Tour, Henk Tillman, Gabriel Goh, Rajan Troll, Alec Radford, Ilya Sutskever, Jan Leike, Jeffrey Wu (OpenAI).
* **Contribuição fundamental:** Avançou a **interpretabilidade mecanicista** de modelos de fronteira ao treinar autoencoders esparsos (*Sparse Autoencoders* - SAEs) em larga escala para decompor as ativações internas de redes neurais profundas. 
* **Impacto:** Permitiu desentrelaçar o fenômeno da superposição de características (*feature superposition*), mapeando milhões de conceitos monosemânticos e interpretáveis dentro do espaço latente de modelos como o GPT-4 e formalizando leis de escala para o treinamento dessas estruturas.

---

#### 4. **Byte Latent Transformer: Patches Scale Better Than Tokens (BLT)** (2024–2025)
* **Autores/Laboratório:** Meta AI.
* **Premiação:** *Outstanding Paper Award* no **ACL 2025**.
* **Contribuição fundamental:** Propôs uma arquitetura transformadora que **elimina completamente a tokenização fixa de subpalavras**, operando diretamente sobre fluxos brutos de *bytes*. O BLT agrupa os bytes dinamicamente em *patches* latentes com base na entropia do texto, alocando mais capacidade computacional apenas onde a complexidade informacional é maior.
* **Impacto:** Supera gargalos estruturais clássicos de vocabulário, melhora a robustez a ruídos de entrada e corrige disparidades de processamento entre idiomas de diferentes recursos.

---

#### 5. **Artificial Hivemind: The Open-Ended Homogeneity of Language Models (and Beyond)** (2025)
* **Autores:** Liwei Jiang, Yuanjun Chai, Margaret Li, Mickel Liu, Raymond Fok, Nouha Dziri, Yulia Tsvetkov, Maarten Sap, Yejin Choi.
* **Premiação:** *Best Paper Award* no **NeurIPS 2025**.
* **Contribuição fundamental:** Introduziu o *benchmark* **Infinity-Chat** para diagnosticar o colapso de modos e a perda de diversidade em respostas abertas e criativas de LLMs. O estudo revelou empiricamente o efeito de *Artificial Hivemind*, marcado tanto pela repetição interna dentro do mesmo modelo quanto pela extrema homogeneidade entre diferentes famílias de modelos comerciais.
* **Impacto:** Expôs os efeitos colaterais dos métodos atuais de alinhamento e aprendizado por reforço, que tendem a recompensar respostas seguras e convergentes em detrimento da criatividade e da pluralidade humana.

---

💡 Quer que eu faça uma análise aprofundada dos detalhes técnicos ou das fórmulas de algum desses artigos específicos?

#### Discuss what these sources say about Visão Geral e Arquitetura, in the larger context of Byte Latent Transformer (BLT). (Sugestão do Gemini)


## Link do notebook compartilhado

https://notebook.google.com/notebook/dea91149-4480-455c-9423-4a3705b62419
