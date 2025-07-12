# 🌐 NLW Agents - Projeto de Interface com IA

Interface web que usa inteligência artificial para responder perguntas sobre jogos como **Valorant**, **League of Legends** e **CS:GO**, com dicas sobre estratégia, builds e jogabilidade.

## 🚀 Funcionalidades

- Escolha de jogo.
- Envio de perguntas personalizadas.
- Conexão com a API Gemini (Google AI).
- Respostas diretas, rápidas e com formatação em Markdown.
- Design estilizado com animações CSS.

 ## 💻 Tecnologias Utilizadas

- HTML5.
- CSS3.
- JavaScript.
- Gemini AI (API do Google).
  
## 🚀 Como Utilizar

1. Abra o arquivo `index.html` no seu navegador.

2. Insira sua **API Key do Gemini** no campo apropriado.  
   👉 Você pode gerar a chave aqui: [https://aistudio.google.com/apikey?hl=pt-br](https://aistudio.google.com/apikey?hl=pt-br).

3. Escolha um jogo da lista.

4. Escreva sua pergunta (ex: "Melhor build para ADC...").

5. Clique no botão **"Perguntar"** e aguarde a resposta da IA.


## 📸 Funcionamento

![Demonstração do assistente em uso](./assets/NLW_demo.gif)

  

## 🧠 Fundamentos Estudados

A seguir, estão os principais conceitos que estudei e apliquei ao longo do desenvolvimento deste projeto:

# HTML
- **HyperText**
   - Texto puros,livros,revistas,jornais.
   - Links: acessar outros documentos.
   - Imagens, vídeos, áudios.
- **Markeup**
   - Marcação.
   - Tags:  `<a> Link </a>`
   - Atributos: `<a href="Link">`
   - globais: `id`,`class`,...  `<a class="button" href="Link">`
- **Language**
   - Linguagem.
   - Sintaxe: maneira de escrever.

# HTTP
- **HyperText**
- **Transfer**
   - Tranferência.
- **Protocol**
   - Protocolo.
   - Conjunto de regras.
- **Methods HTTP (Verbos):** `Get`, `Post`, `Patch`/`Put`, `Delete`.
- **Headers (cabeçalhos):** Instruções/Informações extras para cada chamada.


# URL
- **Uniform**
   - Uniforme.
- **Resource**
   - Recurso.
- **Locator**
   - Localizador.  
   (Encontrar um recurso: `.html`, `.css`, `.js`, `.pdf`, `.png`, `.jpg`, `.mp4`, `.mp3`...).  
   Endereço.  

# IP
- **Internet**
   - Rede mundial de computadores.
- **Protocol**
   - Conjunto de regras.
- É o endereço do computador.  
- Comentarios:  
       `rocketseat.com.br` (domínio)  
       `123.32.1.23` (ip)  

# DNS
- **Domain**
   - Domínio.
- **Name**
   - Nome.
- **Server**
   - Servidor.

# CSS
- **Cascading**
   - Cascata.
   - Regras das escritas.
   - Hierarquia.
   - Especifidade.
- **Style**
    - Estilo.
- **Sheet**
   - Folha.

- delaração.
- seletor.
- propriedade e valor.

    - **Box Model:**
       - Espaços internos: `padding`  
       - Bordas: `border`  
       - Espaços externos: `margin`  
       - Conteúdo: `content`  
       - Largura: `width`  
       - Altura: `height`
         
     - **Tamanho:**
       
       `1rem` = `16px`  
       px= menor unidade de medida  

     - **Sobre Margin:**
     - 
        margin: 3rem;                   (aplica a todos os lados)  
        margin: 3rem 4rem;              (cima/baixo, direita/esquerda)  
        margin: 1rem 2 rem 3 rem 4 rem; (cima, direita, baixo, esquerda)  
        margin: auto;                   (divide igualmente)  
        margin: 3rem auto;               
        margin: 1rem 2rem 3rem auto;    (somente o lado de baixo será automático)  
    
# JS
- Linguagem de programação
- Browsers
- Input - Process - Output
- Variáveis
- Gemini (AI): esperar uma resposta
- Mexer no meu navegador
- Estrutura de dados
- Estrutra de decisão
- Algoritmo: sequência de passos lógica, de maneira ordenada, a fim de chegar a alguma conclusão (limitada)
  
- **Funcion**
   - Agrupamento e reuso de código
   - Sequencia lógica
   - Saída
- **Lógica (Pensamento computacional)**
   - Abstração
   - Decomposição
   - Algoritmo
   - Reconhecimento de padrão
- **Tipos de dados**
   - `Number` (numeros)
   - `String` (textos) (" ",' ', `` )
   - `Boolean`: true/false
   - `Objects`
   - ...

 # DOM
 - **Document**
 - **Object**
 - **Model**

 # API
- **Aplication**
- **Programming**
- **Interface**
- JSON: JavaScript Object Notation

# CDN
- **Content**
- **Devilery**
- **Network**

# LLM (tipo corretor de mensagem)
- **Large**
- **Language**
- **Model**
- Gemini, OpenAI (chatGPT), Anthropic (Claude)...

# Agentes AI
- Tools (ferramentas): permitem uso de código, ou apps, ou qualquer informação extra
- Melhor contexto

# Engenharia de prompet
- **One shot:** uma única pergunta sem muito contexto
- **Few shot:** é apresentado exemplos de que se espera
- **Chain of Thought:** Cadeia de pensamento para a IA responder gradativamente conforme a instrução.
