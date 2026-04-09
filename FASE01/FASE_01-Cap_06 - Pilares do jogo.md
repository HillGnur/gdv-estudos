# Capítulo 06 – Pilares do Jogo

## Visão Geral

O capítulo aborda os três pilares fundamentais do Game Design: **História**, **Estética** e **Mecânicas/Sistemas**. Cada pilar sustenta a experiência do jogador e deve estar alinhado com os demais para que o jogo seja coeso e bem-sucedido.

---

## Pilar 1 – História (Narrativa)

### A importância da amarração narrativa

A história de um jogo precisa estar integrada com seu contexto interno. O exemplo do jogo *Ronin: The Last Samurai* ilustra como detalhes visuais e de gameplay (como o próprio dinheiro do jogo) reforçam a narrativa e mantêm a imersão. Quanto mais a história estiver entrelaçada com os outros elementos do jogo (visual, som, gameplay), mais poderosa será a experiência.

---

## 2. Tipos de História

O capítulo diferencia dois grandes caminhos para trabalhar narrativa em jogos.

### 2.1 A história que surge

É a história que nasce das próprias partidas e das situações criadas pelos sistemas do jogo. Ela não depende, necessariamente, de uma narrativa tradicional roteirizada.

Exemplos citados no material:

- *The Sims*
- *Battlegrounds*
- *Tycoon*
- *Rocket League*

Nesses casos, o jogador constrói a sua própria história a partir das ações realizadas durante a experiência.

### 2.2 A história que é contada

É a história planejada para ser entregue ao jogador de forma mais estruturada. O material destaca que ela pode aparecer em dois formatos principais:

- **Linear** — segue uma progressão mais controlada
- **Ramificada** — muda de acordo com as decisões tomadas

---

## 3. Tipos de Histórias Contadas

### 3.1 Furi

*Furi* é usado como exemplo de **história contada linear**. O capítulo mostra que o jogo escolhe uma narrativa mais enxuta, com trechos curtos e rápidos, porque a experiência principal está centrada na ação intensa e na atenção constante do jogador.

Assim, a história entrega apenas o mínimo necessário para manter o jogador conectado ao que está acontecendo, sem competir com a ação principal.

### 3.2 Stories: The Path of Destinies

Já *Stories: The Path of Destinies* é o exemplo de **história contada ramificada**.

No material, o jogo é apresentado como um caso em que:

- as decisões mudam os próximos acontecimentos;
- a narrativa leva a múltiplos finais;
- existem **25 finais diferentes**, sendo 24 finais relacionados aos caminhos percorridos e 1 fechamento ideal, o **“final verdadeiro”**.

Aqui, a narrativa e os diferentes desfechos são parte central da experiência, enquanto o combate aparece mais como apoio.

### Comparando os dois modelos

O ponto principal do capítulo é que os dois jogos funcionam porque cada um escolhe a forma de história mais adequada à experiência que deseja produzir:

- em *Furi*, a história linear reforça a ação frenética;
- em *Stories*, a história ramificada reforça o foco nas escolhas e nos desfechos.

---

## 4. Árvores de decisão

Ao desenhar uma história ramificada, surge um problema de produção: o número de possibilidades cresce rapidamente.

O capítulo explica que, com muitas decisões, forma-se uma **árvore de decisões** que cresce em progressão geométrica. Cada novo caminho exige trabalho de várias áreas:

- texto;
- arte;
- programação;
- testes;
- e demais etapas da produção.

### “Bolsões” de decisão

Como solução, o material sugere criar **bolsões de decisão** que se encontram novamente em certos pontos da narrativa. Isso ajuda a manter a sensação de escolha sem tornar a produção inviável.

### Cuidados com histórias ramificadas

O capítulo também destaca alguns cuidados importantes:

- se o jogador não conquistar o **final verdadeiro**, pode ficar decepcionado;
- todas as decisões precisam parecer **igualmente importantes**;
- é necessário controlar o tamanho da estrutura narrativa para que o jogo continue viável.

### Perguntas essenciais ao definir a história

