# Imersão IA - Alura

## AULA 01 - EXPLORANDO A IA: FERRAMENTAS E POSSIBILIDADES

> Será que a inteligência artificial vai revolucionar a maneira como trabalhamos atualmente?

> Nesta primeira aula da Imersão IA, você terá a oportunidade de explorar ferramentas inovadoras, como o ChatGPT, Bing.AI e outras que podem te auxiliar em seu trabalho, independentemente da área em que atue. Essa é uma oportunidade única para entender como a inteligência artificial está impactando o mundo e descobrir como essas tecnologias podem ser aplicadas de forma relevante em seu trabalho.

### Prompts da aula

- Escreva a sinopse de um filme de Star Wars que se passa durante a invasão da cidade de São Paulo em um futuro apocalíptico.
- Write the synopsis of a Star Wars movie that takes place during the invasion of São Paulo city in a future apocalyptic scenario.
- Crie uma imagem de um poster para esse filme.
- Qual é a diferença entre o Excel e o google spreadsheets?
- Crie uma tabela com os 10 países mais populosos da Europa. Ela vai ter 3 colunas. Na primeira coluna você terá o nome do país; na segunda coluna, a capital desse país; e na terceira coluna, a população desse país.
- Crie cinco ideias para uma campanha promocional de lançamento de um novo filme, cuja sinopse é...
- Crie um título e uma legenda atraentes para um post no Instagram sobre a estreia de um novo filme, cuja sinopse é...

### Links citados

