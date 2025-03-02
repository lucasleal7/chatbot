# Chatbot Interativo com Python e Langchain
## Descrição
Este projeto foi desenvolvido como parte do meu aprendizado em Ciência de Dados, com o objetivo de aprimorar meus conhecimentos em processamento de linguagem natural e integração de dados. Usando Python e a biblioteca Langchain, criei um chatbot interativo capaz de buscar e interpretar informações de fontes como páginas web, vídeos do YouTube e documentos PDF.
## Objetivo
O objetivo deste projeto é criar um chatbot inteligente usando Python e a biblioteca Langchain, capaz de buscar, interpretar e interagir com informações de diferentes fontes, como páginas web, vídeos do YouTube e documentos PDF.
# Plajenamento da solução
## Produto final
O produto final desse projeto é um chatbot interativo e eficiente, capaz de responder perguntas de forma dinâmica, buscando informações de diferentes fontes — como páginas web, vídeos do YouTube e documentos PDF. Ele usa a biblioteca Langchain para criar prompts avançados e interagir com modelos de linguagem, permitindo consultas mais precisas e contextualizadas.
Esse chatbot pode ser facilmente adaptado para diferentes casos de uso, como atendimento ao cliente, suporte técnico ou assistentes virtuais personalizados, tornando-se uma ferramenta versátil e poderosa.
## Ferramentas
Python 3.12.9: Linguagem de programação principal, conhecida pela sua simplicidade e poder na área de ciência de dados e inteligência artificial.
Langchain: Biblioteca que facilita a criação de aplicativos baseados em modelos de linguagem, permitindo a construção de fluxos de conversa mais avançados.
OpenAI API: Para integrar modelos de linguagem avançados, como o GPT, responsáveis pelo entendimento e geração de respostas.
WebBaseLoader: Para coletar e interpretar dados diretamente de páginas web.
YoutubeLoader: Para extrair informações de vídeos do YouTube.
PyPDFLoader: Para ler e interpretar conteúdos de arquivos PDF.
# Desenvolvimento
## Estratégia da Solução
Para desenvolver este chatbot inteligente, utilizei a linguagem Python junto com a biblioteca Langchain, estruturando um fluxo que integra diferentes fontes de dados (web, YouTube e PDF). A estratégia foi construir prompts eficientes e usar modelos de linguagem avançados através da API da OpenAI. A cada etapa, testei a captura e interpretação de dados, ajustando parâmetros e técnicas de pré-processamento para garantir respostas precisas e contextuais. O modelo final foi validado pela qualidade das interações, buscando um equilíbrio entre a compreensão da pergunta e a assertividade das respostas.
## O passo a passo
Passo 1: Definição do objetivo e escopo do chatbot, estabelecendo as fontes de dados a serem integradas (web, YouTube e PDF).
Passo 2: Configuração do ambiente Python e instalação das bibliotecas necessárias, como Langchain, OpenAI, WebBaseLoader, YoutubeLoader e PyPDFLoader.
Passo 3: Criação das chaves de API e configuração das credenciais de acesso à OpenAI.
Passo 4: Implementação dos loaders de dados, permitindo a extração de informações das fontes escolhidas.
Passo 5: Pré-processamento dos dados coletados, transformando-os em um formato adequado para serem usados pelo modelo de linguagem.
Passo 6: Construção dos prompts usando a biblioteca Langchain, otimizando a interação entre o modelo de linguagem e as fontes de dados.
Passo 7: Testes iniciais do chatbot, ajustando parâmetros dos modelos de linguagem e técnicas de consulta para melhorar a precisão das respostas.
Passo 8: Validação da performance do chatbot, analisando a qualidade e relevância das respostas fornecidas.
Passo 9: Ajustes finais e otimização do modelo, garantindo interações fluidas e assertivas.
Passo 10: Documentação do projeto, incluindo a descrição, estratégia, ferramentas utilizadas e instruções para execução.
# Resultados
## Usando para sites
### Escolha das opções
![opcpes_escolha]( 
img/opções_escolha.png)
### Inserindo url do site
![url_site]( 
img/url_site.png)
### Pergunta do usuário e resposta do bot
![resposta_site]( 
img/resposta_site.png)

## Usando para videos do YouTube
### Inserindo url do video
![url_youtube]( 
img/url_video.png)
### Pergunta do usuário e resposta do bot
![resposta_youtube]( 
img/resposta_video.png)
## Usando para PDFs
### Inserindo opção de pdf
![escolha_pdf]( 
img/escolha_pdf.png)
### Pergunta do usuário e resposta do bot
![resposta_pdf]( 
img/resposta_pdf.png)

# Conclusão
Este projeto resultou no desenvolvimento de um chatbot inteligente, capaz de buscar, interpretar e responder perguntas com base em diferentes fontes de dados, como páginas web, vídeos do YouTube e documentos PDF. Usando Python e a biblioteca Langchain, conseguimos integrar essas fontes de forma eficiente, proporcionando interações dinâmicas e precisas. Durante a construção, aprimoramos técnicas de manipulação de dados, criação de prompts avançados e integração de modelos de linguagem, reforçando a importância de um bom pré-processamento e ajustes de parâmetros para melhorar a qualidade das respostas.  
Esse chatbot tem potencial para ser adaptado em diversos contextos, como assistentes virtuais, sistemas de suporte ao cliente ou ferramentas de consulta automatizada, demonstrando a flexibilidade e robustez da solução construída.  

# Próximos passos
Como próximos passos deste projeto, pretendo expandir as fontes de dados integradas, incluindo bancos de dados SQL e planilhas, para aumentar a versatilidade do chatbot. Também quero aprimorar o pré-processamento dos dados, aplicando técnicas mais avançadas de limpeza e enriquecimento, a fim de melhorar a qualidade das respostas. Planejo explorar diferentes modelos de linguagem além da API da OpenAI, testando alternativas open-source ou APIs especializadas. Outro objetivo é desenvolver uma interface de usuário que torne a interação mais intuitiva e acessível. Por fim, vou avaliar a performance do chatbot com diferentes métricas, ajustando os prompts para alcançar ainda mais precisão nas respostas.
