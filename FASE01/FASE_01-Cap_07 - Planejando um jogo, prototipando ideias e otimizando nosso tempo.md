# Capítulo 07 – Planejando um Jogo, Prototipando Ideias e Otimizando Nosso Tempo

---

## 1. Como Planejar um Jogo?

O planejamento é essencial para o desenvolvimento de qualquer jogo. Após definir a ideia, é preciso se organizar para cumprir todas as etapas do projeto dentro do prazo, considerando que diversas áreas trabalham em conjunto em momentos específicos.

O planejamento traz clareza ao dimensionamento das etapas: o que parecia um projeto gigante e impossível torna-se palpável, com metas realistas dentro das capacidades de produção. Além disso, o acompanhamento diário é indispensável, pois imprevistos acontecem e, sem replanejamento constante, o projeto fica cada vez mais difícil de controlar.

---

### 1.1 Organização por Áreas

Ao iniciar a construção de um game, é importante ter noção de todas as áreas envolvidas na produção. A quantidade e o tipo de áreas pode variar conforme o tamanho do game (game jam, empresa pequena, empresa grande etc.).

**Áreas comuns em um projeto de jogo:**

1. **Programação**
   - *Back-end*: informações enviadas a servidores (rankings online, estatísticas de partidas multiplayer, download de novos conteúdos etc.)
   - *Front-end*: parte com que o jogador interage diretamente (indicadores de vida, resposta a controles, carregamento de cenários etc.)

2. **Arte**
   - Produção dos assets: personagens, cenários, objetos etc.

3. **Animação**
   - Animações de personagens, cenários e objetos (correndo, andando, caindo, atacando etc.)

4. **Motion**
   - Animação de janelas, transições e efeitos de telas (abertura do menu, troca de telas, seleção de personagem etc.)

5. **Game Design**
   - Definição e descrição do jogo: mecânica principal, ambientação, narrativa, número de jogadores, modo competitivo ou cooperativo, condições de vitória etc.

6. **QA (Quality Assurance)**
   - Testes do jogo: colisões, indicadores, pontuação, carregamento de modelos, bugs em geral etc.

7. **Gerenciamento**
   - Controle de datas e prazos.
   - Monitoramento de atividades: quem está sem trabalho? Por quê? Há bloqueios entre áreas?

8. **Música**
   - Trilha sonora de cada momento do jogo: menu principal, gameplay, enfrentamento de chefes etc.

9. **Efeitos Sonoros**
   - Feedback sonoro de cada ação: dano recebido, ataque acertado, vitória etc.

10. **Comunidade e Social**
    - Interação com o público-alvo: redes sociais, administração de páginas, promoções, anúncios e contato direto com jogadores.

> Antes de iniciar o projeto, faça a listagem de todas as áreas, defina responsabilidades e identifique o que precisará ser feito em cada uma delas.

---

### 1.2 Etapas do Projeto

Uma boa prática é quebrar o jogo em várias etapas menores, subdividindo a meta final em objetivos mais "alcançáveis". Ao agregar esses objetivos, o resultado é o game final.

#### Etapa 1 – Planejamento

| Atividade | Responsabilidade |
|---|---|
| Produção do PIV | Arte |
| Validação do PIV | Cliente |
| Definição dos conteúdos | Cliente |
| Reunião de Kick-off | Equipe e Cliente |
| Alinhamento de requisições técnicas | Equipe e Cliente |
| Criação do fluxo do game | Game Designer |
| Validação do fluxo | Cliente |
| Definição do conteúdo das situações | Cliente |

Nessa etapa, o cliente tem papel central trazendo o conteúdo que será aplicado no game e validando a linha visual (PIV – Proposta de Identidade Visual) e o fluxo macro do jogo.

> **Atenção:** Evite dar seguimento ao projeto sem ter todas as atividades anteriores finalizadas e validadas. Vale mais ter certeza do que será produzido do que produzir errado e ter que refazer.

---

#### Etapa 2 – Pré-produção

| Atividade | Responsabilidade |
|---|---|
| Desenvolvimento do GDD | Game Designer |
| Criação dos wireframes | Game Designer |
| Criação da demanda de motions/animações | Game Designer |
| Criação dos personagens | Arte |
| Validação dos personagens | Cliente |
| Criação dos cenários | Arte |
| Validação dos cenários | Cliente |
| Criação das narrativas e textos | Equipe e Cliente |
| Validação das narrativas e textos | Cliente |

A pré-produção abrange tudo que precisa estar pronto antes do desenvolvimento pleno. O GDD (Game Design Document) é central nessa etapa: é a partir dele que se obtêm as respostas sobre como o jogo será e o que precisará ser produzido. A produção de arte (personagens e cenários) nessa fase dá bons insumos para a etapa de produção.

