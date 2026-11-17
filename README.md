# LearnLab&lt;/&gt; ✦

Criei este projeto para organizar meu estudo contínuo de Java e IA e transformar o que aprendo em prática de back-end, com foco em tecnologia bancária.

A ideia é ter um lugar para decidir o que estudar hoje, acompanhar minha semana e registrar o que consegui implementar, o que deu errado e o que ainda preciso entender. Quero construir essa evolução aos poucos, com sessões de cerca de uma hora e projetos que eu consiga explicar tecnicamente.

## A cara do meu laboratório

Escolhi uma estética feminina geek/dev: fundo escuro, lilás, rosa neon, grade de terminal e uma ilustração original de dev com headset de gatinho. A decoração reúne referências pessoais a anime, games, Bistecone, Alanzoka e Peter Jordan, do Ei Nerd.

O nome do sistema é **LearnLab</>**. Brew & Code continua como um dos meus projetos de prática dentro dele.

## Duas áreas de estudo

Adicionei uma barra no topo para alternar entre **Java** e **CPA**. O painel abre em Java por padrão. Cada área tem seus próprios registros, progresso, histórico, revisões e backup; os dados anteriores de Java continuam na mesma chave de armazenamento.

Na CPA, organizei um mapa resumido dos quatro blocos do programa da ANBIMA: sistema financeiro, produtos, relacionamento e inovação. Também incluí plano diário, semana, data planejada da prova, oito questões autorais com correção, caderno de erros, registro de simulados externos, transcrições e glossário.

O treino local é introdutório e não estima aprovação. O programa completo e suas atualizações devem ser consultados na [Central de documentos da ANBIMA](https://anbimaedu.com.br/central-documentos). A base foi consultada em 17/11/2026.

A exportação e a restauração de backup se aplicam à área selecionada. Para guardar Java e CPA, exporte um arquivo em cada área.

## Meu ponto de partida

- Bootcamp Java com IA do Itaú/DIO.
- Exercícios Java que já pratiquei e quero organizar.
- Projeto Brew & Code.
- Desafio Tech Sisters.
- Aprendizados recentes de SQL, ML, RAG e IA/automação.

Esses temas já aparecem no painel como pontos de partida. Os enunciados, soluções e anotações específicos ainda precisam ser adicionados por mim; o progresso não parte de atividades presumidas como concluídas.

## O que tem no painel

- Plano de estudo diário com revisão, teoria, prática e registro.
- Visão semanal e trilhas de Java, IA e back-end bancário.
- Registro de exercícios, desafios e avanços dos projetos.
- Revisão espaçada com intervalos de 1, 3 ou 7 dias.
- Registro de erros, dúvidas, tentativas e soluções.
- Biblioteca para colar transcrições, escrever resumos e manter um glossário técnico e financeiro.
- Comparações de implementações Java, com explicações passo a passo, linha a linha, alternativas e casos especiais.
- Histórico de prática e uma visão de competências para estágio, trainee e júnior.
- Exportação e restauração dos dados em JSON.

## O que quero praticar

No Brew & Code e nos outros projetos, quero trabalhar com APIs REST, validação, testes, bancos de dados, transações, idempotência, microsserviços, AWS e fluxos de pagamentos. Na parte de IA, quero explorar ML, RAG e automação com atenção à avaliação das respostas e ao uso dos dados.

As explicações seguem uma abordagem técnica e direta, sem analogias aleatórias do cotidiano. Meu objetivo é entender as decisões por trás do código e comparar formas diferentes de resolver o mesmo problema.

## Como executar

O painel foi feito com HTML, CSS e JavaScript, sem dependências de aplicação e sem etapa de build.

1. Clone o repositório:

   ```bash
   git clone https://github.com/bru-ddecor/LearnLab_Java.git
   cd LearnLab_Java
   ```

2. Inicie um servidor estático. Se tiver Python 3 instalado:

   ```bash
   python3 -m http.server 8000
   ```

3. Acesse [http://localhost:8000](http://localhost:8000).

## Estrutura

```text
LearnLab_Java/
├── index.html   # Estrutura do painel
├── style.css    # Estilos e layout responsivo
├── app.js       # Navegação, registros, progresso e armazenamento local
├── cpa.js       # Área CPA e alternância entre as duas jornadas
├── theme.css    # Identidade visual feminina geek/dev
├── assets/
│   └── dev-orbit.svg # Ilustração original
└── README.md
```

## Como os dados são salvos

As informações ficam no `localStorage` do navegador. Por enquanto, não há login próprio, banco de dados nem sincronização entre dispositivos. Limpar os dados do navegador pode apagar os registros, então o painel permite exportar um backup em JSON e restaurá-lo depois.

Os resumos de aulas são preenchidos manualmente a partir de um roteiro. Esta versão não faz chamadas a modelos de IA. A fonte tipográfica é carregada do Google Fonts, com fontes alternativas caso ela não esteja disponível.

## Uso do Codex

Usei o **Codex, da OpenAI**, como apoio para transformar minha ideia em uma primeira versão do site, incluindo a estrutura, o visual, as funcionalidades em JavaScript e este README. Os objetivos e temas de estudo vieram do que quero desenvolver na minha jornada.

Quero usar essa base também como material de estudo: ler o código, entender as escolhas, testar os comportamentos e fazer minhas próprias melhorias ao longo do tempo.

## Próximos passos

- [ ] Adicionar meus exercícios e anotações reais.
- [ ] Detalhar os requisitos e as entregas do Brew & Code.
- [ ] Registrar os desafios do Tech Sisters.
- [ ] Ampliar as comparações de implementações Java.
- [ ] Fazer uma revisão visual e de acessibilidade no navegador.
- [ ] Estudar como implementar persistência e autenticação em uma futura versão com back-end Java.

Este repositório acompanha meu aprendizado. Vou atualizar o projeto conforme avanço nos estudos e na prática.
