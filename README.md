# Stand Castelo — Tatuador de Elite

Modelo 3D interativo, em escala real, do conjunto de três estandes modulares para feira de tatuagem.

Abra o `index.html` em qualquer navegador (ou publique pelo GitHub Pages) para girar, aproximar e alternar entre as vistas isométrica, frente, lateral, fundo e planta.

## Projeto

- 3 estandes de 3 × 2 m em formato de L (18 m² no total)
  - Estande 1: frente esquerda
  - Estande 2: frente direita
  - Estande 3: atrás do estande 2
- Altura total de 2,70 m: placas de 2,20 m + testeira de 0,50 m
- 10 placas brancas de 1 × 2,20 m
  - 6 na parede principal de 6 m (atrás dos estandes 1 e 2)
  - 2 na lateral esquerda do estande 1
  - 2 na lateral esquerda do estande 3
- Abertos: frente de 6 m, lateral direita de 4 m e fundo de 3 m do estande 3
- Sem divisória entre os estandes 1 e 2

## Testeiras

Pretas, com a logo do Tatuador de Elite (fênix, nome, "Marketing para tatuadores" e bandeiras do Brasil, EUA e União Europeia):

| Testeira | Comprimento | Logos |
| --- | --- | --- |
| Frente | 6 m | 2 (uma centralizada em cada estande) |
| Lateral direita | 4 m | 1 |
| Fundo do estande 3 | 3 m | 1 |

## Banners na parede principal (6 m)

Placas numeradas da esquerda para a direita, viradas para a frente do estande:

| Placa | Banner |
| --- | --- |
| 1 | Damisel Ramirez |
| 2 | Patrocinador oficial Arromba Tattoo Shop (cupom CASTELO) |
| 3 | Rafael Luzart |
| 4 | Fabrícia Gonçalves |
| 5 | Patrocinador oficial The One (cupom CASTELO) |
| 6 | Samara Christo |

## Laterais de 2 m

Face voltada para dentro do estande:

| Placa | Lateral | Banner |
| --- | --- | --- |
| 7 | Estande 1 (perto da frente) | Arte Tatuador de Elite + Castelo Ads |
| 8 | Estande 1 (perto do fundo) | Arte Tatuador de Elite + Castelo Ads |
| 9 | Estande 3 | Arte "Marketing para Tatuadores" |
| 10 | Estande 3 | Arte "Marketing para Tatuadores" |

## Fundo interno do estande 3 (3 m)

O verso das placas 4, 5 e 6, voltado para dentro do estande 3, recebe os três painéis com os tatuadores do Tatuador de Elite. Vistos de dentro do estande 3, da esquerda para a direita:

| Verso da placa | Painel |
| --- | --- |
| 6 | Tatuadores 1 (Rafael, Fabrícia, Samara, Dami, Pedro, Elisa, Victoria, Ink Korps, Imad, Fernanda, Gameiro, Gabriel) |
| 5 | Tatuadores 2 (Anderson, Eduardo, Elen, Letícia, Junio, Francisco, Leandro, Igor, Ana Beatris, Vinícius, Joana, Sérgio) |
| 4 | Tatuadores 3 (Gabriel, Eduardo, Tiago, Emerson, Julia, Ramon, Luiz RM, Prime Art, Giulia, Rodrigo, Beatris, Junior) |

## Balcões

Três balcões modulares de 0,98 m (largura) × 0,48 m (profundidade) × 0,91 m (altura), em alumínio com painéis brancos, todos do lado de fora do estande 3:

- 2 lado a lado ao longo da lateral direita do estande 3, com a arte virada para o corredor:
  - 1º (junto ao pilar do canto do fundo): QR Code Tatuador de Elite
  - 2º (ao lado do primeiro, em direção à frente): "Resultado em 45 dias ou o seu dinheiro de volta"
- 3º: ao longo do fundo do estande 3, ao lado do mesmo pilar do canto, com o QR Code Tatuador de Elite virado para o corredor

## Arquivos

- `index.html` — modelo 3D (Three.js), arquivo único
- `assets/logo-tatuador-de-elite.png` — logo enviada (300 × 50 px)
- `assets/banners/` — banners originais dos tatuadores (placas 1, 3, 4 e 6), a arte da marca (placas 7 e 8), os painéis de tatuadores (estande-3-tatuadores-1 a 3, verso das placas 6, 5 e 4), a arte "Marketing para Tatuadores" (placas 9 e 10), os patrocinadores (placas 2 e 5) e as artes dos balcões
- `docs/especificacao-estandes.md` — especificação completa do projeto

## Observação

A logo disponível é de baixa resolução. No modelo, o texto e as bandeiras foram redesenhados em vetor e a fênix foi ampliada. Para a plotagem real das testeiras, é necessário o arquivo da logo em alta resolução (SVG, PDF ou PNG grande).
