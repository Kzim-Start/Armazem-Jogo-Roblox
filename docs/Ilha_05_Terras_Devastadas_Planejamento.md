# Ilha 05 — Terras Devastadas

> **Projeto:** Fragmentos do Infinito (Roblox)  
> **Fase:** documentação e referências; não equivale a modelos 3D ou mecânicas implementadas.  
> **Fonte:** atlas histórico de biomas, mobs, drops e armaduras fornecido no projeto.

## Visão geral

Ilha 05 de caça. Abaixo estão os dados originais recuperados do atlas histórico **Fragmentos_do_Infinito_Atlas_Mobs_Drops_Armaduras.html**. Nomes de criaturas, armaduras, materiais e probabilidades devem permanecer consistentes com esse registro.

Fragmento vulcânico hostil, com fortalezas em ruínas e Leviantes resistentes ao calor.

**Solo e relevo:** Basalto quebrado, cinzas, crateras e rocha avermelhada; veios de lava apenas em pontos de perigo e ambientação.

**Ponto de atenção:** Crie uma arena com cobertura visual suficiente para o jogador distinguir ataques de área e zonas quentes.

## Direção de arte e assets

### Natureza e relevo

- **Rochas pontiagudas:** Silhuetas recortadas
- **Vegetação carbonizada:** Troncos e galhos secos
- **Fumarolas:** Vapor em pontos específicos
- **Fendas com lava:** Perigo localizado
- **Cristais de magma:** Destaques quentes

### Construções e decoração

- **Fortaleza abandonada:** Marco no horizonte
- **Pontes metálicas danificadas:** Travessias
- **Correntes e gaiolas:** Atmosfera industrial medieval
- **Altares de pedra:** História ambiental
- **Acampamento de expedição:** Ponto de respiro

### Texturas e recursos

- **Basalto:** Terreno / rocha
- **Cinza vulcânica:** Terreno / camada
- **Obsidiana:** Coletável / lâminas
- **Minério ígneo:** Coletável / forja
- **Carvão mineral:** Coletável / combustível
- **Núcleo incandescente:** Recompensa de Leviante

## Leviantes e conjuntos derivados

| Criatura | Classe | Características | Armadura | Direção visual da armadura |
| --- | --- | --- | --- | --- |
| Magrath | Predador | Predador de couro negro, placas incandescentes e mandíbulas fortes. | **Veste das Cinzas** | Couro carbonizado, placas pequenas de escama fosca e costura cobre-vermelho |
| Vulkron | Predador | Besta grande com placas ígneas e presas de basalto. | **Escama da Caldeira** | Casaco de couro escuro com escamas dorsais em camadas e presas nos fechos |
| Volkaron | Leviante • chefe | Colosso vulcânico de couraça rubra e chifres queimados. | **Mandíbula Rubra** | Peitoral de couraça fosca, chifres recortados na gola e faixas vermelhas sem asas ou espinhos enormes |

## Drops originais (chance por abate)

As porcentagens são as chances sugeridas pelo atlas, sujeitas a balanceamento. Não inferir exclusividade mútua entre itens.

| Leviante | Material comum | Chance | Material raro | Chance | Material especial | Chance |
| --- | --- | ---: | --- | ---: | --- | ---: |
| Magrath | Pele Carbonizada | 81% | Garra Vulcânica | 40% | Glândula de Brasa | 12% |
| Vulkron | Escama Ígnea | 77% | Presa de Basalto | 36% | Núcleo de Magma | 10% |
| Volkaron | Couraça Rubra | 72% | Chifre Calcinado | 30% | Coração Ígneo | 8% |

## Mineração e fundição

| Minério | Produto refinado | Chance no atlas |
| --- | --- | ---: |
| Minério Basáltico | Barra Basáltica | 70% |
| Minério de Magmito | Liga Magmática | 24% |
| Minério Rubrídio | Lingote de Rubrídio | 6% |

## Receitas preliminares

A proposta do atlas para cada conjunto é **8 unidades do primeiro drop + 4 do segundo + 1 do terceiro + 2 barras locais**. Quantidades de barras específicas devem ser escolhidas no balanceamento da forja; não há sistema de crafting confirmado como implementado.

- **Veste das Cinzas:** 8× Pele Carbonizada, 4× Garra Vulcânica, 1× Glândula de Brasa, 2× barras locais.
- **Escama da Caldeira:** 8× Escama Ígnea, 4× Presa de Basalto, 1× Núcleo de Magma, 2× barras locais.
- **Mandíbula Rubra:** 8× Couraça Rubra, 4× Chifre Calcinado, 1× Coração Ígneo, 2× barras locais.

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
- [Catálogo visual da Ilha 05](../catalogos/Ilha_05_Terras_Devastadas.html)

**Observação de consistência:** o Refúgio dos Errantes continua reservado ao lobby. Embora o atlas antigo agrupasse Gravalhor, Torogar e Brontar sob o identificador interno `refugio`, esses Leviantes pertencem às **Escarpas Ancestrais** no plano atual. Sempre distinguir referências conceituais de conteúdo já implementado.
