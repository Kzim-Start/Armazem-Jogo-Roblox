# Ilha 06 — Reino da Geada

> **Projeto:** Fragmentos do Infinito (Roblox)  
> **Fase:** documentação e referências; não equivale a modelos 3D ou mecânicas implementadas.  
> **Fonte:** atlas histórico de biomas, mobs, drops e armaduras fornecido no projeto.

## Visão geral

Ilha 06 de caça. Abaixo estão os dados originais recuperados do atlas histórico **Fragmentos_do_Infinito_Atlas_Mobs_Drops_Armaduras.html**. Nomes de criaturas, armaduras, materiais e probabilidades devem permanecer consistentes com esse registro.

Mundo congelado de florestas nevadas, ruínas glaciais e predadores adaptados ao frio.

**Solo e relevo:** Neve em camadas, gelo aparente em lagos e pedras nas encostas. Deixe trilhas e rochas visíveis para orientar o jogador.

**Ponto de atenção:** Diferencie neve profunda, gelo liso e rocha escura para comunicar caminhos e riscos sem depender só do mapa.

## Direção de arte e assets

### Natureza e relevo

- **Pinheiros com neve:** Variar forma e altura
- **Montes de neve:** Ritmo visual do solo
- **Cristais de gelo:** Acentos próximos a cavernas
- **Rochedos congelados:** Abrigos e paredões
- **Arbustos gelados:** Vida resistente ao clima

### Construções e decoração

- **Postos de caça abandonados:** Refúgios temporários
- **Torres cobertas de gelo:** Referências no horizonte
- **Pontes congeladas:** Travessia
- **Estátuas e ruínas antigas:** Mistério
- **Trenós e suprimentos:** Detalhes narrativos

### Texturas e recursos

- **Neve:** Terreno / cobertura
- **Gelo:** Terreno / superfícies
- **Rocha de montanha:** Terreno / encostas
- **Peles resistentes:** Coletável / proteção
- **Cristal glacial:** Coletável / forja
- **Essência de geada:** Recompensa de Leviante

## Leviantes e conjuntos derivados

| Criatura | Classe | Características | Armadura | Direção visual da armadura |
| --- | --- | --- | --- | --- |
| Cryvon | Predador | Fera glacial ágil, pelagem espessa e garras de gelo. | **Manto Invernal** | Capuz forrado de pelagem, couro azul acinzentado e garras como fivelas |
| Hrimor | Predador | Predador massivo semelhante a urso, com presas cobertas por geada. | **Guarda do Inverno** | Sobreposição de peles grossas, ombros de couro robusto e presas esculpidas |
| Gelmorath | Leviante • chefe | Grande fera de gelo e rocha, com coroa natural de cristais. | **Trono de Geada** | Pelagem clara no colar, gelo opaco pequeno nos ombros e capa curta de tecido azul |

## Drops originais (chance por abate)

As porcentagens são as chances sugeridas pelo atlas, sujeitas a balanceamento. Não inferir exclusividade mútua entre itens.

| Leviante | Material comum | Chance | Material raro | Chance | Material especial | Chance |
| --- | --- | ---: | --- | ---: | --- | ---: |
| Cryvon | Pelagem Invernal | 83% | Garra de Gelo | 40% | Cristal de Frio | 11% |
| Hrimor | Couro Glacial | 77% | Presa de Geada | 36% | Medula Congelada | 10% |
| Gelmorath | Manto Boreal | 71% | Coroa de Gelo | 30% | Essência Glacial | 8% |

## Mineração e fundição

| Minério | Produto refinado | Chance no atlas |
| --- | --- | ---: |
| Minério de Glacita | Barra de Glacita | 70% |
| Minério Boreal | Liga Boreal | 24% |
| Minério de Nevicita | Lingote de Nevicita | 6% |

## Receitas preliminares

A proposta do atlas para cada conjunto é **8 unidades do primeiro drop + 4 do segundo + 1 do terceiro + 2 barras locais**. Quantidades de barras específicas devem ser escolhidas no balanceamento da forja; não há sistema de crafting confirmado como implementado.

- **Manto Invernal:** 8× Pelagem Invernal, 4× Garra de Gelo, 1× Cristal de Frio, 2× barras locais.
- **Guarda do Inverno:** 8× Couro Glacial, 4× Presa de Geada, 1× Medula Congelada, 2× barras locais.
- **Trono de Geada:** 8× Manto Boreal, 4× Coroa de Gelo, 1× Essência Glacial, 2× barras locais.

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
- [Catálogo visual da Ilha 06](../catalogos/Ilha_06_Reino_da_Geada.html)

**Observação de consistência:** o Refúgio dos Errantes continua reservado ao lobby. Embora o atlas antigo agrupasse Gravalhor, Torogar e Brontar sob o identificador interno `refugio`, esses Leviantes pertencem às **Escarpas Ancestrais** no plano atual. Sempre distinguir referências conceituais de conteúdo já implementado.