> A falta de uma definição na pré-produção pode custar tempo e dinheiro no desenvolvimento.

---

#### Etapa 3 – Produção

Nessa etapa há muito mais atividades e poucas envolvem o cliente diretamente, pois todas as validações já foram feitas. Cabe à equipe de desenvolvimento produzir o jogo em si.

O cliente volta a se envolver ao final desta etapa com a **validação beta** — uma validação "quase" completa do jogo.

O papel do Game Designer nessa etapa é apoiar a equipe tirando dúvidas e testando e validando o que foi produzido. Mesmo com um GDD detalhado, quem for produzir pode ter dúvidas ou interpretações diferentes. Estar próximo da equipe é crucial para que o que foi planejado seja entregue do jeito esperado.

---

#### Etapa 4 – Qualidade

Terminar o jogo não garante que ele está funcionando corretamente. A etapa de qualidade é necessária para ajustar bugs e outros problemas encontrados. Essa etapa pode se estender pelas diversas validações e pela complexidade do jogo, por isso é importante que haja revisões de qualidade ao longo da produção, e não apenas ao final.

---

#### Etapa 5 – Entrega

Ao garantir uma versão 100% funcional do game, chega-se à etapa de entrega (para um cliente ou para publicação em plataformas como Steam ou Google Play). Nela, são finalizados os últimos ajustes e o produto fica disponível para o público.

> Dividir o game em etapas claras facilita o controle do andamento e permite ter uma visão melhor do que acontece e do que precisa ser feito.

---

## 2. SCRUM

O **SCRUM** é um framework de gestão e planejamento utilizado em desenvolvimento de software que usa um estilo de "ondas" incrementais no projeto, sempre melhorando o produto a cada nova versão.

A ideia central é quebrar grandes projetos em vários ciclos de semanas (**Sprints**) para que, ao final de cada ciclo, seja produzido algo que incrementa o produto final.

### Principais Conceitos e Rituais

- **Product Backlog** – Lista de tudo que precisa ser feito no projeto, do começo ao fim. É criada em uma reunião geral com todas as áreas, tendo a ideia do projeto finalizada. É o primeiro passo para o detalhamento de tudo que será feito para entregar o produto final.

- **Sprint** – Parte do projeto; ciclo que pode durar de 1 a 3 semanas. Define o foco da equipe nas próximas semanas. Sempre tem um objetivo e deve entregar uma melhoria palpável para o projeto (ex.: finalizar a construção de todos os personagens, prototipar e definir a mecânica base, testar a tecnologia prevista etc.).

- **Sprint Planning Meeting** – Reunião de definição da Sprint a partir do Product Backlog. Define o que será feito nas próximas semanas.

- **Sprint Backlog** – Lista de atividades da Sprint gerada após a reunião de planejamento, com tudo que precisa ser feito para entregar o que foi combinado.

- **Daily SCRUM** – Reunião diária e curta. Cada membro responde a três perguntas:
  1. O que fiz ontem?
  2. O que vou fazer hoje?
  3. Existe algo impedindo o meu trabalho?
  
  Serve para acompanhar diariamente o andamento e identificar impedimentos que possam atrapalhar a Sprint.

- **Sprint Review** – Reunião ao fim da Sprint. Analisa tudo que foi feito e o que pode ser mudado para ganhar velocidade de produção, melhoria de qualidade e outros fatores. A ideia é melhorar o processo ao longo do tempo.

> Ao montar a Sprint, pense: o que é mais crítico para a entrega do jogo? Identificar prioridades ajuda a definir se o projeto está adequado ou precisa de ajustes.

---

## 3. Trello

O **Trello** é uma ferramenta de organização e gerenciamento de projetos que permite criar listas de atividades divididas por tarefas, ajustáveis conforme a necessidade. Com ele, é muito mais fácil acompanhar o andamento do projeto.

