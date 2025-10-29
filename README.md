# Prompt Engineering e Data Analytics com Python

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/[SEU-USUARIO-GITHUB]/[SEU-REPOSITORIO]/)

Um repositório com todos os materiais, notebooks e slides do curso que explora a interseção moderna entre a Análise de Dados tradicional e o poder dos Grandes Modelos de Linguagem (LLMs).

## Sobre o Curso

Este curso demonstra como o Python serve como a ponte essencial entre a Engenharia de Dados (a coleta e estruturação) e a Análise de Dados (a extração de valor).

Exploramos desde os fundamentos da análise de dados qualitativos com NLTK até técnicas avançadas de Engenharia de Prompt para interagir com APIs de IA de ponta (como Groq e Gemini), transformando dados brutos em insights acionáveis.

## Tópicos Abordados

### 1. Data Analytics com Python
* **Fundamentos:** Diferenças entre dados Quantitativos e Qualitativos.
* **Análise Qualitativa:** Técnicas de processamento de linguagem natural (NLP) para extrair insights de textos (ex: feedbacks de clientes).
* **Bibliotecas Essenciais:**
    * `Pandas`: Para carregar e manipular dados (ex: carregar CSVs).
    * `NLTK`: Para limpeza de texto (tokenização, stopwords).
    * `Matplotlib`: Para criar visualizações clássicas (ex: gráficos de barras).
    * `WordCloud`: Para criar nuvens de palavras e identificar temas frequentes.

### 2. Engenharia de Prompt
* **Fundamentos:** O que é, por que é crucial e sua história.
* **Técnicas Essenciais:**
    * Atribuição de Papel (Role Playing).
    * Zero-Shot vs. Few-Shot (Aprendizado no Contexto).
    * Chain-of-Thought (CoT) para resolução de problemas.
* **Estruturação:** Exemplos práticos de prompts bem e mal estruturados.
* **Aplicações Práticas:** Onde aplicar (Chatbots, Análise de Dados, Geração de Código, Marketing, etc.).

### 3. Integração de IA (APIs)
* **Conexão com APIs:** Como obter e usar chaves de API de forma segura no Google Colab (usando "Secrets").
* **Groq:** Conexão com modelos ultra-rápidos (ex: `llama-3.1-8b-instant`).
* **Google (Gemini):** Conexão com a plataforma Google AI Studio (ex: `gemini-1.0-pro`).
* **Caso de Uso:** Usar a IA como uma assistente para analisar um DataFrame do Pandas.

## Como Utilizar

A forma mais fácil de executar os notebooks (`.ipynb`) deste repositório é abri-los diretamente no Google Colab.

1.  **Clique no "badge" (selo) "Open in Colab"** no topo deste README.
    * (Não se esqueça de **substituir `[SEU-USUARIO-GITHUB]/[SEU-REPOSITORIO]`** no link do badge pelo seu usuário e nome do repositório!)
2.  Navegue até o notebook que deseja executar.
3.  Para os notebooks que usam as APIs do Groq ou Gemini, lembre-se de adicionar suas chaves de API pessoais no menu "Secrets" (🔑) do Colab.

## Tecnologias Utilizadas

* Python 3
* Google Colab
* Pandas
* NLTK (Natural Language Toolkit)
* Matplotlib
* WordCloud
* API do Groq
* API do Google (Gemini)
* `python-pptx` (Para geração de slides)