- Você quer contar uma história no seu jogo?
- Que tipo de história é essa — emergente (nasce a cada partida) ou pré-definida?
- O jogador poderá alterá-la ou ela terá início, meio e fim fixos?
- Como os elementos do contexto (visual, som, gameplay) podem potencializar essa história?

> **Princípio central:** Sempre parta da experiência que você quer transmitir antes de definir a história.

### Quando a história ajuda o jogo

| Benefício | Descrição |
|---|---|
| **Peso emocional** | Personagens e história adicionam motivação e conexão emocional — fundamental em jogos orientados por objetivos dos personagens |
| **Recompensas e ritmo** | A progressão narrativa pode ter um bom ritmo e envolver o jogador além da mecânica pura (ex.: Half-Life, StarCraft, God of War) |
| **Entretenimento opcional** | A história pode ser uma camada extra — jogadores interessados a aproveitam; outros simplesmente pulam |
| **Personagens como ganchos** | Arquétipos fortes (Duke Nukem, Solid Snake) criam conexão emocional sem necessidade de narrativa profunda |

### Quando a história atrapalha o jogo

| Problema | Descrição |
|---|---|
| **Desnecessária** | Jogos de quebra-cabeça, títulos esportivos e minigames geralmente são melhores sem história |
| **Conflito com a jogabilidade** | Cenas longas e não-interativas (cutscenes) que retiram o controle do jogador nos momentos mais intensos prejudicam a experiência |
| **Roteiro inexperiente** | Uma boa narrativa é difícil; designers iniciantes devem buscar feedback, pois é fácil se apaixonar pela própria história e não perceber seus problemas |
| **Personagem fora do contexto** | O tema e os personagens devem se alinhar com a jogabilidade (ex.: Lara Croft faz sentido como ladra de túmulos; Guybrush Threepwood, não) |

### A metáfora do "brincar com fogo"

> A narrativa como elemento de design pode ser um bom servo, mas um mestre terrível. É melhor começar com uma parte pequena e inconsequente de um jogo maior, sob supervisão experiente.

---

## Pilar 2 – Estética (Visual e Sonora)

### O que é Estética?

A estética vai além da beleza visual: engloba **todas as sensações** que o jogador experimenta — visuais, sonoras e outras. Quanto mais a estética estiver alinhada com a experiência e os outros pilares, mais coeso o jogo será.

### Escolhendo o visual adequado

O apelo visual é poderoso — chama atenção antes mesmo de o jogador ler qualquer descrição. Porém, apostar em visuais complexos tem riscos:

- Um visual bonito **não garante** que o jogo será bom se os outros aspectos não estiverem no mesmo nível
- O **tempo de produção** aumenta drasticamente
- O projeto exige mais da máquina de **produção e do hardware do jogador**

#### Exemplo comparativo

| Jogo | Estilo Visual | Justificativa |
|---|---|---|
| **Dwarf Fortress** | Simples (ASCII/símbolos) | Permite geração procedural de mundos infinitos com baixo custo computacional; visual simples serviu à experiência de cada partida única |
| **Lost Soul Aside** | Complexo e detalhado | Alto apelo visual, mas produção cara e exigente de hardware |

> **Conclusão:** O visual do *Dwarf Fortress* foi **adequado** porque entregou exatamente o que a experiência precisava — não é sobre "mais bonito", mas sobre "mais adequado".

### Estética bem definida — Benefícios

- **Chama a atenção** dos jogadores instantaneamente
- **Dá vida ao mundo**, tornando-o mais real e crível
- **Cada nova área** pode ser uma recompensa visual por si só

Exemplos de estéticas singulares e reconhecíveis: *Fortnite*, *Super Mario Odyssey*, *Brawl Stars* — o jogador sabe que tipo de jogo é ao primeiro olhar.

### Equilíbrio estético

- Quanto mais foco em uma área, mais as outras ficam defasadas
- A **estética deve reforçar o Design**, não sustentá-lo sozinha
- Exemplo do *Just Cause 4*: a destruição cenográfica (estética) cria um problema de navegação → solução com **grappling hook**, wingsuit, paraquedas e veículos chamáveis → a estética e o gameplay se complementam

### A Estética sedimenta o Design

