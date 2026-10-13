# Plano de design: site da Vany

## 1. Plano inicial

### Ideia central
A página é o chão do terreiro. O fundo é terra batida. Sobre ele ficam objetos preparados à mão: cada pacote é um rótulo de papel, como os rótulos de banho de ervas, vela e defumador das casas de artigos religiosos. Esse rótulo é o único elemento ousado do site. O resto fica calmo.

### Cores (todas a confirmar com a Vany)
Atualizadas a partir da arte mensal da Vany: vinho profundo, cobre rosado e carmim. Ficaram só as cores. Lua, estrelas, cristais, tarô, zodíaco e letra cursiva ficaram de fora, porque estão na lista do que não usar.

| Nome | Hex | Papel |
|---|---|---|
| Vinho de oferenda | #3E1520 | Fundo principal da página |
| Papel rosado | #F2E6DE | Papel dos rótulos e das seções de leitura longa; texto sobre o vinho |
| Cobre rosado | #E3A47E | Botões principais e o nome "Vany" na abertura |
| Fumo | #2A1015 | Texto sobre o papel |
| Arruda | #55663F | Pacote holístico e links sobre o papel |

Cores próprias de cada pacote (só nos rótulos):
| Pacote | Inspiração | Cor | Hex |
|---|---|---|---|
| Página Virada / Castigo do Ex | Iansã | Cobre | #9C3D23 |
| Fogo de Padilha | Maria Padilha | Vermelho rosa-velha + preto | #8E1622 / #1E1414 |
| Mel de Oxum | Oxum | Mel escuro (texto) / mel (faixa) | #8A5A00 / #C98A12 |
| Brilho de Cleópatra | Cleópatra | Lápis-lazúli | #22406B |
| Holístico | Ervas | Arruda | #55663F |

As cores de orixá e entidade variam de casa para casa. A Vany precisa aprovar cada uma.

### Fontes
Bodoni Moda, nos títulos e no nome "Vany" (em itálico). Alto contraste, com traços finíssimos e curvas longas: delicada e sensual, como o nome num frasco de perfume ou de óleo preparado à mão. Substituiu a Rozha One, que era pesada demais para o tom que a Vany quer.

Alegreya Sans, no texto. Uma sem serifa humanista, com traço de caligrafia, quente e muito legível no celular. Tem todos os acentos do português.

As duas são bem diferentes entre si: uma pesada e decorativa, a outra leve e de leitura. Escala: texto 19px, subtítulos 1.5rem, títulos de seção 2.4rem, nome da abertura entre 8rem e 20rem. Linhas de texto com até 62 caracteres.

### Esboço (celular)
```
┌─────────────────────────────┐
│ Vany      Pacotes  Contato  │
├─────────────────────────────┤
│ VANY  (letra gigante, cor   │  abertura em terra batida
│        de cera, sangrando)  │  único movimento: o nome
│   ┌───────────────────────┐ │  acende como vela
│   │ FOTO A TIRAR: mãos da │ │
│   │ Vany com as guias,    │ │
│   │ luz de vela           │ │
│   └───────────────────────┘ │
│ frase da Vany               │
│ [ Ver pacotes ]             │
├─────────────────────────────┤
│ Sobre: foto do espaço,      │
│ texto curto                 │
├─────────────────────────────┤
│  ╱‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾╲    │  rótulos de papel com
│ │ Iansã (faixa cobre)    │   │  cantos cortados, borda
│ │ Página Virada          │   │  dupla e leve inclinação
│ │ para quem / inclui     │   │
│ │ R$ ... por mês         │   │
│ │ [Assinar no cartão]    │   │
│ │ [Pagar 1 mês no Pix]   │   │
│  ╲______________________╱    │
│   (um rótulo por pacote)    │
├─────────────────────────────┤
│ Avulsos: lista simples,     │
│ nome, descrição, preço      │
├─────────────────────────────┤
│ Como funciona: 1 2 3 4      │  numeração só aqui, porque
│                             │  é uma sequência real
├─────────────────────────────┤
│ Perguntas  (papel)          │
│ Contato    [Chamar no Whats]│
│ Políticas  (papel)          │
│ Rodapé                      │
└─────────────────────────────┘
                        (Whats)
```

### Três princípios que fazem o site ser só da Vany
1. Os pacotes são objetos de terreiro, não cartões de site: rótulos de papel preparados à mão, cada um na cor da sua inspiração.
2. A paleta sai do material do trabalho dela (terra, algodão cru, cera, fumo, arruda), e não de um "site esotérico".
3. A abertura é o nome dela usado como desenho, junto da foto das mãos com as guias. Nada de título centralizado sobre gradiente.

## 2. Revisão: o que trocou

1. Fundo da página em algodão cru com título serifado. Isso é o "creme com serifa" de qualquer site de terapia. Troquei: o fundo virou terra batida, e o algodão cru ficou só no papel dos rótulos e nas seções de leitura longa.
2. Botões e detalhes em dourado. Viraria "brilho dourado". Troquei por cera de vela, uma cor chapada e fosca, sem gradiente e sem brilho.
3. Ícones de folhas e ervas desenhados nos rótulos. Qualquer marca de cosmético natural usa. Tirei. O rótulo se apoia só em tipografia, borda e cor.
4. Rótulo pequeno em caixa alta acima de cada título. Está na lista proibida. Tirei: cada seção abre direto no título.
5. Cartões dos avulsos. Eram mais uma grade de cartões iguais. Viraram uma lista simples, como a tabela de preços da casa.

## 3. Elemento decorativo retirado antes da entrega
O furo com barbante desenhado no topo de cada rótulo. Os cantos cortados e a borda dupla já dizem "rótulo". O barbante só pesava.

## 4. Ajuste: mais delicado, sensual e espiritual
- Títulos trocados para Bodoni Moda; o nome "Vany" em itálico.
- Rótulos com fio duplo fino no lugar da borda grossa, cantos menores, inclinação mais leve e faixa da inspiração em itálico com um fio embaixo.
- Botões com borda fina e peso de letra mais leve.
- Uma luz baixa de vela atrás do nome na abertura. É o único brilho da página.