> Acesse: [https://trello.com/](https://trello.com/)

> **Lembrete importante:** as ferramentas e metodologias só funcionam se usadas diariamente. Quanto mais tempo você deixar de controlar, mais tempo levará para retomar a produção de forma saudável e produtiva.

### Estrutura do Quadro no Trello

| Coluna | Significado |
|---|---|
| **TO DO** | Atividades a fazer |
| **DOING** | O que está sendo feito no momento |
| **QA** | Em fase de testes |
| **DONE** | Concluído |

Todas as atividades do Product Backlog entram na lista **TO DO** e, conforme são realizadas, avançam da esquerda (TO DO) para a direita (DONE).

### Dicas de Uso do Trello

- Insira todas as atividades do Product Backlog na lista TO DO para ter visão completa do esforço necessário.
- Quanto mais detalhadas as atividades, melhor a visualização real do que precisa ser produzido (ex.: no card "GDD", insira sub-atividades: pegar o modelo, definir as mecânicas, a estética, a história etc.).
- Atribua responsáveis a cada card para saber quem está fazendo o quê e identificar atividades sem dono.
- Insira datas nos cards para controlar quando cada atividade deveria iniciar e terminar.
- Atualize o status das atividades diariamente.

A força do Trello está em dar visibilidade geral ao time. Combinado com cerimônias do SCRUM como a Daily, ajuda o time a se alinhar e antecipar possíveis problemas.

### Outras Ferramentas

Além do Trello, outras ferramentas podem ser usadas para gerenciamento de projetos de jogos:

- **ClickUp**
- **Hack N Plan**
- **Codecks**

> O importante é controlar as etapas do game, independentemente da ferramenta escolhida.

---

## 4. Prototipando Ideias e Otimizando o Tempo

### 4.1 Escolha uma Ideia e Siga em Frente

Durante o processo de criação de um jogo, surgem várias ideias. As perguntas comuns nesse momento são:

- Dentre todas as ideias que surgiram, qual é a melhor?
- Qual é a ideia mais fácil de produzir?
- De qual ideia os meus jogadores vão gostar mais?

#### Pense de Forma Racional

Não é possível se "apaixonar" por uma ideia a ponto de ignorar alternativas melhores. É preciso ter consciência de que mudar o design ou o projeto, quando necessário, faz parte do processo.

**Registre cada ideia.** Uma ideia não registrada ocupa espaço mental e impede que outras surjam. Ao documentar uma ideia, o cérebro "libera" espaço e novas ideias aparecem. Com o tempo, esse hábito gera um acervo valioso de conceitos que podem virar jogos futuros.

Quando uma ideia parecer interessante, o primeiro passo é se comprometer com ela. Durante o projeto, haverão momentos de dúvida sobre decisões tomadas, mas é preciso ser persistente: só é possível desenvolver um game se houver comprometimento com uma ideia.

---

## 5. Avaliação de Riscos

### 5.1 Os Oito Filtros de Jesse Schell

Com a ideia definida, os primeiros passos são detalhar os aspectos do jogo: História, Estética, Mecânicas e Tecnologia. Nesse processo, podem ser aplicados os **oito filtros de Jesse Schell**, que permitem questionar se o caminho tomado é o melhor.

1. **Impulso artístico** – *Qual é a sua sensação em relação ao design do jogo?*
   - Totalmente subjetivo. Se algo incomoda — mesmo sem saber o que é — é preciso investigar e definir o que precisa mudar.

2. **Público-alvo** – *Os jogadores vão gostar do jogo?*
   - O jogo é feito para alguém jogar. É preciso entender gostos e desejos do público-alvo.
   - Pesquise jogos similares, leia reviews em lojas como Play Store ou Steam, analise comunidades no Facebook, Instagram e TikTok. Identifique: quem são essas pessoas? Faixa etária? O que comentam? Que outros jogos também gostam?

3. **Design da experiência** – *O jogo tem um design bem-feito?*
   - O jogo está muito difícil ou muito fácil? É difícil entender o que precisa ser feito? Os feedbacks são confusos? Todos esses fatores influenciam a percepção de qualidade pelo jogador.

4. **Inovação** – *Esse jogo é inovador?*
   - Inovação ajuda a se destacar no mercado. Quanto mais inovador, mais chances de chamar atenção.
   - Porém, inovar demais pode criar algo que poucas pessoas entendam ou gostem. A recomendação é inovar em elementos dentro de um gênero já conhecido, e não tentar criar um gênero totalmente novo.
   - Referência: *Grand Theft Auto 3* foi um dos precursores do estilo mundo aberto, amplamente difundido hoje.

5. **Negócios e marketing** – *Esse jogo vende?*
   - O objetivo final é criar jogos rentáveis. Uma ideia tecnicamente perfeita não se sustenta se não houver quem a compre.
   - O marketing garante que jogadores potencialmente interessados saibam que o jogo existe.

6. **Desenvolvimento** – *É possível produzir o game tecnicamente?*
   - Muitos jogos, de empresas grandes ou pequenas, ficam anos em produção e nunca são lançados. Complicações técnicas subestimadas consomem tempo e dinheiro.
   - Olhar friamente o que será necessário para o desenvolvimento é essencial para entender se vale a pena começar o projeto e se será possível entregá-lo.

7. **Comunidade e social** – *O jogo atinge os objetivos sociais e de comunidade?*
   - Para jogos com aspectos sociais (multiplayer), é preciso avaliar se o jogo oferece as ferramentas necessárias para que os jogadores se conectem facilmente. Dificuldades de conexão afetam diretamente a percepção do game.

8. **Playtesting** – *Quem faz o playtest está gostando?*
   - É o momento de verificar se o que foi imaginado é realmente divertido para os jogadores.
   - Observar com crítica a experiência de quem testa e anotar informações é essencial para melhorar o produto antes do lançamento.

> Os filtros são bons pontos de partida para avaliar o Design. Aplicados constantemente ao longo de todo o projeto, ajudam a ajustar a percepção do que é divertido para o criador e o que o jogador realmente acha divertido.

---

### 5.2 Tetraedro dos Elementos do Jogo

Mesmo com os filtros aplicados, riscos existem em qualquer projeto. Uma forma de prever possíveis problemas é usar o **Tetraedro dos Elementos do Jogo**, de Jesse Schell, isolando cada aspecto do game.

O Tetraedro organiza as quatro grandes áreas do jogo da seguinte forma:

| Posição | Elemento | Visibilidade para o jogador |
|---|---|---|
| Topo | **Estética** | Mais visível |
| Lado | **Mecânicas** | Visível |
| Lado | **História** | Visível |
| Base | **Tecnologia** | Menos visível |

Todos os elementos são importantes e podem apresentar riscos ao projeto, impactando a percepção de qualidade. Por exemplo: um game multiplayer ótimo em todos os outros aspectos pode ser arruinado se os jogadores não conseguirem se conectar aos servidores (problema de Tecnologia).

> Se um elemento tiver problemas, os outros não importarão — o jogador achará o jogo "ruim". Por isso, o Tetraedro é usado para identificar riscos antes do desenvolvimento, por meio de protótipos.

---

## 6. Protótipo

### 6.1 Por Que Fazer Um?

O protótipo é uma forma de testar um aspecto do jogo antes de se comprometer com a produção completa, economizando tempo e dinheiro, e confirmando que o que será produzido terá o efeito desejado.

### Regras Básicas do Protótipo

- **Baixo custo** – Deve ser básico. Se estiver muito detalhado, não é um protótipo.
- **Rápido** – Se levar muito tempo para fazer, já não é um protótipo.
- **Específico** – Deve responder apenas a algumas dúvidas definidas.
- **Descartável** – Se não funcionar como esperado, pode ser jogado fora sem problemas.
- **Não precisa ser digital** – Protótipos de papel funcionam muito bem. Quanto mais simples, melhor.
- **Precisa de prioridades** – Qual é a pergunta mais importante que precisa ser respondida?

> Definir explicitamente o que precisa ser resolvido facilita a produção e foca o desenvolvimento. Quanto mais perguntas forem respondidas pelo protótipo, menos risco se corre na produção do jogo.

### 6.2 Exemplos Práticos de Protótipos

Usando o Tetraedro dos elementos, define-se o que precisa ser validado antes de produzir:

**Exemplo 1 – Estética:**
- *Dúvida:* Tenho uma ideia para um jogo mobile e quero que o jogador ache engraçado o design dos personagens.
- *Protótipo:* Criar o personagem principal em diversos estilos visuais (pixel art, realista, voxel art, cartoon etc.) e apresentar ao público-alvo para colher percepções.

**Exemplo 2 – História:**
- *Dúvida:* A história é complexa e com diversos personagens. O jogador pode se perder.
- *Protótipo:* Descrever algumas cenas e personagens, apresentar para a equipe ler sem instruções adicionais e pedir que cada um descreva o que entendeu.

**Exemplo 3 – Mecânicas:**
- *Dúvida:* A mecânica exige física com colisão e ricocheteio. Talvez não seja tão divertido quanto imaginado.
- *Protótipo:* Criar uma aplicação simples com cubos, esferas e cilindros para testar os efeitos sem personagens ou outros detalhes visuais.

**Exemplo 4 – Tecnologia:**
- *Dúvida:* Um jogo de mundo aberto com muitos elementos na tela pode não carregar bem nos consoles.
- *Protótipo:* Gerar uma versão do jogo com a maior quantidade de objetos na tela possível. O game fica mais lento? Trava? Ir cortando pela metade até achar o limite ideal.

---

## 7. Testar, Testar e Testar

Os protótipos garantem que as ideias estão de acordo com o que o projeto precisa, sem comprometer muito tempo e dinheiro. É normal descobrir, após protótipos, que uma ideia não é tão boa quanto se imaginava ou que levará mais tempo do que o disponível.

> **Não descarte ideias.** Guarde-as em local de fácil acesso. Uma ideia descartada hoje pode ser a mecânica principal do seu próximo projeto. Todo conhecimento gerado serve em algum momento da carreira.

> **Cuidado com a paixão pelas próprias ideias** – isso pode custar o desenvolvimento do seu game.

---

## Referências

- SCHELL, Jesse. *The Art of Game Design: A book of lenses*. Boca Raton, FL: CRC Press, 2014.
- SUTHERLAND, Jeff. *Scrum: a arte de fazer o dobro do trabalho na metade do tempo*. São Paulo: Leya, 2016.