Segundo Schell (2008): *"Game Design é abstrato, ilustrações são concretas."*

O simples ato de **desenhar** uma ideia cria um loop de iteração que faz o design crescer:

```
Ideia → Desenho → Limitações percebidas → Refinamento → Novo desenho → ...
```

#### Vantagens do esboço em papel

| Vantagem | Detalhe |
|---|---|
| **Rápido** | Mais rápido que protótipar via código ou modelar em 3D |
| **Feito em qualquer lugar** | Em casa, no trabalho, no ônibus, na padaria |
| **Baixo custo** | Papel e lápis — cerca de R$ 5,00 |
| **Visão compartilhada** | A ideia sai da cabeça e pode ser discutida e melhorada por todos |
| **Fácil de alterar** | Alguns riscos já mudam tudo |
| **Descartável** | Pouco tempo investido = menos apego a ideias ruins |
| **Concreto** | A ideia registrada libera a mente para novas ideias |

> **Dica prática:** Tenha sempre um caderno e lápis à mão — uma boa ideia pode surgir a qualquer hora.

---

## Pilar 3 – Mecânicas e Sistemas

### O papel das mecânicas

Assim como o esqueleto sustenta os órgãos do corpo, as mecânicas e sistemas sustentam a experiência, a história e a estética. Pensar as mecânicas antecipadamente evita desperdício de tempo e retrabalho.

Schell (2008) subdivide as mecânicas em **seis grandes grupos**:

---

### 3.1 Espaço — *Onde o jogador joga?*

Todo jogo acontece em um espaço — o **círculo mágico** do gameplay. O espaço define regras específicas que não existiriam fora dele.

- **Exemplo físico:** Campo de futebol — as linhas brancas determinam laterais, escanteios, pênaltis; fora da partida, é só um gramado
- **Exemplo digital:** Em *Horizon Zero Dawn*, o jogador pode usar armas em áreas selvagens, mas não dentro das cidades — restrição que faz sentido narrativo e técnico (evita quebrar o jogo ao matar NPCs de missões)

#### Perguntas a responder sobre o Espaço

- Quais são os "espaços" do jogo?
- O que o jogador **pode** fazer em cada um?
- O que o jogador **não pode** fazer?
- Como se muda de um espaço para outro?

> **Boa prática:** Desenhar os espaços e suas conexões (mapa de espaços) antes de produzir revela informações críticas sobre o projeto.

---

### 3.2 Objetos, Atributos e Estados — *O que há no jogo? Como se comporta?*

Cada objeto do jogo deve ser descrito em detalhes com seus **atributos** (o que faz) e **estados** (como pode se encontrar).

#### Exemplo: Fantasma do PAC-MAN

| Categoria | Descrição |
|---|---|
| **Objeto** | Fantasma |
| **Atributo 1** | Caça o PAC-MAN sem parar |
| **Atributo 2** | Tira uma vida do PAC-MAN ao tocá-lo |
| **Atributo 3** | Foge do PAC-MAN quando este pega uma power pellet |
| **Atributo 4** | Se morto, volta para a gaiola no mapa |
| **Estado 1** | Caçando o PAC-MAN (comportamento normal) |
| **Estado 2** | Azul — enfraquecido pela power pellet |
| **Estado 3** | Comido pelo PAC-MAN (apenas olhos, voltando à gaiola) |

> Esta descrição permite que o **programador** saiba como o objeto se comporta e que o **ilustrador** saiba que precisará de três artes diferentes para o mesmo personagem.

---

### 3.3 Ações e Reações — *O que o jogador pode fazer? Como o jogo reage?*

Cada ação do jogador deve gerar **reações adequadas** para que ele saiba que sua decisão teve efeito. Sem reação, a ação não é compreendida.

#### Exemplo: Ataque com espada em *Child of Light*

| Ação | Reação 1 | Reação 2 | Reação 3 | Reação 4 | Reação 5 |
|---|---|---|---|---|---|
| Ataque com espada | Animação de ataque (protagonista) | Dano no inimigo (em números) | Animação de dano no inimigo | Efeito de fumaça | Descrição de vulnerabilidade do inimigo |

