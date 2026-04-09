# Capítulo 13: Animar, Como é Possível?

## Introdução

Este capítulo explora os conceitos fundamentais de animação 2D e fornece um guia prático para criar animações utilizando a técnica de Rigging 2D na engine Unity. O foco está na técnica de personagens Cutout (em pedaços), que permite criar animações de qualidade de forma eficiente, sem a necessidade de redesenhar todos os frames manualmente.

---

## 1. Introdução à Animação 2D

### Por Que Rigging 2D?

O Rigging foi escolhido como técnica de foco neste capítulo porque:

- **Controle preciso:** Cada parte do corpo do personagem é controlável, parecendo com o controle do corpo humano real
- **Hierarquia natural:** Com estrutura baseada em hierarquia, levantar o braço automaticamente levanta a mão, sem necessidade de ação separada
- **Eficiência produtiva:** Não é necessário desenhar todos os frames – personagem pode ser reaproveitado
- **Ideal para iniciantes:** Oferece uma curva de aprendizado acessível para estudos em animação 2D

#### Comparação com Quadro a Quadro

Se o personagem tivesse partes separadas sem rigging, seria necessário levantar braço e mão separadamente para cada ação. Com rigging, a estrutura hierárquica resolve isso automaticamente.

---

## 2. Conceitos Fundamentais de Animação

### 2.1. Frames – Quadros

#### Definição

Um **frame** ou **quadro** é uma imagem "parada" que, com várias outras, dá a impressão de movimento. Tem esse nome porque, em sua origem, era literalmente formada por um pequeno quadro de filme fotográfico.

#### Versão Digital

Na versão digital do frame, é possível guardar uma informação de animação, como:
- Escala
- Rotação
- Movimentação
- Cor
- Opacidade
- E outras propriedades

#### Keyframe (Quadro-Chave)

De "frame" derivou-se o termo **"keyframe"** (quadro-chave), que é um quadro com uma ação importante, geralmente responsável pelo:
- Início de uma transição
- Fim de uma transição

A partir da marcação de alguns keyframes, consegue-se gerar uma ação completa.

---

### 2.2. Interpolação

#### Conceito

A **interpolação** é uma característica fundamental da maioria dos softwares e técnicas de animação digital. É um divisor de águas porque permite que, a partir de dois keyframes, todos os frames intermediários sejam interpretados automaticamente.

#### Exemplo Prático

Imaginemos:
- **Frame 1:** Braço levantado (keyframe)
- **Frame 12:** Braço abaixado (keyframe)

A interpolação cria automaticamente todos os frames entre eles, gerando a ação de descida do braço.

#### Vantagem Comparativa

Se a animação fosse feita de modo clássico (quadro a quadro), o animador precisaria elaborar manualmente todos os 12 frames, desenhando a ação completa. A interpolação reduz drasticamente o trabalho.

#### Base do Rigging

A técnica de Rigging abordada neste capítulo utiliza a interpolação como base de seu funcionamento.

---

### 2.3. Linha do Tempo – Timeline

#### Função Principal

A **timeline** (linha do tempo) será a principal ferramenta de trabalho, pois é nela que:
- Marcam-se e editam-se os keyframes
- Salva-se a animação
- Aplicam-se efeitos diversos

#### Funcionalidades

Através da timeline é possível:
- **Definir espaço de trabalho:** De poucos frames até centenas e milhares deles
- **Controlar velocidade:** Acelerar e desacelerar a animação
- **Ajustar frame rate:** Trocar a quantidade de frames por segundo (FPS)

#### Importância Operacional

A timeline é essencial para organização, visualização e controle fino da animação durante o desenvolvimento.

---

## 3. Unity e Animação 2D

### Introdução

O mundo dos softwares para animação 2D é composto de diversas opções pagas (Adobe Animate, Toon Boom, Spine 2D, entre outras). Para quem busca um software gratuito e de qualidade, a Unity oferece ferramentas próprias integradas.

#### Vantagens da Abordagem Unity

- **Leve:** Não consome recursos excessivos
- **Prático:** Permite criar um rigging com poucos passos
- **Foco:** Possibilita focar na parte de animação rapidamente
- **Integração:** Eliminação de passos intermediários de importação

---

## 4. O Processo de Animação 2D

### Visão Geral

Na criação de animações 2D de qualidade, principalmente para estilo Cutout, é necessário passar por um processo específico que garante uma animação de qualidade.

---

### 4.1. Projetar o Sprite

#### Preparação

Antes de realizar a rigging, é importante ter uma ideia clara de como o personagem deve parecer.

#### Opções de Desenvolvimento

**Opção 1: Criar do Zero**
- Projete o personagem em software de gráficos como Adobe Photoshop, Illustrator ou similar
- Se possui habilidade em desenho, crie uma série de artes para utilização dentro da Unity

