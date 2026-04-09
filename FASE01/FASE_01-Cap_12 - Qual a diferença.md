# Capítulo 12: Qual a Diferença?

## Introdução

Uma das decisões mais importantes no desenvolvimento de um jogo é a escolha entre utilizar animação 2D, 3D ou uma combinação de ambas. Não existe uma resposta correta ou única para essa questão, pois a escolha ideal depende de diversos fatores críticos como plataforma alvo, gênero do jogo, habilidades da equipe de desenvolvimento e a sensação ou sentimento que se deseja transmitir aos jogadores. Este capítulo explora técnicas, softwares e exemplos práticos que ajudam na decisão entre esses estilos gráficos.

---

## 1. Animação 2D vs 3D

### Considerações Fundamentais

A escolha entre 2D e 3D não deve ser vista como uma questão de qualidade, mas sim como uma opção técnica e artística legítima. Contrário ao que muitos acreditam, 2D não é um estilo "preguiçoso" – muitos jogos em 2D possuem grande complexidade técnica e visual. Fatores como orçamento, cronograma de produção e capacidades da equipe influenciam significativamente nessa decisão.

---

## 2. Arte e Animação 2D

### Características Gerais

A arte 2D é clássica, popular e querida, sendo o estilo gráfico que existiu no início dos videogames e permitiu a popularização da Pixel Art como um estilo atemporal. Porém, o 2D vai além da Pixel Art – diversas técnicas e tecnologias foram desenvolvidas ao longo do tempo.

A animação 2D é uma forma de arte que:
- **Transmite emoções e narrativas** de maneira simplificada, mas profundamente significativa
- **Permite conexão emocional** através de desenhos que ganham vida em cores vibrantes
- **Evoca nostalgia** e transmite mensagens que transcendem barreiras de tempo e espaço
- **Evolui constantemente**, combinando técnicas tradicionais com tecnologia de ponta moderna

### 2.1. Animação Clássica – Quadro a Quadro

#### O Legado da Técnica

Ao contrário do que muitos imaginam, o estilo de animação clássica não desapareceu – ainda está vivo em jogos de altíssima qualidade. Esta técnica envolve desenhar mão-a-mão, digitalizar e animar quadro a quadro.

#### Exemplos Notáveis

**Hollow Knight:**
- Baseado em arte desenhada à mão e digitalizada
- Animação feita quadro a quadro no Photoshop
- Integração posterior com a Engine Unity
- Uso de shaders simples (sprite_default e sprite_diffuse) com alterações

**Cuphead:**
- Técnica de animação quadro a quadro foi escolhida para imitar animações dos anos 1930
- Equipe pequena: apenas 5 animadores, 1 artista de fundos e 1 pintor digital
- Processo: desenho e pintura manual → escaneamento digital → colorização no Photoshop
- Resultado visual muito semelhante ao filme "Flowers and Trees" (1933)
- Personagens foram rascunhados, desenhados, pintados à mão, digitalizados e coloridos digitalmente

#### Requisitos para Sucesso

Esta técnica geralmente exige:
- Equipes com background forte em arte 2D
- Tempo de produção e orçamentos compatíveis
- Expertise visivelmente consolidada

---

### 2.2. Pixel Art

#### Diversidade de Estilos

A Pixel Art existe em muitos estilos, formas e visões diferentes, podendo ser extremamente simples com poucos pixels ou ter um número gigante de detalhes em alta resolução. Esses fatores variam conforme:
- Habilidade artística da equipe
- Orçamento disponível
- Desejo de emular nostalgia (8 bits, 16 bits, etc.)

#### Variáveis Criativas do Pixel Art

| Aspecto | Opções |
|--------|--------|
| **Resolução** | 8x8, 32x32, 128x128, etc. |
| **Proporção** | Cartoon, realista, chibi |
| **Paleta de cores** | 2, 16, 256 cores |
| **Estilo visual** | Anime, realista, retrô |
| **Ponto de vista** | Lado, cima, isométrico |

#### Exemplos de Estratégias

**Nidhogg (2014):**
- Foco na mecânica única de combate
- Emulação de estilo Atari com artes em baixa resolução
- Muitas vezes monocromáticas
- Decisão inteligente que tornou o visual marcante e reduziu orçamento

**Eastward:**
- Pixel Art hiper detalhada
- Público de nicho forte
- Cenários encantadores e visualmente impactantes

**Risk of Rain:**
- Meio termo entre arte prática/rápida e visual interessante
- Demonstra que não é necessário ficar nos extremos

**Hotline Miami e Witchbrook:**
- Exemplo da frase de Byford: "Um jogo de Pixel Art nunca vai envelhecer visualmente"
- Jogos com uma década mantêm visual à prova de envelhecimento
- Witchbrook: visão isométrica, alta resolução, muitas cores, estilo cartoon-anime

**Undertale:**
- Visão de cima em resolução mais baixa
- Cores limitadas na paleta
- Personagens cartoon-chibi
- Estilo feito para lembrar jogos retrô

#### Softwares para Pixel Art

