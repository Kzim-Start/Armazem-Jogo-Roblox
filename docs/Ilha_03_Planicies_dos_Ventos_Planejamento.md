# Ilha 03 — Planícies dos Ventos

> **Projeto:** Fragmentos do Infinito (Roblox)  
> **Fase:** documentação e referências; não equivale a modelos 3D ou mecânicas implementadas.  
> **Fonte:** atlas histórico de biomas, mobs, drops e armaduras fornecido no projeto.

## Visão geral

Ilha 03 de caça. Abaixo estão os dados originais recuperados do atlas histórico **Fragmentos_do_Infinito_Atlas_Mobs_Drops_Armaduras.html**. Nomes de criaturas, armaduras, materiais e probabilidades devem permanecer consistentes com esse registro.

Campos abertos onde ruínas, vales e correntes de ar conduzem a exploração.

**Solo e relevo:** Grama curta e terra seca em manchas largas; trilhas gastas, rochas baixas e ondulações suaves que quebram a sensação de tapete.

**Ponto de atenção:** Use o vento como identidade: capins inclinados, bandeiras em movimento, moinhos antigos e passagens para planadores.

## Direção de arte e assets

### Natureza e relevo

- **Capim alto e baixo:** Agrupamentos com densidades diferentes
- **Árvores isoladas:** Sombras e pontos de orientação
- **Flores campestres:** Pequenas manchas coloridas
- **Pedras planas:** Variação no solo
- **Arbustos resistentes:** Próximos a paredões

### Construções e decoração

- **Moinhos de vento antigos:** Marco visual
- **Pontes de corda:** Entre platôs
- **Ruínas de postos de vigia:** Exploração
- **Marcos de pedra:** Guia de rota
- **Carroças e cercas:** Vestígios de antigos viajantes

### Texturas e recursos

- **Grama seca:** Terreno / camada
- **Terra arenosa:** Terreno / trilhas
- **Calcário:** Pedra / formação
- **Fibra de capim:** Coletável
- **Pedra de vento:** Coletável especial
- **Madeira leve:** Coletável / aeronave

## Leviantes e conjuntos derivados

| Criatura | Classe | Características | Armadura | Direção visual da armadura |
| --- | --- | --- | --- | --- |
| Aeronox | Predador | Ave caçadora de médio-grande porte, penas rígidas e mergulho cortante. | **Traje do Rasante** | Penas longas nas costas e punhos, couro leve e meia-máscara de bico original |
| Valcron | Predador | Fera de pernas potentes, crista óssea e membranas que canalizam correntes de ar. | **Veste do Corredor** | Peças estreitas de escama, braçadeiras com membrana curta e botas leves |
| Torvak | Leviante • chefe | Senhor das rajadas; besta alada de ossatura larga e plumas prateadas. | **Sentinela dos Ventos** | Pele leve, leque de penas no ombro e fivela confeccionada com osso alar |

## Drops originais (chance por abate)

As porcentagens são as chances sugeridas pelo atlas, sujeitas a balanceamento. Não inferir exclusividade mútua entre itens.

| Leviante | Material comum | Chance | Material raro | Chance | Material especial | Chance |
| --- | --- | ---: | --- | ---: | --- | ---: |
| Aeronox | Pena Cortavento | 84% | Garra de Rasante | 40% | Membrana Aerada | 12% |
| Valcron | Escama Veloz | 79% | Espora de Vento | 38% | Glândula de Brisa | 10% |
| Torvak | Pluma da Tempestade | 72% | Osso Alar | 30% | Essência do Vendaval | 9% |

## Mineração e fundição

| Minério | Produto refinado | Chance no atlas |
| --- | --- | ---: |
| Minério de Aerita | Barra de Aerita | 70% |
| Minério de Venturita | Liga de Venturita | 24% |
| Minério de Alísio | Lingote de Alísio | 6% |

## Receitas preliminares

A proposta do atlas para cada conjunto é **8 unidades do primeiro drop + 4 do segundo + 1 do terceiro + 2 barras locais**. Quantidades de barras específicas devem ser escolhidas no balanceamento da forja; não há sistema de crafting confirmado como implementado.

- **Traje do Rasante:** 8× Pena Cortavento, 4× Garra de Rasante, 1× Membrana Aerada, 2× barras locais.
- **Veste do Corredor:** 8× Escama Veloz, 4× Espora de Vento, 1× Glândula de Brisa, 2× barras locais.
- **Sentinela dos Ventos:** 8× Pluma da Tempestade, 4× Osso Alar, 1× Essência do Vendaval, 2× barras locais.

### Acabamentos visuais opcionais

Base: couro, tecido e anatomia do Leviante visíveis. Divino: detalhes dourados discretos. Sombrio: escurecimento dos materiais e runas pequenas. Elemental: sinais moderados do elemento do Leviante. Todos mantêm a silhueta e a legibilidade do modelo original.

## Checklist de implementação no Blender e Roblox Studio

- [ ] Aprovar direção de arte e escala do mapa.
- [ ] Modelar módulos ambientais reutilizáveis, materiais e pontos de interesse.
- [ ] Modelar cada Leviante com silhueta distinta e animações de ataque anunciadas.
- [ ] Produzir modelos de armadura para rig compatível com Roblox.
- [ ] Produzir ícones e modelos dos nove drops e três minérios.
- [ ] Implementar coleta, chance de drop, receita, forja e teste do combate.
- [ ] Testar orçamento de triângulos, colisões, UVs, materiais, LOD e desempenho nos dispositivos-alvo.
- [ ] Verificar o conteúdo em Roblox Studio antes de declarar qualquer elemento como pronto.

## Navegação

- [Índice dos biomas](INDEX_BIOMAS.md)
- [Catálogo visual da Ilha 03](../catalogos/Ilha_03_Planicies_dos_Ventos.html)

**Observação de consistência:** o Refúgio dos Errantes continua reservado ao lobby. Embora o atlas antigo agrupasse Gravalhor, Torogar e Brontar sob o identificador interno `refugio`, esses Leviantes pertencem às **Escarpas Ancestrais** no plano atual. Sempre distinguir referências conceituais de conteúdo já implementado.