**Opção 2: Usar Assets Prontos**
- Se o foco é a animação (não na arte), encontre desenhos prontos na internet
- Sugestão: Sites como **CraftPix** oferecem assets Cutout prontos

#### Softwares Recomendados

- Adobe Photoshop
- Adobe Illustrator
- Qualquer software de gráficos adequado
- Photopea (gratuito, imita Photoshop)

---

### 4.2. Criar um Esqueleto

#### Conceito

Em um software 2D, crie um esqueleto virtual colocando **ossos** (bones) em pontos-chave de articulação, como as juntas.

#### Função

Esses ossos servem como a estrutura subjacente para o personagem 2D, controlando como ele se move.

#### Pontos-Chave de Posicionamento

Os bones devem ser estrategicamente posicionados em:
- Articulações naturais do corpo
- Pontos onde há movimento previsto
- Áreas de conexão entre partes do personagem

---

### 4.3. Juntar o Sprite e Esqueleto

#### Processo

Associe as diferentes partes do personagem aos ossos do esqueleto. Esta etapa envolve mapear:
- Braços → ossos correspondentes
- Pernas → ossos correspondentes
- Cabeça → osso correspondente
- Tronco → osso correspondente
- Outras partes → ossos correspondentes

#### Resultado

Ao final, todas as partes visuais (sprites) estão conectadas aos ossos da estrutura esquelética.

---

### 4.4. Definir Restrições e Hierarquias

#### Objetivo

Configure restrições e hierarquias dentro da estrutura para controlar como as diferentes partes do personagem se movem em relação umas às outras.

#### Importância

Esta etapa garante que:
- Os movimentos pareçam naturais
- O controle seja adequado
- A estrutura se comporte como esperado

#### Exemplo de Hierarquia

Se o ombro se move, o braço e a mão devem acompanhar automaticamente (hierarquia natural do corpo humano).

---

### 4.5. Skinning

#### Processo

Ajuste a **influência de cada osso** nos sprites anexados. Esta etapa é crucial para garantir que o personagem deforme e se mova realisticamente.

#### Importante

A qualidade do skinning determina como o personagem se deforma quando os ossos são manipulados. Um skinning ruim resulta em deformações não-realistas.

---

### 4.6. Animação do Rig

#### Etapa Final de Preparação

Utilize o software de rigging para animar o personagem:
- Crie quadros-chave (keyframes)
- Configure animações
- Manipule a estrutura para dar vida ao personagem

#### Próxima Etapa

Com o rig preparado, é possível criar as animações efetivamente.

---

## 5. Criando a Animação – Guia Prático na Unity

### Pré-Requisitos

Antes de começar, certifique-se de ter:
- Personagem Cutout pronto em arquivo apropriado
- Unity instalada

---

### 5.1. Criar Novo Projeto

1. Abra a **Unity Hub** e clique em **New Project**.
2. Selecione a opção **2D (URP)**.
3. Clique em **Create Project**.
4. Aguarde alguns minutos até a criação do projeto ser finalizada.

---

### 5.2. Instalar Pacotes 2D

1. Na Unity, vá em **Window > Package Manager**.
2. Procure por **2D**.
3. Instale os **sete pacotes disponíveis**.

O capítulo apenas orienta a instalar todos os pacotes 2D encontrados, porque os passos seguintes dependem deles.

---

### 5.3. Importar Personagem Cutout

1. Acesse **https://craftpix.net/**.
2. Vá até a aba **Freebies**.
3. Procure um personagem no estilo **Cutout**.
4. Faça o download do personagem.
5. Descompacte o arquivo.

#### Exemplo de Asset

Para este tutorial, recomenda-se o **Minotaur Tiny Style**:
URL: https://craftpix.net/freebies/free-minotaur-tiny-style-2d-sprites/

---

### 5.4. Preparar o Arquivo

1. Localize a pasta com os arquivos **EPS**.
2. Selecione os arquivos disponíveis.
3. Desmarque apenas **Face_02** e **Face_03**.

#### Passo 2: Consolidar em Arquivo Photoshop

Para tudo funcionar corretamente na Unity, agregue todos os arquivos em um único arquivo Photoshop com diversas camadas.

##### Usar Photopea (Gratuito)

1. Acesse: https://www.photopea.com/
2. Clique em: Novo > Novo Projeto
3. Defina: 1200 x 1200 pixels
4. Deixe: Plano de fundo transparente

##### Montar o Personagem

1. Arraste os arquivos EPS para o arquivo aberto
2. Cada arquivo EPS será salvo como camada diferente
3. Observe os "Controles de transformação" para modificar escala se necessário
4. Organize as camadas para montar o personagem completo

##### Salvar em Formato Apropriado