Pixel Art possui uma das maiores gamas de softwares gratuitos e acessíveis:
- **Opções populares:** Photoshop, Piskel, Pixilart, Lospec, Aseprite
- **Vantagem:** Muitos programas rodam diretamente do navegador, sendo totalmente gratuitos
- **Processamento:** Não cobra muito do computador

---

### 2.3. Rigging 2D

#### O Conceito

A técnica de Rigging consiste na criação de uma estrutura de ossos que comanda um personagem. Embora amplamente conhecida na animação 3D, a técnica também existe e está muito presente no 2D.

#### Como Funciona

Para usar Rigging em 2D, utiliza-se personagens desenhados em formato **Cutout** (em pedaços), estruturando esses pedaços através de um esqueleto virtual.

#### Vantagens Principais

- **Maior velocidade:** Não é necessário redesenhar o personagem a cada quadro
- **Flexibilidade:** Manipulando a estrutura esquelética, podemos marcar posições sem redefinição
- **Eficiência:** Economia significativa de tempo de produção

#### Limitações

A maior desvantagem é que se torna mais complicado fazer alterações significativas no design do personagem durante a animação, já que a aparência base permanece a mesma em todos os quadros, baseando-se nos pedaços de imagem (cutout).

#### Exemplos de Aplicação

**Nidhogg 2:**
- Continuou com Pixel Art do primeiro título, mas utilizou técnicas de Rigging
- Experimento com programas de rigging em 2D permitiu animar partes do corpo independentemente
- Facilitou combinar esgrima, movimento do pé, várias partes do corpo e tipos de arma
- Possibilidade de substituir sprites sem "quebrar" a animação

**Flipping Death (2017):**
- Personagens únicos desenhados em pedaços (cutout)
- Unificados pela técnica de rigging, otimizando o processo

#### Softwares Disponíveis

| Categoria | Softwares |
|-----------|-----------|
| **Adobe** | Animate |
| **Especializados** | Spine 2D, Spine Creature, Spriter |
| **Gratuitos** | DragonBones Pro |
| **Integrados em Engine** | Anima 2D (Unity) |

#### Método de Integração

Muitas engines de jogos permitem que riggings sejam feitos diretamente dentro da engine (nativamente ou com assets adicionais) – é um método prático, mas pode significar uma interface de animação simplificada. O desenvolvedor deve pesar os prós e contras dos diferentes softwares.

---

## 3. Arte e Animação 3D

### Visão Geral

Do lado 3D, temos técnicas que possuem a vantagem fundamental da profundidade, ausente no 2D. O Rigging é o padrão de mercado para personagens e objetos, frequentemente combinado com tecnologias como captura de movimento (motion capture).

---

### 3.1. Rigging 3D

#### Definição e História

O Rigging surgiu ainda nos anos 1990 e desde então cresceu em técnica e tecnologia. O processo envolve:

1. **Modelagem:** O artista modela um personagem
2. **Estrutura:** Garante que ele tenha polígonos suficientes para que o esqueleto se ligue aos polígonos (malha/mesh)
3. **Influência:** O esqueleto possui uma influência sobre a malha
4. **Refinamento:** Editado para polimentos através de um processo chamado Pintura de Influência

#### Complexidade Variável

O processo pode ser:
- **Simples:** Feito em poucas horas para personagens básicos
- **Complexo:** Pode levar dias de trabalho para personagens com mais detalhes

#### Rigging Facial

Com foco em realismo, foi desenvolvido o **Rigging Facial** – posicionamento de ossos no rosto para controle da animação facial, aumentando muito a profundidade das animações.

**Exemplo: The Last of Us - Personagem Ellie**
- 98 joints (juntas) no rosto
- Malha densa que permite bastante movimento
- Diversas possibilidades de feições para suportar grande número de emoções
- Necessário consultar animador para garantir que o rigging suporte o necessário

**Exemplo: Uncharted 4 - Nathan Drake**
- Densidade de malha facial muito alta para expressão realista

#### Softwares Profissionais Disponíveis

| Software | Características |
|----------|----------------|
| **3DS Max** | Padrão da Autodesk para modelagem, rigging e animação |
| **Autodesk Maya** | Principal software da indústria, usado por estúdios como Rockstar, Ubisoft, Activision |
| **Blender** | Open-source, principal software gratuito, recebe investimento constante, base gigantesca de entusiastas |
| **Houdini** | Sistema de programação visual, criação procedural, excelente para simulações |
| **ZBrush** | Ferramenta complementar de escultura digital |
| **Modo** | Alternativa profissional |

#### Exemplos de Produção

**The Witcher 3 - CD Projekt Red:**
- Personagem Geralt foi modelado, riggado e animado com Autodesk Maya
- Demonstra a relevância do conhecimento em Maya para o mercado

#### Automação e Inovação

Técnicas estão sendo desenvolvidas para automatizar o máximo possível o processo de Rigging:
- Autorig não é novidade, mas o uso de inteligência artificial é algo sem precedentes
- Busca por otimização e qualidade aumentadas

---

### 3.2. Motion Capture (Mocap)

#### Propósito e Benefícios

