# Ilha 07 — Abismo Estelar

> **Projeto:** Fragmentos do Infinito (Roblox)  
> **Fase:** documentação e referências; não equivale a modelos 3D ou mecânicas implementadas.  
> **Fonte:** atlas histórico de biomas, mobs, drops e armaduras fornecido no projeto.

## Visão geral

Ilha 07 de caça. Abaixo estão os dados originais recuperados do atlas histórico **Fragmentos_do_Infinito_Atlas_Mobs_Drops_Armaduras.html**. Nomes de criaturas, armaduras, materiais e probabilidades devem permanecer consistentes com esse registro.

Fragmento quase sem luz, com flora alienígena, ruínas suspensas e energia desconhecida.

**Solo e relevo:** Rocha arroxeada, fissuras profundas e áreas de pó cósmico; vegetação luminosa pontual para orientar a navegação.

**Ponto de atenção:** Use silhuetas gigantes, brumas leves e luzes de direção, sem comprometer a visibilidade do combate.

## Direção de arte e assets

### Natureza e relevo

- **Flora luminescente:** Formas alienígenas
- **Cogumelos gigantes:** Cobertura e escala
- **Espinhos minerais:** Perigo natural
- **Pilares rochosos:** Verticalidade
- **Nuvens de partículas:** Atmosfera controlada

### Construções e decoração

- **Arcos de civilização perdida:** Pontos de interesse
- **Plataformas suspensas:** Travessias avançadas
- **Santuários partidos:** Segredos
- **Destroços de aeronaves:** Consequência de expedições
- **Observatório antigo:** Grande marco visual

### Texturas e recursos

- **Rocha sombria:** Terreno / base
- **Poeira estelar:** Terreno / camada
- **Mineral gravitacional:** Coletável / tecnologia
- **Cristal do vazio:** Coletável raro
- **Metal antigo:** Construção / aeronaves
- **Essência anômala:** Recompensa de Leviante

## Leviantes e conjuntos derivados

| Criatura | Classe | Características | Armadura | Direção visual da armadura |
| --- | --- | --- | --- | --- |
| Umbryon | Predador | Corvo colossal do vazio; plumagem negra e olhos violeta, caçador noturno. | **Penas do Eclipse** | Capuz de caçador, penas pretas em camadas, máscara de bico estilizada e couro fosco |
| Nethrakar | Predador | Caçador alienígena de carapaça escura, membros longos e espinhos curvos. | **Couro do Vazio** | Couro negro ajustado e carapaça leve nos antebraços, espinhos curtos nas luvas |
| Noxaryon | Leviante • chefe | Leviante cósmico cuja ossatura emite pequenas pulsações do vazio. | **Ecos do Abismo** | Manto preto de trama firme, pequenos ossos prateados na gola e bordas púrpura discretas |

## Drops originais (chance por abate)

As porcentagens são as chances sugeridas pelo atlas, sujeitas a balanceamento. Não inferir exclusividade mútua entre itens.

| Leviante | Material comum | Chance | Material raro | Chance | Material especial | Chance |
| --- | --- | ---: | --- | ---: | --- | ---: |
| Umbryon | Pluma Sombria | 82% | Garra do Crepúsculo | 41% | Bico Umbral | 11% |
| Nethrakar | Carapaça Vazia | 78% | Espinho Anômalo | 35% | Núcleo de Gravidade | 10% |
| Noxaryon | Membrana Abissal | 70% | Osso do Eclipse | 29% | Essência do Vazio | 7% |

## Mineração e fundição

| Minério | Produto refinado | Chance no atlas |
| --- | --- | ---: |
| Minério de Umbrita | Barra de Umbrita | 70% |
| Minério Gravítico | Liga Gravítica | 24% |
| Minério do Vazio | Lingote Sombrio | 6% |

## Receitas preliminares

A proposta do atlas para cada conjunto é **8 unidades do primeiro drop + 4 do segundo + 1 do terceiro + 2 barras locais**. Quantidades de barras específicas devem ser escolhidas no balanceamento da forja; não há sistema de crafting confirmado como implementado.

- **Penas do Eclipse:** 8× Pluma Sombria, 4× Garra do Crepúsculo, 1× Bico Umbral, 2× barras locais.
- **Couro do Vazio:** 8× Carapaça Vazia, 4× Espinho Anômalo, 1× Núcleo de Gravidade, 2× barras locais.
- **Ecos do Abismo:** 8× Membrana Abissal, 4× Osso do Eclipse, 1× Essência do Vazio, 2× barras locais.

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
- [Catálogo visual da Ilha 07](../catalogos/Ilha_07_Abismo_Estelar.html)

**Observação de consistência:** o Refúgio dos Errantes continua reservado ao lobby. Embora o atlas antigo agrupasse Gravalhor, Torogar e Brontar sob o identificador interno `refugio`, esses Leviantes pertencem às **Escarpas Ancestrais** no plano atual. Sempre distinguir referências conceituais de conteúdo já implementado.
