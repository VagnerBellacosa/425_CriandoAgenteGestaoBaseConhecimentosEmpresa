[**](https://web.dio.me/track/nublify-primeiros-passos-em-ia-e-cloud)

##### Criando um Agente de Gestão de Base de Conhecimentos de uma Empresa

**

**

**

# Entendendo o Desafio

Agora é a sua hora de praticar, aprender fazendo e construir um projeto que mostra como você pensa uma solução em nuvem. Neste desafio, você vai propor uma arquitetura na **AWS** para um problema que quase toda empresa tem: documentos importantes espalhados em formatos que ninguém consegue consultar. Antes de começar, acesse o repositório:

**Repositório Do Desafio:**
https://github.com/digitalinnovationone/laboratorio-wiki-aws

Dentro dele estão a pasta `raw/` e o `resposta.md`, onde você escreve a solução.

## O Que Criar

A empresa guarda registros comerciais soltos em uma pasta só, sem organização. Seu objetivo é propor, usando serviços da AWS, como transformar esse acervo em uma base consultável em linguagem natural. Alguém pergunta *"qual foi a decisão sobre o projeto X"* e a solução responde citando o documento de onde tirou a informação.

São três arquivos, e nenhum se parece com o outro:

- Uma **ata em PDF** de cinco páginas, que já nasce com o texto dentro;
- Uma **folha digitalizada**, que é só imagem e ainda traz anotações à mão;
- Uma **exportação do CRM** em CSV, com centenas de oportunidades em dezenove colunas.

O `resposta.md` organiza esse caminho em 4 Quests:

1. **O Mapa dos Arquivos Perdidos:** que documentos existem e o que extrair deles;
2. **O Portal de Entrada na AWS:** como eles entram, ficam guardados e viram texto;
3. **A Relíquia dos Metadados:** como padronizar, enriquecer e organizar esse texto;
4. **O Oráculo da Wiki Inteligente:** como indexar, buscar e responder com IA.

**Tratar os três do mesmo jeito não funciona**, e é aí que mora o desafio. Justificar o caminho de cada um separa uma proposta genérica de uma proposta de verdade.

## Como Fazer

Comece abrindo os três arquivos. Depois releia as **Regras da Expedição** no README: apenas serviços da AWS, nada de ferramenta externa de OCR ou IA, e não altere o `raw/`. Está tudo solto no mesmo diretório, sem subpastas, e é essa regra que torna a classificação um problema de verdade.

Depois desenhe o caminho do dado, do arquivo que chega até a resposta que sai. Para cada etapa, escolha um serviço e escreva **por que** ele. "Usei o Amazon Textract" diz pouco. "Usei o Textract porque parte das atas são fotos, e sem OCR esse conteúdo não entra na base" diz o que você entendeu.

Não é preciso implementar nada: uma proposta bem argumentada já atende. Mostrar algo rodando na AWS é bônus.

## Ideias Para Evoluir

Depois de fechar a proposta principal, você pode ir além:

- Automatizar a ingestão, para um arquivo novo entrar na base sozinho;
- Classificar documentos por tipo, área ou confidencialidade;
- Adicionar autenticação e restringir o acesso por perfil;
- Estimar o custo mensal e discutir alternativas mais baratas;
- Definir o que a Wiki responde quando a base não tem a informação.

Se você ainda está começando, tudo bem. Uma melhoria pequena, bem explicada e coerente vale mais que uma ideia grande pela metade.

## Uma Ajuda Durante O Caminho

Se travar, o [DIO Agent](https://github.com/digitalinnovationone/dio-agent) ajuda a destravar o raciocínio:

```
Estou fazendo o Desafio de Projeto do Bootcamp Nublify.

Repositório: https://github.com/digitalinnovationone/laboratorio-wiki-aws

Me ajude a entender que tipos de documento existem na pasta raw/
e quais deles precisam de OCR antes de virarem texto pesquisável.

Não quero a arquitetura pronta. Quero entender o problema
para desenhar a minha.
```

## O Que Entregar

Dê um fork no repositório ou crie o seu no GitHub. Preencha o `resposta.md` pelas quatro Quests, começando pela identificação. No `README.md`, explique:

- Qual problema o projeto resolve;
- Como a sua arquitetura funciona, do arquivo bruto até a resposta;
- Quais serviços você escolheu e por quê;
- Como você trata cada um dos três formatos;
- O que você aprendeu durante o desafio.

Diagrama, prints e exemplos de uso contam muito. Evidência de que a solução saiu do papel é o que mais chama atenção em um portfólio.

Antes de submeter, confira:

- O `resposta.md` está preenchido, sem sobrar nenhum `Preencha aqui`;
- Todo arquivo e pasta citada no README existem e têm conteúdo;
- O link enviado é o do repositório, não o de um arquivo dentro dele;
- O repositório está na sua conta e público;
- O nome ficou legível, em minúsculas e sem acento.

## Resultado Esperado

Ao final, você terá uma proposta que leva um acervo bagunçado até uma resposta em linguagem natural. Mais que a lista de serviços, vale o raciocínio: quem abre o seu repositório precisa entender o problema, o caminho que você escolheu e por que ele faz sentido. É esse tipo de projeto que rende conversa em entrevista.

Bons estudos e bom projeto 🚀

XP 520895/561017

NÍVEL 42

**5/5**

- CONTEÚDOS
- INFORMAÇÕES

Criando um Agente de Gestão de Base de Conhecimentos de uma EmpresaEntendendo o Desafio