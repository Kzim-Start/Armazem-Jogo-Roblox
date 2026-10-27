# Ilha 01 — Escarpas Ancestrais

> **Projeto:** Fragmentos do Infinito (Roblox)  
> **Fase:** documentação e referências; não equivale a modelos 3D ou mecânicas implementadas.  
> **Fonte:** atlas histórico de biomas, mobs, drops e armaduras fornecido no projeto.

## Visão geral

Ilha 01 de caça. Abaixo estão os dados originais recuperados do atlas histórico **Fragmentos_do_Infinito_Atlas_Mobs_Drops_Armaduras.html**. Nomes de criaturas, armaduras, materiais e probabilidades devem permanecer consistentes com esse registro.

Terreno rochoso de cânions e penhascos flutuantes, ruínas, antigas pontes e trilhas nas escarpas. Esta descrição usa a ambientação já aprovada na Ilha 01, e não importa as construções do lobby.

## Direção de arte e assets

### Natureza e relevo

- **Afloramentos rochosos:** variações para encostas e arenas
- **Vegetação de escarpa:** distribuição esparsa
- **Rochas altas:** sinalizadores de navegação

### Construções e decoração

- **Ruínas de pedra:** identidade da ilha
- **Pontes antigas:** travessia entre penhascos
- **Marcos de caça:** orientação e progressão

### Texturas e recursos

- **Pedra rachada:** paredes e caminho
- **Terra pedregosa:** trilhas
- **Ferrita, calcário e aurélio:** mineração do bioma

## Leviantes e conjuntos derivados

| Criatura | Classe | Características | Armadura | Direção visual da armadura |
| --- | --- | --- | --- | --- |
| Gravalhor | Predador | Quadrúpede de granito, veios minerais azuis e mandíbula larga. | **Couraça dos Desfiladeiros** | Couro castanho, sobreposições de pedra nas ombreiras e luvas, pequeno pingente azul |
| Torogar | Predador | Fera montanhosa de presas curvas, dorso blindado e patas pesadas. | **Traje do Quebra-Rochas** | Colete de couro áspero, presas nas tiras do ombro, botas de couro costurado |
| Brontar | Leviante • chefe | Guardião das pontes; galhadas minerais e tremores que racham o chão. | **Vigia das Pontes** | Capacete discreto de pedra talhada, ombreiras de couraça e faixas azuis discretas |

## Drops originais (chance por abate)

As porcentagens são as chances sugeridas pelo atlas, sujeitas a balanceamento. Não inferir exclusividade mútua entre itens.

| Leviante | Material comum | Chance | Material raro | Chance | Material especial | Chance |
| --- | --- | ---: | --- | ---: | --- | ---: |
| Gravalhor | Placa Rochosa | 82% | Garra de Pedra | 41% | Núcleo Estável | 12% |
| Torogar | Couro Resistente | 79% | Presa Colossal | 36% | Osso Ancestral | 11% |
| Brontar | Couraça Ancestral | 72% | Chifre do Guardião | 31% | Essência Pétrea | 9% |

## Mineração e fundição

| Minério | Produto refinado | Chance no atlas |
| --- | --- | ---: |
| Minério de Ferrita | Barra de Ferrita | 70% |
| Minério Calcário | Liga Calcária | 24% |
| Minério de Aurélio | Lingote de Aurélio | 6% |

## Receitas preliminares

A proposta do atlas para cada conjunto é **8 unidades do primeiro drop + 4 do segundo + 1 do terceiro + 2 barras locais**. Quantidades de barras específicas devem ser escolhidas no balanceamento da forja; não há sistema de crafting confirmado como implementado.

- **Couraça dos Desfiladeiros:** 8× Placa Rochosa, 4× Garra de Pedra, 1× Núcleo Estável, 2× barras locais.
- **Traje do Quebra-Rochas:** 8× Couro Resistente, 4× Presa Colossal, 1× Osso Ancestral, 2× barras locais.
- **Vigia das Pontes:** 8× Couraça Ancestral, 4× Chifre do Guardião, 1× Essência Pétrea, 2× barras locais.

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
- [Catálogo visual completo original da Ilha 01](../catalogos/Ilha_01_Escarpas_Ancestrais.html)

**Observação de consistência:** o Refúgio dos Errantes continua reservado ao lobby. Embora o atlas antigo agrupasse Gravalhor, Torogar e Brontar sob o identificador interno `refugio`, esses Leviantes pertencem às **Escarpas Ancestrais** no plano atual. Sempre distinguir referências conceituais de conteúdo já implementado.
