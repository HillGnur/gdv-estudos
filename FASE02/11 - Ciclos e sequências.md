# Capítulo 11 – Ciclos e Sequências: Animação 2D em Jogos

## 1. Animações em Ciclo
O capítulo diferencia animação para jogos de outras mídias, destacando o uso intenso de loops.

Ponto central:
- Trechos curtos de animação se repetem para sustentar movimento contínuo

## 2. Looping
Um loop eficiente reduz percepção de repetição.

Diretriz:
- Início e fim devem conectar suavemente
- Falhas de loop ficam muito visíveis ao longo da partida

## 3. Idle (Repouso)
Animação de espera quando não há comando do jogador.

Variações possíveis:
- Respiração leve
- Gestos de tédio
- Reações contextuais (frio, calor etc.)

Exemplos citados:
- Hollow Knight
- Super Mario Odyssey

## 4. Walk e Run Cycle
Ciclos de caminhada/corrida são tratados como base da animação de personagens.

Conceitos destacados:
- Poses-chave (contact, passing, kickoff, up)
- Ajuste por personalidade e estilo do personagem

## 5. Ações Lineares
Animações não cíclicas com início e fim definidos.

Exemplos:
- Ataques
- Pulo
- Agachamento
- Combos

Fluxo comum:
- Idle -> ação linear -> retorno ao Idle

## 6. Preparação de Personagem Rigged
Pipeline apresentado:
1. Montagem do personagem em arquivo por partes
2. Importação na Unity
3. Skinning editor
4. Bones
5. Mesh
6. Influência de ossos por parte
7. Criação das animações na timeline

## 7. Síntese
O capítulo enfatiza qualidade de ciclo, clareza de transição e boa estrutura de rig para animações consistentes em jogo.