- Link da ferramenta [ChatGPT.openai](https://chat.openai.com/)
- Link do navegador [Bing AI](https://www.bing.com/?/ai)
- Link da ferramenta [Poe](https://poe.com/login?redirect_url=%2F)
- Link da ferramenta [Bard](http://bard.google.com/)
- Link do navegador [Opera](https://www.opera.com/pt-br)
- O que é [VPN?](https://pt.wikipedia.org/wiki/Rede_privada_virtual)?
- Link da faculdade [FIAP](https://www.fiap.com.br/)

### Desafios desta aula

- Jogo de adivinhação de palavras
  A ideia é você escolher uma palavra aleatória e pedir ao ChatGPT para tentar adivinhar, dando uma dica por vez. Por exemplo, o ChatGPT pode começar dando a primeira letra da palavra e, em seguida, pedir a você para confirmar se essa letra faz parte da palavra escolhida. Se sim, ele pode dar a segunda letra e assim por diante. O objetivo do jogo é adivinhar a palavra com o menor número possível de dicas.

- Jogo de adivinhação de filmes
  Escolha um dos seus filmes favoritos e sugira ao ChatGPT que faça perguntas sobre a trama, os personagens, o gênero do filme ou a sua data de lançamento para tentar adivinhar qual é o nome do filme que você escolheu. O objetivo do jogo é que o ChatGPT adivinhe o nome do filme com o menor número possível de perguntas.

## AULA 02 - GPT NO SEU TRABALHO: FLUXO E DADOS

> Continuaremos a falar sobre aplicações práticas do GPT. Neste mergulho, vamos nos aprofundar um pouco mais e mostrar como você pode aproveitar todo o potencial do ChatGPT para arquivos que são muito comuns no seu dia a dia, como planilhas, JSON e CSV.

### Prompts da aula

- Resuma as críticas a seguir para o filme “Avatar”. Para cada uma delas diga qual é o sentimento, se é positivo, negativo ou neutro.
- Analise as críticas abaixo e me responda em português: Quantos filmes estão sendo analisados? Quais são os nomes de todos os filmes? Um resumo curto de cada filme, baseado nas críticas. Gere uma nota pra cada filme, baseado nas críticas.
- Dada a avaliação do filme a seguir, qual nota de 0 a 10 você acha que o avaliador deu?
- Tenho uma planilha de avaliações de filmes no google sheets, onde cada linha é uma avaliação. Na coluna A está o nome do filme e na coluna D está a nota do filme que pode estar em texto. Qual fórmula posso usar para agrupar os filmes com a média de suas notas?

### Links citados

- [Planilha](https://docs.google.com/spreadsheets/d/1qnOo2Gm-AeOjyZMQygmtvKIxxIUFCN9R_sWwZYy4QHc/edit?usp=sharing) com as críticas ao filme Avatar
- Arquivo [JSON](https://gist.github.com/fabriciocarraro/796e9e2f8fafac3712b33fc09c93c43e) com 20 filmes e sem as notas
- Arquivo [JSON](https://gist.github.com/fabriciocarraro/a1760940faf23eb5a264c79732dc27ac) com 20 filmes e com as notas
- [SheetGPT](https://sheetgpt.ai/) - Extensão para Google Spreadsheets
- Link da ferramenta [ChatGPT.openai](https://chat.openai.com/)
- Link para a ferramenta [Stable Diffusion](https://stablediffusionweb.com/)

### Desafios

- Crie 10 críticas variadas para filmes
  Peça ao ChatGPT para gerar 10 críticas variadas para outro filme. Em seguida, solicite que ele converta essas respostas para o formato CSV, copie esses valores e salve-os em um arquivo de texto (.txt). Depois disso, abra o Google Sheets, crie uma nova planilha e importe o arquivo .txt (em "Arquivo -> Importar -> Fazer upload"). Ao fazer essa importação, pode ocorrer um erro se o Google Sheets confundir as vírgulas de separação com vírgulas presentes no texto. Caso ocorra algum erro, peça ao ChatGPT para corrigi-lo.

- Sugira descrições de imagens para serem inseridas em outras IA's
  Utilize o ChatGPT para sugerir descrições de imagens que possam ser inseridas em outras inteligências artificiais, como o Stable Diffusion. Peça ao ChatGPT para criar 5 descrições de imagens com estilos diferentes, a fim de explorar essa combinação entre o ChatGPT e o Stable Diffusion.

- Calcule a média salarial de pessoas com o Google Sheets e o ChatGPT
  Usando a função GPT_LIST() do SheetGPT, gere 20 nomes de pessoas brasileiras na coluna A, a área de atuação dessas pessoas (como "Marketing", "TI", "Direito" ou "Saúde") na coluna B e 20 valores aleatórios de salário entre 1.000 e 20.000 na coluna C. Agora, peça ao ChatGPT para criar uma macro para o Google Sheets que calcule a média desses salários e mostre a resposta na célula D2.

## AULA 03 - ENGENHARIA DE PROMPT PARA TAREFAS COMPLEXAS

> Vamos mergulhar em engenharia de prompts e apresentar as principais técnicas utilizadas nesse processo. Além disso, iremos explorar o funcionamento do algoritmo do ChatGPT para que você possa adquirir domínio sobre essa ferramenta.

### Prompts da aula

- Vamos simular o funcionamento do ChatGPT. Para cada frase que você escrever no prompt, você deve listar as 5 palavras com maior probabilidade de completá-la, juntamente com a probabilidade de cada uma delas. Apenas as palavras e probabilidades, sem mais nada, certo?
- Resuma em português este texto.
- Crie um texto para LinkedIn para divulgar a Imersão em IA da Alura.
- Pergunta: Um diretor de cinema já dirigiu 16 filmes. Metade dos filmes que ele dirigiu são de ação, e metade dos filmes de ação conta com a participação do Nicolas Cage. Quantos filmes de ação com a participação do Nicolas Cage ele dirigiu? Resposta: A resposta em números é...

### Links utilizados na aula

- Link para o [ChatGPT](https://openai.com/blog/chatgpt)
- Ferramenta IA para otimizar o seu uso do Linkedin: [Engage-AI](https://engage-ai.co/)
- Link para o [Hipsters ponto tech](https://www.hipsters.tech/chatgpt-transformers-e-redes-neurais-hipsters-ponto-tech-352/)
- Link para o Artigo: [Whats is ChatGPT Doing… and why does it work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/)
- Link para o Artigo: [Large Language Models are zero-shot reasoners](https://arxiv.org/abs/2205.11916)
- Link para o Artigo: [Language Models Perform Reasoning via Chain of Thought](https://ai.googleblog.com/2022/05/language-models-perform-reasoning-via.html)
- Link para o Artigo: [Melhores práticas de uso do GPT](https://platform.openai.com/docs/guides/gpt-best-practices)
- Link para o Artigo: [Maieutic prompting (Técnica maiêutica)](https://github.com/openai/openai-cookbook/blob/main/techniques_to_improve_reliability.md#maieutic-prompting)
- Link para o Artigo: [Chain-of-thought Prompting Elicits Reasoning in LLM](https://arxiv.org/abs/2201.11903)

### Desafios do dia

- Explorando as respostas do ChatGPT
  Teste as respostas do ChatGPT quando você faz perguntas curtas, sem dar exemplos, e quando você elabora mais a pergunta, fornecendo um ou mais exemplos.

- Calculando Imposto com ChatGPT: Cadeia de Raciocínio e Valores da Planilha
  Utilize a lista de valores da planilha e o método Chain-of-Thought (Cadeia de raciocínio) no ChatGPT para obter o cálculo do valor do imposto a ser arrecadado. Considere que pessoas com rendimento de até R$20.000,00 pagam 10% de imposto, pessoas com rendimento entre R$20.000,00 e R$40.000,00 pagam 20% de imposto, e pessoas com rendimento acima de R$40.000,00 pagam 30% de imposto.

## AULA 04 - TAREFAS EM PLANILHAS COM IA E APIS

> Vamos mergulhar em um mundo de possibilidades ao explorar ferramentas de inteligência artificial que vão te ajudar no seu trabalho do dia a dia com planilhas e macros. E não para por aí! Você também conhecerá sobre os parâmetros usados para calibrar e controlar o GPT, e aprenderá como criar a sua própria ferramenta utilizando a API do GPT, uma técnica que te permitirá juntar diferentes recursos para automatizar tarefas e otimizar o seu trabalho.

### Prompts da aula

- Tenho uma planilha no Google Sheets com notas de alunos. Na coluna A está o nome do aluno e na coluna B a nota. Crie uma fórmula para filtrar os alunos com nota acima de 7.
- Tenho uma planilha no Google Sheets com uma lista de alunos e as notas de cada aluno em 4 diferentes provas. Quero uma função em App Script para calcular a nota final do aluno. Ela recebe as 4 notas das provas e devolve uma nota com o seguinte critério: Se o aluno tirou algum zero a nota final é 0; Senão a nota final é a média das 3 maiores notas.
- Escreva um email para um aluno de física para apresentar a nota dele no semestre. Nome: Marcelo Barbosa; Nota: 8,8.

### Links citados

- Link da ferramenta: [Script](https://www.google.com/script/start/)
- Link da ferramenta: [ChatGPT](https://chat.openai.com/)
- Link para a [OpenAI](https://openai.com/)
- Link da ferramenta: [Eightify](https://eightify.app/)
- Link da ferramenta: [Gamma](https://gamma.app/)
- Link da ferramenta: [Jasper](https://www.jasper.ai/free-trial?_from=ads&fp_sid=1-g-Cj0KCQjwnMWkBhDLARIsAHBOftp3-2_GQsww0SIqFbn0x56rZWHUlJDDIFeF8UskgLWHk9we0Us-dKAaAsk1EALw_wcB)
- Link para a [Planilha de notas](https://docs.google.com/spreadsheets/d/1jMZToQ1y5aThfBIG8U8H00V4CEdujRgn4hmuiXjjy5A/edit?usp=sharing) (Lembre-se de fazer uma cópia da planilha para conseguir editar)
- Link para o [Playground da OpenAI](http://platform.openai.com/)
- Link para o [GPT Tokenizer](https://gpt-tokenizer.dev/)
- Link para o [Código para gerar um email com a API do GPT](https://gist.github.com/sergiolopes/faf25d8781f4340edfc65a11b37ceb60)
- Link para a ferramenta: [ElevenLabs](https://elevenlabs.io/)
- Link para a ferramenta: [Whisper](https://huggingface.co/spaces/openai/whisper)
- Link para o conteúdo apresentado na live: [7 ferramentas de IA além do chatGPT](https://docs.google.com/presentation/d/1YWqJEKJxJToQNFKL-vpQ26ojem2oV60sxnD4TtB4dq0/edit?usp=sharing)

### Desafios do dia

1. Tokenização: Explorando o GPT-Tokenizer e o ChatGPT

Peça para o ChatGPT padrão gerar um texto curto sobre um assunto de seu interesse. Em seguida, acesse a página do GPT-Tokenizer, cole esse texto e observe como o modelo do GPT separa as palavras para gerar 'x' tokens.

2. Playground OpenAI: Brincando com Modelos e Temperaturas no Modo Chat

Crie uma conta na OpenAI, acesse o Playground, selecione o modo 'Chat' e experimente com os diferentes modelos e temperaturas. Gere o mesmo texto em diferentes temperaturas e analise as diferenças entre elas.

3. Gerando Mensagens com base em Notas dos Alunos: Usando a API_KEY

Usando o código do Sérgio e a sua API_KEY, faça a alteração no campo "content:" de 'role: "system"' no código, com o objetivo de gerar uma mensagem personalizada e carinhosa para cada aluno(a), com base na nota que ele(a) recebeu.

## AULA 05 - FLUXO DE TRABALHO: AUTOMAÇÃO NOCODE

> Chegou a hora de mergulhar no conceito de "No-code"! Vamos usar uma ferramenta em que você não precisa conhecer nenhuma linha de código, o Zapier. No Zapier é possível criar automações incríveis com diversas plataformas, do Gmail ao Twitter, do Google Sheets ao Instagram. Nele vamos criar uma automação para responder e-mails de forma automática, aproveitando todo o potencial do GPT. Prepare-se para descobrir como essa poderosa combinação de ferramentas pode transformar o seu trabalho!

> Ps: para encerrar a Imersão IA com chave de ouro, reservamos uma surpresa especial pra você mergulhar mais fundo em inteligência artificial e tecnologia! Fique de olho no seu e-mail, em breve você vai receber informações importantes!

## Links citados na aula

- Link da ferramenta: [ChatGPT](https://chat.openai.com/)
- Link para o [TechGuide](https://techguide.sh/)
- Link para a ferramenta: [Zapier](https://zapier.com/)
- Link para a plataforma da [OpenAI](https://platform.openai.com/)
- Link para a ferramenta: [IFTTT](https://ifttt.com/)
- Link para a ferramenta: [Whisper](https://huggingface.co/spaces/openai/whisper)
- Link para a ferramenta: [ElevenLabs](https://elevenlabs.io/)
- Link para a ferramenta: [PDF.co](https://pdf.co/)
- Código para chamada de API usando o [Google Colab](https://colab.research.google.com/drive/17B0fxL1lXCOPtOvUKBIHxbfsH1n5H9fS?usp=sharing)

## Desafios do dia:

1. Automação de categorização de tweets em uma planilha do Google Sheets

   Neste desafio, você deve criar um sistema automatizado para categorizar tweets em uma planilha do Google Sheets. A ideia é analisar campanhas de marketing nas redes sociais, especificamente aqueles que utilizam uma hashtag específica.

   Sempre que alguém postar um tweet com essa hashtag no Twitter, o sistema deve adicionar automaticamente o tweet a uma planilha do Google Sheets e categorizá-lo como "Positivo", "Negativo" ou "Neutro". Isso permitirá a análise da recepção da campanha e a possibilidade de aprimorar a estratégia de marketing.

   Você irá criar uma planilha no Google Sheets similar a esta, com as colunas "Usuário", "Tweet" e "Categoria". Depois, irá criar um novo Zap no Zapier, usando o Twitter como trigger (gatilho), e escolhendo a opção de busca por termo, utilizando a hashtag específica da campanha, como por exemplo #7DaysOfCode ou #ImersaoIA.

   Feito isso, você poderá adicionar mais uma ação, que será usar o ChatGPT para categorizar o tweet como "Positivo", "Negativo" ou "Neutro". Por fim, você terá outra ação, que será para adicionar as informações do tweet na planilha do Google Sheets que você já criou (pode escolher a opção de criar múltiplas linhas na planilha), e você irá mapear cada coluna para seu item correspondente, que virão ou do Twitter ou do ChatGPT.

2. Análise automática de currículos

   Você possui uma pasta no Dropbox onde os candidatos enviam seus currículos em formato PDF. Seu desafio é criar um fluxo automatizado que extraia os dados relevantes desses currículos e faça uma análise para determinar o nível de experiência de cada candidato.

   Para isso, primeiramente você irá criar uma conta gratuita no PDF.co para acessar os dados de um PDF e converter arquivos PDF em texto, e obterá sua API KEY.

   Em seguida, crie uma planilha no Google Drive similar a esta, com as colunas: "Nome completo", "Email", "Telefone", "Nível" e "Análise".

   Com isso pronto, você irá começar um novo Zap no Zapier, e o trigger será a adição de um arquivo PDF a uma pasta sua no Dropbox. No app da PDF.co, configure o evento "PDF to Anything Converter" e insira sua API KEY. Defina o formato de saída como "Plain text without layout...". Preencha o campo "Source PDF URL" com o "1. Share link" do arquivo PDF no Dropbox. Selecione o idioma como "Portuguese".

   Agora sim, você vai brincar com o ChatGPT. Você pode adicionar várias ações dele uma depois da outra. Cada ação irá extrair dados diferentes do texto do currículo:

   - Na primeira ação, extraia apenas o nome completo do candidato.
   - Na segunda ação, extraia apenas o email do candidato.
   - Na terceira ação, extraia apenas o telefone do candidato.
   - Na quarta ação, faça a análise do currículo. Avalie anos de experiência, projetos relevantes e tecnologias com as quais o candidato trabalhou. Classifique o nível do candidato como Júnior, Pleno ou Sênior.
   - Na quinta e última ação, analise a resposta anterior do ChatGPT e responda com uma palavra se o candidato é Júnior, Pleno ou Sênior.
   - Por fim, insira os dados extraídos na planilha criada usando uma ação do Google Sheets no Zapier (pode escolher a opção de criar múltiplas linhas na planilha).

## Notion Guia de Mergulho

[Link](https://grupoalura.notion.site/Imers-o-Intelig-ncia-Artificial-IA-Guia-do-Mergulho-dec0aacfadeb45039f0424a27b5c51eb)

## Rede sociais

- LinkedIn e Instagram Alura: @AluraOnline
- LinkedIn e Instagram Paulo: @paulo_hipster