1. Vá em **Arquivo > Salvar Mais > Salvar PSB**.
2. Salve exclusivamente em formato **.PSB**.

---

### 5.5. Importar na Unity

1. Arraste o arquivo **.PSB** para dentro da Unity.
2. Garanta que as configurações estejam corretas, como mostrado no material.
3. Clique em **Sprite Editor**.
4. Verifique se o personagem aparece dividido em partes no editor — isso indica que a importação foi reconhecida corretamente.

---

### 5.6. Acessar o Skinning Editor

No **Sprite Editor**, vá ao canto superior esquerdo e selecione **Skinning Editor**. É a partir dele que a criação efetiva do projeto acontecerá.

#### Interface do Skinning Editor

O Skinning Editor divide-se em áreas para diferentes processos:

| Área | Função |
|------|--------|
| **Bones** | Criação e gerenciamento de ossos |
| **Geometry** | Configuração de malha e influência |
| **Pose** | Visualização e teste de posições |
| **Hierarchy** | Organização e nomenclatura de bones |

---

## 6. Criando Bones (Ossos)

### 6.1. Iniciar Criação de Bones

#### Passo 1: Encontrar Opção Create Bone
```
Encontre a opção "Create Bone" dentro do menu "Bones"
```

#### Passo 2: Criar Ossos
```
Para criar um osso: clique e arraste
Cada um terá uma cor diferente para identificação
```

### 6.2. Estratégia de Posicionamento

#### Locais de Articulação

Os Bones devem ser criados em regiões onde notamos que possa existir uma junta ou movimento:
- Articulações do corpo
- Juntas principais
- Pontos de rotação natural

#### Processo Recomendado

```
1. Comece da pélvis/base
2. Clique e arraste até pontos de junta
3. Crie bones na sequência: pélvis → tronco → pescoço → cabeça
```

#### Criar Membros (Braços/Pernas)

```
Para criar braços/pernas com hierarquia correta:
1. Clique novamente na pélvis (ponto de origem)
2. Arraste para criar o primeiro bone do membro
3. Continue criando bones para o membro completo
4. Repita para todos os membros
```

#### Resultado Final

Ao final do processo, deve haver:
- Uma coluna vertebral (pélvis → tronco → pescoço → cabeça)
- Dois braços (um em cada lado)
- Duas pernas (uma em cada lado)
- Possíveis ossos adicionais (dedos, cauda, etc.)

---

## 7. Configuração de Geometry e Skinning

### 7.1. Auto Geometry

#### Passo 1: Selecionar Auto Geometry
```
Localize o menu "Geometry"
Selecione a opção "Auto Geometry"
Para que as opções sejam mostradas corretamente
```

#### Passo 2: Visibility
```
Clique em "Visibility"
Um menu lateral será exibido
```

#### Passo 3: Generate For All Visible
```
No canto direito, em "Geometry"
Clique em "Generate For All Visible"
```

#### Resultado

Automaticamente, a Unity distribuirá a influência de um osso para uma imagem:
- O osso verde claro influencia os locais que estão com verde claro
- Cada cor representa a influência de um osso específico

---

### 7.2. Nomenclatura de Bones

#### Importância

Nomenclatura adequada é crucial em projetos mais complexos (faz muita diferença).

#### Processo

```
No canto direito da interface
Nomeie cada um dos ossos apropriadamente
Exemplos:
  - "Pélvis" para base
  - "Tronco" para tronco
  - "Braço_Esq" para braço esquerdo
  - "Mão_Esq" para mão esquerda
  - E assim sucessivamente
```

#### Nota

Nomear pode ser trabalhoso, mas em projetos mais complexos faz muita diferença na organização.

---

### 7.3. Bone Influence (Pintura de Influência)

#### Passo 1: Selecionar Bone Influence
```
Selecione a opção "Bone Influence"
```

#### Passo 2: Verificar Influências
```
Clique nas imagens que formam o personagem
Note que cada imagem tem influência de vários ossos
```

#### Passo 3: Ajustar Influências
```
O objetivo é ajustar isso!
Agora é possível definir quais ossos irão influenciar cada parte do personagem
```

#### Refinamento

```
Para cada sprite/parte:
1. Remove influências desnecessárias
2. Fortalece influências apropriadas
3. Equilibra a deformação para realismo
```

#### Resultado

Cada parte do personagem deve ter influência apenas dos ossos relevantes para aquela parte.

---

## 8. Preview e Validação

### 8.1. Preview Pose

#### Localização
```
Em "Pose", selecione a função "Preview Pose"
```

#### Funcionalidade
```
Permite mexer nos ossos e:
- Ver como eles estão funcionando
- Verificar se tudo está correto
- Testar o rigging antes de fazer animações efetivas
```

#### Importância

Esta validação prévia evita retrabalhos significativos após começar a animar.

---

