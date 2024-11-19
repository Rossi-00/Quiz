### **README.md**

```markdown
# Quiz de Fatos Históricos

Este é um projeto de quiz interativo sobre eventos históricos importantes. O objetivo é testar seus conhecimentos sobre marcos históricos e as datas em que ocorreram.

O quiz é composto por 30 perguntas de múltiplos eventos históricos, e a aplicação seleciona aleatoriamente 10 perguntas para você responder. Ao final, é exibida a sua pontuação, juntamente com uma mensagem sobre o seu desempenho.

## Funcionalidade

- O jogador será desafiado a responder perguntas sobre eventos históricos, fornecendo o ano correto.
- A pontuação final será calculada com base nas respostas corretas, e uma mensagem personalizada será exibida ao jogador, dependendo da pontuação alcançada.

## Como Funciona

A aplicação utiliza um banco de perguntas históricas com 30 questões, selecionando 10 delas aleatoriamente para o quiz. O jogador deve digitar a resposta (o ano do evento) para cada uma das perguntas. Ao final do quiz, a pontuação e uma mensagem com o feedback sobre o desempenho do jogador são exibidas.

## Como Usar

### 1. Clone este repositório:

```bash
git clone https://github.com/rossi-00/quiz.git
cd quiz-fatos-historicos
```

### 2. Instale as dependências:

Este projeto depende do pacote `readline-sync` para coletar as respostas do jogador. Você pode instalar as dependências usando o seguinte comando:

```bash
npm install 'readline-sync'
```

### 3. Execute o Quiz:

Após instalar as dependências, basta rodar o seguinte comando para iniciar o quiz:

```bash
npm run dev
```

O quiz será iniciado, e você poderá responder às perguntas no console.

### 4. Interaja com o Quiz:

- O quiz exibirá uma série de perguntas.
- O jogador deverá digitar o ano correto para cada pergunta.
- A pontuação será exibida no final, junto com uma mensagem sobre o desempenho.

## Exemplo de Execução

Aqui está um exemplo de execução do quiz no terminal:

```
--------QUIZ DE FATOS HISTÓRICOS--------

Seja Bem-vindo jogador(a)!

Digite o seu nome: João

1: Quando aconteceu o atentado às Torres Gêmeas?
Digite a resposta (ano): 2001
Resposta correta!

2: Em que ano foi detectado o primeiro paciente com coronavírus?
Digite a resposta (ano): 2019
Resposta correta!

...

Jogador(a): João
Pontuação final: 7 acertos.
BOM TRABALHO! Pratique um pouco mais.
```

Com isso, você pode rodar o quiz com o comando:

```bash
npm run dev
```
