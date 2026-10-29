# Auditoria visual pendente — sete ilhas e 21 Leviantes

**Projeto:** Fragmentos do Infinito · **Data do levantamento:** 29/10/2026
**Escopo:** verificação das imagens dos grandes catálogos HTML, distinção de armaduras, criaturas e cenários, antes de transformar as referências em modelos de Blender/Roblox Studio.

## Situação comprovada

- [x] Documentação de sete ilhas e respectivos 21 Leviantes está presente.
- [x] Existem sete catálogos HTML originais, preservados.
- [x] Atlas SVG de armaduras V1 já existia e foi mantido.
- [x] [Revisão V2 das 21 silhuetas](../catalogos/PRANCHAS_SILHUETAS_21_V2.html) adicionada: 21 desenhos frontais individuais; há um modo de comparação monocromática.
- [x] [Plantas conceituais de sete mapas](../catalogos/ESTUDOS_MAPAS_7_ILHAS.html) adicionadas, com três posições propostas por ilha.
- [ ] **Ainda falta inspeção visual real, imagem a imagem, das ilustrações incorporadas aos sete catálogos HTML grandes.** O conteúdo embutido desses arquivos excedeu a capacidade de leitura de conteúdo pelo conector durante esta revisão. Isso **não demonstra que as imagens estão ausentes**, nem comprova que estão corretas.
- [ ] Não existem nesta auditoria renderizações 3D de todas as 21 armaduras aprovadas para produção. SVG = referência 2D, não malha 3D.

## Matriz de validação

| Ilha | Leviantes a inspecionar | Armaduras a inspecionar | Marcos do cenário | Estado |
| --- | --- | --- | --- | --- |
| 01 — Escarpas Ancestrais | Gravalhor, Torogar, Brontar | Couraça dos Desfiladeiros, Traje do Quebra-Rochas, Vigia das Pontes | Penhascos, ponte, ruína | Imagens individuais não validadas |
| 02 — Floresta Ancestral | Virdrak, Mosskar, Sylvarok | Veste de Casca Viva, Manto do Galheiro, Coração da Mata | Rio, clareira, caverna | Imagens individuais não validadas |
| 03 — Planícies dos Ventos | Aeronox, Valcron, Torvak | Traje do Rasante, Veste do Corredor, Sentinela dos Ventos | Campo, moinho, mirante | Imagens individuais não validadas |
| 04 — Vale Cristalino | Prismakar, Obelkar, Krysalor | Escama Prismática, Traje do Cristal Negro, Guarda-Prisma | Fenda, mina, monólito | Imagens individuais não validadas |
| 05 — Terras Devastadas | Magrath, Vulkron, Volkaron | Veste das Cinzas, Escama da Caldeira, Mandíbula Rubra | Lava, fortaleza, cratera | Imagens individuais não validadas |
| 06 — Reino da Geada | Cryvon, Hrimor, Gelmorath | Manto Invernal, Guarda do Inverno, Trono de Geada | Lago gelado, torre, ravina | Imagens individuais não validadas |
| 07 — Abismo Estelar | Umbryon, Nethrakar, Noxaryon | Penas do Eclipse, Couro do Vazio, Ecos do Abismo | Plataforma, observatório, santuário | Imagens individuais não validadas |

## Checklist **por Leviante** (repetir 21 vezes)

- [ ] Retrato integral frontal do Leviante; o corpo não deve ser apenas uma recoloração de outra criatura.
- [ ] Perfil lateral, porte relativo a um avatar R15 e área de alcance das principais habilidades.
- [ ] Anatomia coerente com a ficha: número de membros, galhadas, asas, carapaça, rocha, pelo e outras propriedades específicas.
- [ ] Nome correto e nenhuma imagem repetida acidentalmente entre criaturas.
- [ ] Origem própria do design e ausência de elementos copiados de Dauntless.

## Checklist **por armadura** (repetir 21 vezes)

- [ ] Conferir retrato ilustrado, nome da armadura e Leviante de origem no HTML correspondente.
- [ ] Comparar em preto: cabeça, ombros e tronco precisam ser reconhecíveis mesmo sem cores.
- [ ] Vista frontal, perfil e costas com pontos de clipping e articulação R15.
- [ ] Diferença real de materiais (rocha, couro, pelo, osso, madeira, penas, cristal), além da paleta.
- [ ] Troféu característico, acabamento e receita/drops coerentes com o planejamento.
- [ ] Verificar transparências, links quebrados, distorção de proporção e imagens repetidas.
- [ ] Validar a simplicidade de modelagem, UV/material e desempenho nos aparelhos-alvo antes de fechar como asset final.

## Checklist **por mapa** (repetir sete vezes)

- [ ] Mostrar imagem de visão geral da ilha, incluindo referências de escala.
- [ ] Confirmar três arenas com leitura clara de silhuetas, espaço de esquiva e linhas de visão.
- [ ] Diferenciar o bioma pelo solo, relevo, flora, arquitetura e iluminação — não só por cor.
- [ ] Confirmar entrada, rotas, atalhos, mineração, recursos e orientação do jogador.
- [ ] Testar colisões, pontos de travessia e desempenho no Roblox Studio.
- [ ] Registrar capturas reais do Studio quando o cenário estiver construído; não substituir por ilustrações conceituais.

## Ordem de revisão

1. Fazer auditoria de **Escarpas Ancestrais** e do Refúgio (lobby separado, sem caçadas), começando pelas imagens dos HTMLs originais e a versão `REVISAO_VISUAL`.
2. Repetir por Floresta, Planícies, Vale, Terras, Geada e Abismo.
3. Quando a imagem de uma criatura/armadura/cenário for aprovada, registrar arquivo-fonte Blender, render de referência, versão, dimensões e destino no Roblox Studio.
4. **Não marcar como aprovado** com base somente na existência de um nome, um link, um SVG ou uma miniatura.

## Fontes internas

- [Índice visual dos biomas](../catalogos/INDEX_BIOMAS.html)
- [Atlas técnico original das armaduras](../catalogos/ATLAS_ARMADURAS_21.html)
- [Matriz de identidade visual](MATRIZ_IDENTIDADE_VISUAL_ARMADURAS.md)

Este documento acompanha entregas e pendências, mas não substitui a inspeção das imagens nem testes de jogo.
