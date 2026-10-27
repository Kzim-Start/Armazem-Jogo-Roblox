# Ilha 02 — Floresta Ancestral

> **Projeto:** Fragmentos do Infinito (Roblox)  
> **Fase:** documentação e referências; não equivale a modelos 3D ou mecânicas implementadas.  
> **Fonte:** atlas histórico de biomas, mobs, drops e armaduras fornecido no projeto.

## Visão geral

Ilha 02 de caça. Abaixo estão os dados originais recuperados do atlas histórico **Fragmentos_do_Infinito_Atlas_Mobs_Drops_Armaduras.html**. Nomes de criaturas, armaduras, materiais e probabilidades devem permanecer consistentes com esse registro.

Primeiro mundo explorável, com biodiversidade densa, cavernas e um Leviante territorial.

**Solo e relevo:** Solo irregular, terra úmida e raízes à mostra; manchas de grama, pedras cobertas por musgo e clareiras para combate.

**Ponto de atenção:** A clareira do primeiro Leviante precisa de espaço para esquiva, leitura de ataques e coleta de materiais após a luta.

## Direção de arte e assets

### Natureza e relevo

- **Árvores altas e retorcidas:** Misturar 3–4 silhuetas
- **Samambaias e arbustos:** Volumes baixos e médios
- **Raízes expostas:** Cruzar trilhas e árvores
- **Cogumelos luminosos:** Sinalizar áreas especiais
- **Folhas, galhos e troncos:** Cobertura esparsa no chão
- **Rochas com musgo:** Acentos de relevo

### Construções e decoração

- **Ruínas tomadas por vegetação:** Pontos de interesse
- **Ponte de madeira antiga:** Travessia de rio e ravina
- **Acampamento abandonado:** Narrativa ambiental
- **Totens e marcos de caça:** Sinalização de perigos
- **Pequenas cavernas:** Materiais raros
- **Restos de máquinas antigas:** Indício da Grande Ruptura

### Texturas e recursos

- **Terra úmida:** Terreno / lama
- **Grama de floresta:** Terreno / manchas
- **Musgo e casca de árvore:** Texturas
- **Madeira ancestral:** Coletável / construção
- **Fibra vegetal:** Coletável / artesanato
- **Minério comum:** Coletável / forja
- **Essência natural:** Recompensa de caçada

## Leviantes e conjuntos derivados

| Criatura | Classe | Características | Armadura | Direção visual da armadura |
| --- | --- | --- | --- | --- |
| Virdrak | Predador | Fera coberta de casca viva; membros longos e garras de raízes. | **Veste de Casca Viva** | Túnica flexível de linho com placas de casca nas canelas e braçadeiras |
| Mosskar | Predador | Grande cervídeo rochoso, galhadas retorcidas e pelo coberto de musgo. | **Manto do Galheiro** | Manto curto de pelagem musgosa, fivelas de galhada e cintos de cipó |
| Sylvarok | Leviante • chefe | Colosso de raízes e troncos, que faz espinhos emergirem do solo. | **Coração da Mata** | Peitoral de casca trabalhada, pequenas raízes na gola e capa de folhas costuradas |

## Drops originais (chance por abate)

As porcentagens são as chances sugeridas pelo atlas, sujeitas a balanceamento. Não inferir exclusividade mútua entre itens.

| Leviante | Material comum | Chance | Material raro | Chance | Material especial | Chance |
| --- | --- | ---: | --- | ---: | --- | ---: |
| Virdrak | Casca Viva | 83% | Garra Enraizada | 42% | Seiva Cintilante | 12% |
| Mosskar | Pelagem Musgosa | 78% | Galhada Ancestral | 37% | Coração de Madeira | 11% |
| Sylvarok | Escama de Raiz | 71% | Coroa de Ramos | 32% | Essência da Mata | 9% |

## Mineração e fundição

| Minério | Produto refinado | Chance no atlas |
| --- | --- | ---: |
| Minério de Raizferro | Barra de Raizferro | 70% |
| Minério Silvano | Lingote Silvano | 24% |
| Minério Verdejante | Liga Verdejante | 6% |

## Receitas preliminares

A proposta do atlas para cada conjunto é **8 unidades do primeiro drop + 4 do segundo + 1 do terceiro + 2 barras locais**. Quantidades de barras específicas devem ser escolhidas no balanceamento da forja; não há sistema de crafting confirmado como implementado.

- **Veste de Casca Viva:** 8× Casca Viva, 4× Garra Enraizada, 1× Seiva Cintilante, 2× barras locais.
- **Manto do Galheiro:** 8× Pelagem Musgosa, 4× Galhada Ancestral, 1× Coração de Madeira, 2× barras locais.
- **Coração da Mata:** 8× Escama de Raiz, 4× Coroa de Ramos, 1× Essência da Mata, 2× barras locais.

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
- [Catálogo visual da Ilha 02](../catalogos/Ilha_02_Floresta_Ancestral.html)

**Observação de consistência:** o Refúgio dos Errantes continua reservado ao lobby. Embora o atlas antigo agrupasse Gravalhor, Torogar e Brontar sob o identificador interno `refugio`, esses Leviantes pertencem às **Escarpas Ancestrais** no plano atual. Sempre distinguir referências conceituais de conteúdo já implementado.
