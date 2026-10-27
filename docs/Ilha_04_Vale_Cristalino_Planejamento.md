# Ilha 04 — Vale Cristalino

> **Projeto:** Fragmentos do Infinito (Roblox)  
> **Fase:** documentação e referências; não equivale a modelos 3D ou mecânicas implementadas.  
> **Fonte:** atlas histórico de biomas, mobs, drops e armaduras fornecido no projeto.

## Visão geral

Ilha 04 de caça. Abaixo estão os dados originais recuperados do atlas histórico **Fragmentos_do_Infinito_Atlas_Mobs_Drops_Armaduras.html**. Nomes de criaturas, armaduras, materiais e probabilidades devem permanecer consistentes com esse registro.

Território instável onde cristais energizados crescem sobre ruínas e fendas no solo.

**Solo e relevo:** Pedra escura e terra mineral com cristais incrustados, placas rachadas e veios luminosos. Evite deixar todo o chão brilhando.

**Ponto de atenção:** A cor emissiva deve marcar apenas cristais e pontos-chave; contraste com áreas opacas para não poluir a cena.

## Direção de arte e assets

### Natureza e relevo

- **Cristais pequenos e gigantes:** Famílias de formatos
- **Fungos bioluminescentes:** Luz localizada
- **Plantas translúcidas:** Flora alienígena
- **Árvores petrificadas:** Silhueta inconfundível
- **Pedras geométricas:** Variação mineral

### Construções e decoração

- **Poços de extração:** Mineração abandonada
- **Obeliscos quebrados:** Ruínas antigas
- **Elevadores e pontes suspensas:** Travessia vertical
- **Monólitos de energia:** Pontos narrativos
- **Cavernas cristalinas:** Exploração subterrânea

### Texturas e recursos

- **Rocha escura:** Terreno / base
- **Pedra fraturada:** Terreno / fissuras
- **Quartzo energético:** Coletável
- **Cristal luminescente:** Coletável raro
- **Minério condutor:** Forja / dispositivos
- **Pó de cristal:** Refino

## Leviantes e conjuntos derivados

| Criatura | Classe | Características | Armadura | Direção visual da armadura |
| --- | --- | --- | --- | --- |
| Prismakar | Predador | Quadrúpede cujas escamas desviam luz e cujas garras lascam quartzo. | **Escama Prismática** | Escamas facetadas pequenas nas luvas e peitoral, couro escuro entre as juntas |
| Obelkar | Predador | Fera de pedra escura e carapaça de cristal com chifre denso. | **Traje do Cristal Negro** | Placas escuras irregulares e chifre lapidado formando fechos e uma viseira curta |
| Krysalor | Leviante • chefe | Leviante refrator; coroa mineral e espinhos que desviam feixes de luz. | **Guarda-Prisma** | Cota simples com fragmentos translúcidos no colar e bordas discretamente luminosas |

## Drops originais (chance por abate)

As porcentagens são as chances sugeridas pelo atlas, sujeitas a balanceamento. Não inferir exclusividade mútua entre itens.

| Leviante | Material comum | Chance | Material raro | Chance | Material especial | Chance |
| --- | --- | ---: | --- | ---: | --- | ---: |
| Prismakar | Escama Prismática | 83% | Garra de Quartzo | 42% | Fragmento Focal | 11% |
| Obelkar | Placa de Obsidiana | 79% | Chifre Gemado | 38% | Coração Condutor | 10% |
| Krysalor | Carapaça Refratora | 74% | Coroa Prismal | 31% | Essência Radiante | 8% |

## Mineração e fundição

| Minério | Produto refinado | Chance no atlas |
| --- | --- | ---: |
| Minério de Quartzal | Barra de Quartzal | 70% |
| Minério Condutor | Liga Condutora | 24% |
| Minério Prismal | Lingote Prismal | 6% |

## Receitas preliminares

A proposta do atlas para cada conjunto é **8 unidades do primeiro drop + 4 do segundo + 1 do terceiro + 2 barras locais**. Quantidades de barras específicas devem ser escolhidas no balanceamento da forja; não há sistema de crafting confirmado como implementado.

- **Escama Prismática:** 8× Escama Prismática, 4× Garra de Quartzo, 1× Fragmento Focal, 2× barras locais.
- **Traje do Cristal Negro:** 8× Placa de Obsidiana, 4× Chifre Gemado, 1× Coração Condutor, 2× barras locais.
- **Guarda-Prisma:** 8× Carapaça Refratora, 4× Coroa Prismal, 1× Essência Radiante, 2× barras locais.

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
- [Catálogo visual da Ilha 04](../catalogos/Ilha_04_Vale_Cristalino.html)

**Observação de consistência:** o Refúgio dos Errantes continua reservado ao lobby. Embora o atlas antigo agrupasse Gravalhor, Torogar e Brontar sob o identificador interno `refugio`, esses Leviantes pertencem às **Escarpas Ancestrais** no plano atual. Sempre distinguir referências conceituais de conteúdo já implementado.