### 8.2. Fechar Sprite Editor

```
Com o Rigging finalizado:
Feche o Sprite Editor
Vá para a área de animação efetivamente
```

---

## 9. Criando Animações

### 9.1. Abrir Aba de Animação

#### Localização
```
Na Unity, vá aos três pontinhos (⋯) disponíveis na interface
Localize a opção "Animation"
A aba de animação será aberta
```

#### Interface de Animação

Será exibido um editor de animação completo para trabalhar com keyframes.

---

### 9.2. Criar Nova Animação

#### Passo 1: Pressionar Create
```
Pressione o botão "Create"
Uma janela se abrirá para nomear a animação
```

#### Passo 2: Nomear Animação
```
Nomeie a animação
Exemplo: "Idle" (para animação de repouso)
```

#### Nomenclatura Recomendada

| Nome | Tipo |
|------|------|
| **Idle** | Repouso/aguardando ação |
| **Walk** | Caminhada |
| **Run** | Corrida |
| **Jump** | Pulo |
| **Attack** | Ataque |
| **Hurt** | Receber dano |
| **Die** | Morte |

---

### 9.3. Configurar Auto Keyframe

#### Ativar Auto Keyframe
```
Pressione o botão vermelho na timeline
Ele age como um auto-keyframe que captura todas as suas ações
```

#### Benefício
```
Deixa a animação com mais qualidade e automatiza o processo de marcação
```

---

## 10. Criando Animação Prática

### 10.1. Criar Animação de 3 Keyframes

#### Estratégia

Para uma animação simples que mostre o conceito, criar uma animação de 3 keyframes:
- **Frame 1:** Posição inicial (keyframe)
- **Frame Intermediário:** Posição diferente com ação (keyframe)
- **Frame Final:** Retorno à posição inicial (keyframe)

#### Passo 1: Primeiro Keyframe
```
No frame 0, pose o personagem em uma posição inicial
O auto-keyframe irá capturar automaticamente
```

#### Passo 2: Copiar para Último Frame
```
Com Ctrl + C: copie o primeiro keyframe
Com Ctrl + V: cole para o último frame
Isso garante que a animação retorne ao estado inicial
```

#### Passo 3: Frame Intermediário
```
No meio (aproximadamente no frame 12-15):
Insira um frame com ação diferente
Pose o personagem em uma posição diferente
```

#### Resultado

Será criada uma animação onde o personagem:
1. Começa em uma posição
2. Se move para uma posição diferente
3. Retorna à posição original

Esta é uma animação de ciclo básica.

---

## 11. Conclusão

### Eficiência do Processo

A partir da demonstração trabalhada neste capítulo, foi possível perceber que personagens cutout aliados à técnica de Rigging mostram quão prático esse processo pode ser.

### Principais Vantagens

- **Reutilização:** Reaproveita-se o personagem ao invés de redesenhá-lo a cada frame
- **Otimização:** Em termos de produção de um jogo, significa otimização de tempo e economia de recursos
- **Qualidade:** O foco pode recair sobre o que o jogador realmente enxerga – as animações e o desempenho

### Próximas Etapas

```
1. Refaça o exercício algumas vezes
2. Pratique os conceitos apresentados
3. Experimente com diferentes personagens
4. Explore animações mais complexas
```

### Recomendação Final

Para o momento apropriado de desenvolvimento do seu jogo, você já terá esse conhecimento de Rigging e conseguirá animar seus personagens com confiança e eficiência.

---

## Glossário

| Termo | Definição |
|-------|-----------|
| **Frame / Quadro** | Imagem "parada" que, com várias outras, dá a impressão de movimento |
| **Keyframe / Quadro-Chave** | Quadro com uma ação importante, responsável pelo início ou fim de uma transição |
| **Interpolação** | Processo de gerar frames intermediários automaticamente entre dois keyframes |
| **Timeline / Linha do Tempo** | Ferramenta principal para marcar, editar keyframes e organizar animações |
| **Rigging** | Criação de estrutura de ossos que comanda um personagem |
| **Bone / Osso** | Elemento individual da estrutura esquelética que controla partes do personagem |
| **Cutout** | Estilo de arte em pedaços/partes separadas preparadas para rigging |
| **Skinning** | Ajuste da influência de cada osso nos sprites anexados |
| **Mesh / Malha** | Estrutura geométrica que define a forma de um objeto |
| **Sprite** | Imagem 2D usada em jogos |
| **Asset** | Recurso/elemento reutilizável em um projeto |
| **PSB** | Formato Photoshop que preserva camadas (layers) |
| **EPS** | Formato de arquivo vetorial |
| **Auto Keyframe** | Funcionalidade que captura automaticamente poses como keyframes |
| **Spritesheet** | Imagem única que contém os quadros de uma animação ou os gráficos de um jogo |