> **Importante:** Detalhar ações e reações **antes de programar ou ilustrar** permite antecipar o esforço real de produção.

---

### 3.4 Regras — *Como o jogador conquista os objetivos?*

As regras definem o que é possível em cada momento e como ganhar. Segundo Schell (2008), existem três tipos:

| Tipo de Regra | Descrição | Visível ao Jogador? |
|---|---|---|
| **Operacionais** | O que o jogador pode fazer no momento (ex.: atacar, usar item, defender, fugir) | Sim — interface |
| **Escritas** | Objetivos de vitória e o que cada ação gera (ex.: "derrote o inimigo em 3 turnos") | Sim — tutorial/manual |
| **De Fundação** | Regras internas do jogo, como o sistema reage às ações (lógica por trás) | Não — funcionamento interno |

> **Meta do designer:** O jogador deve ser capaz de pensar: *"Entendo as regras, sei como conquistar o objetivo e domino o jogo."*

Regras bem definidas dão ao jogador **domínio e previsibilidade**, essenciais para manter o engajamento.

---

### 3.5 Habilidade — *O jogo destaca alguma habilidade específica?*

A mecânica de habilidade coloca o **jogador em destaque**, fazendo-o demonstrar suas capacidades.

| Tipo de Habilidade | Exemplo Físico | Exemplo Digital |
|---|---|---|
| **Física** | Boxe | Jogos de ritmo, fighting games |
| **Mental** | Xadrez | Estratégia em tempo real |
| **Social** | Poker | Jogos de negociação, blefe |

#### Exemplo: *Spelunky* e os Speedrunners

Em *Spelunky*, jogadores avançados ignoram exploração e narrativa para **terminar o jogo no menor tempo possível**. A estrutura do jogo permite que habilidades excepcionais sejam exibidas — essa é a experiência central para esse público.

> O interessante não é o jogo em si, mas a **capacidade do jogador em demonstrar suas habilidades** de forma diferente e desafiadora.

---

### 3.6 Chance — *Em quais aspectos a sorte será incluída?*

A chance equilibra **previsibilidade e surpresa**. Muito previsível → tédio. Muito aleatório → sensação de falta de controle.

#### Exemplo: *FTL: Faster Than Light* (Roguelike)

A cada partida, elementos gerados proceduralmente mudam:
- Inimigos diferentes
- Mapas alterados
- Tripulação e habilidades variando
- Quantidade de batalhas flutuando

Isso garante que **cada partida seja uma experiência nova**, mesmo com o objetivo central inalterado (chegar de um ponto ao outro da galáxia).

> **Cuidado:** A chance é um aspecto matemático. Balancear jogos baseados em sorte exige tempo considerável para encontrar o ponto de equilíbrio ideal.

---

## Glossário

| Termo | Definição |
|---|---|
| **MOBA** | Multiplayer Online Battle Arena — duas equipes batalham com foco no domínio de pontos do mapa |
| **Gameplay** | O que acontece durante a partida; como o jogo reage às ações do jogador |
| **FPS** | First Person Shooter — jogo de tiro em primeira pessoa |
| **eSports** | Competições profissionais com jogos competitivos entre equipes (ex.: LoL, CS, StarCraft) |
| **NPC** | Non Playable Character — personagem controlado pelo computador com ações definidas pelos desenvolvedores |
| **Roguelike** | Estilo de jogo com alta dificuldade, geralmente uma única vida e mapas/inimigos gerados aleatoriamente |
| **Geração procedural** | Uso de algoritmos para gerar elementos a partir de um banco comum, criando combinações variadas automaticamente |

---

## Síntese Final

Os três pilares do Game Design são interdependentes:

```
História  ←→  Estética  ←→  Mecânicas/Sistemas
     ↑_____________↑_______________↑
              EXPERIÊNCIA
```

- A **história** define o contexto e o peso emocional
- A **estética** dá forma concreta às ideias e sedimenta o design
- As **mecânicas** são o esqueleto que permite que tudo funcione

> O trabalho do Game Designer é garantir que esses três pilares estejam **sempre alinhados com a experiência que se quer transmitir ao jogador**.