Com jogos cada vez mais detalhados, cheios de história, cutscenes e momentos cinematográficos, animar tudo se torna desafiador. O Motion Capture foi criado para:
- Capturar movimentos de pessoa real
- Transferi-los para modelos 3D já modelados e com rigging pronto
- Facilitar criação de cutscenes e animações
- Proporcionar fidelidade muito maior ao realismo

#### Requisitos Profissionais

O método profissional requer:
- Estrutura caríssima com estúdio dedicado
- Equipamentos especializados
- Muito mais popular em grandes títulos do que em independentes

**Exemplo: Hellblade: Senua's Sacrifice**
- Possui captura de movimentos muito elogiada
- Tecnologia permite inclusive interação entre atores

#### Alternativas Acessíveis

É possível criar estruturas simplificadas e improvisadas que:
- Têm resultado inferior
- Podem servir a jogos mais simples
- Geralmente montados com sensor Kinect de Xbox e outras câmeras

#### Avanço Tecnológico: Metahuman

O advento da tecnologia **Metahuman da Unreal Engine** está mudando o mercado:
- Possibilidade de gravar captura de movimento facial através de iPhone
- Captura diretamente para personagem dentro da Engine
- Democratização da tecnologia de mocap

---

## 4. Um Pouco dos Dois

### Introdução à Hibridização

Depois de entender ambas as abordagens, muitos gostariam de usar as duas em seu jogo. Isso é totalmente possível! Tudo depende da direção de arte e mecânicas que se pretende inserir no jogo.

### Objetivos da Mistura

A apresentação isolada de 2D e 3D não objetiva a separação como dois universos inteiramente diferentes, mas simplesmente um espaço para entender um de cada vez. Agora que se entende mais sobre essas abordagens, exemplos criativos que misturam esses universos são possíveis.

---

### 4.1. Personagens 2D em Mundo 3D

#### Paper Mario Series

**Características:**
- Um dos jogos mais famosos a utilizar a ideia de personagens 2D em um mundo 3D
- O mais interessante é que personagens não têm profundidade alguma
- Utilizados de maneira intensa na construção da mecânica do projeto

**Mecânica Integrada:**
- Em alguns cenários, é necessário "brincar" com o fato de personagens serem 2D
- Personagens acessam áreas específicas que seriam impossíveis se fossem 3D

**Paper Mario: The Origami King:**
- Exemplo moderno dessa abordagem com evolução visual

---

### 4.2. Cenários 3D com Personagens 2D

#### Bad North

**Estratégia Visual:**
- Aproveita estilo cartoon e simplista de 3D
- Personagens 2D bastante estilizados
- A estratégia faz sentido do ponto de vista de processamento

**Justificativa Técnica:**
- Dependendo do tipo de modelo 3D, podem ser mais custosos ao processamento do que sprites 2D
- Escolha legitima de otimização

---

### 4.3. Songs of Conquest

- Utiliza técnica de personagens 2D em cenário 3D
- Demonstra outra aplicação criativa da hibridização

---

### 4.4. Técnica Billboard

#### O Que É

A técnica **Billboard** consiste em fazer um sprite estar sempre de frente para a câmera. Sendo assim, ele rotaciona de acordo com a posição da câmera.

#### Aplicações

Jogos que frequentemente utilizam:
- Paper Mario
- Bad North
- Songs of Conquest

#### Vantagens

- Mantém legibilidade do personagem 2D
- Simples de implementar tecnicamente
- Custo de processamento otimizado

---

## 5. Conclusão

### Decisões Artísticas e Técnicas

Todo jogo é baseado em uma visão artística e em referências de seus criadores. A partir disso, diversos estilos e técnicas podem ser escolhidos e combinados, sem existir necessariamente uma escolha melhor que outra.

### Tendências por Gênero

Alguns gêneros são conhecidos por ter mais jogos em 2D ou 3D, ter personagens mais ou menos realistas, entre outras características. Cabe aos desenvolvedores seguir essa tendência ou não.

### Fatores Críticos na Decisão

É importante levar em consideração:
- **Plataforma alvo:** Quais são as limitações técnicas?
- **Habilidades dos membros da equipe:** Qual expertise está disponível?
- **Tipo de arte e animação:** Com qual estilo a equipe tem maior proximidade?

Se levados em consideração esses elementos com toda certeza, um jogo melhor será entregue.

---

## Glossário

| Termo | Definição |
|-------|-----------|
| **Arte Vetorial** | Ilustrações digitais que utilizam formas geométricas primitivas em sua construção, como linhas, curvas, pontos, formas e polígonos |
| **Pintura Digital** | Técnica de ilustração ou pintura que, em vez de usar meios tradicionais, utiliza um ambiente computacional |
| **Rigging** | Criação de uma estrutura de ossos que comanda um personagem |
| **Cutout** | Estilo de arte em pedaços/partes separadas para rigging |
| **Motion Capture (Mocap)** | Captura e transferência de movimentos de pessoa real para modelo 3D |
| **Billboard** | Técnica que mantém sprite sempre de frente para a câmera |
| **Mesh** | Malha de polígonos que forma a estrutura visual de um modelo 3D |
| **Pintura de Influência** | Processo de refinamento e edição de como um esqueleto influencia a malha |
