# Ilha 02 — Floresta Ancestral
## Bíblia de produção visual e de gameplay — Fragmentos do Infinito

> **Status:** Pré-produção. Conceitos e números abaixo são propostas de design, não assets 3D ou mecânicas já implementadas.  
> **Repositório:** Kzim-Start/Armazem-Jogo-Roblox  
> **Princípio:** preservar integralmente o catálogo da Ilha 01 (Escarpas Ancestrais).  
> **Escopo:** ilha de caça com dois predadores e um Leviante-chefe. O Refúgio dos Errantes é um **lobby sem monstros**, separado de todas as ilhas de caça.

## 1. Identidade da região

**Floresta Ancestral** é um fragmento flutuante onde árvores monumentais cresceram sobre ruínas de pedra, raízes formam pontes naturais e a névoa esconde pequenas clareiras. As bordas da ilha revelam cachoeiras suspensas e o vazio abaixo. O coração do bioma abriga cristais verde-água e troncos fossilizados. O ambiente deve parecer **vivo, antigo e hostil**, nunca uma floresta genérica plana.

- **Paleta:** verde-musgo, oliva, casca escura, marrom-terra, dourado-amarelado de fungos, turquesa luminescente (apenas pontos focais).
- **Materiais:** madeira retorcida, casca rachada, folhas sobrepostas, pedra úmida, musgo, cogumelos e minerais translúcidos.
- **Silhuetas do mapa:** árvores com copas amplas, raízes expostas em arcos, pilares caídos, pontes rústicas e galhadas fósseis.
- **Áreas planejadas:** Trilha das Raízes (entrada), Brejo de Esporos, Ruínas Suspensas, Veio Esmeraldino (mineração) e Clareira do Coração (arena do chefe).
- **Loop de exploração:** avistar criaturas, aprender o terreno, coletar minerais, caçar, extrair materiais, retornar à forja no Refúgio, melhorar equipamento e desbloquear arena.

## 2. Leviantes — três designs de identidade própria

### Virdrak — Predador das Folhas (caça comum)
- **Silhueta:** quadrúpede esguio, tronco baixo, cauda longa e flexível, membros de ataque fortes, placas semelhantes a folhas pontiagudas.
- **Cabeça:** focinho estreito e bico córneo; olhos âmbar e crista vegetal. Nada de visual humanoide.
- **Textura/material:** folhas com nervuras amplas, madeira flexível e garras escuras.
- **Combate conceitual:** investida lateral, salto em arco, varredura de cauda; deixa rastros de folhas para sinalizar a direção do ataque.
- **Papel:** introduzir esquiva e leitura de telegráficos de movimento.
- **Armadura derivada:** **Traje do Caçador Foliar** — silhueta leve e ágil, peças laminadas nos antebraços, capa curta de folhas, botas com garras e máscara estreita. Não apenas tingir uma armadura genérica de verde.

### Mosskar — Bastião do Brejo (caça intermediária)
- **Silhueta:** quadrúpede de porte maciço, ombros altos, placas rochosas e presas curvas; musgo e pequenos fungos crescem na carapaça.
- **Cabeça:** baixa, pesada, cercada por casca endurecida, com dois grandes dentes curvos.
- **Textura/material:** pedra quebrada, lama seca, musgo denso, fungos âmbar.
- **Combate conceitual:** carga frontal, pisoteio em área e defesa ao recolher a cabeça. Seus pontos expostos aparecem após golpes pesados.
- **Papel:** ensinar posicionamento e abertura de defesa.
- **Armadura derivada:** **Couraça Musgopétrea** — ombreiras assimétricas de pedra/musgo, peitoral robusto de casca e botas com base larga, sem sacrificar a mobilidade necessária ao personagem Roblox.

### Sylvarok — Coração da Floresta (Leviante-chefe)
- **Silhueta:** colosso ereto composto de raízes, casca e madeira antiga; braços assimétricos, enormes galhadas ramificadas e núcleo de cristal verde no tórax.
- **Cabeça:** máscara de madeira, traços não humanos, galhadas de árvore; corpo delimitado por raízes entrelaçadas.
- **Textura/material:** madeira escura, líquens, cristais turquesa e cogumelos discretos.
- **Combate conceitual:** ondas de raízes no chão, ataque vertical com braço pesado e fase de exposição do núcleo; golpes visivelmente anunciados.
- **Arena:** Clareira do Coração, círculos de raiz, pedras erguidas e três saídas amplas para reposicionamento.
- **Papel:** chefe do bioma, focado em cooperação e coordenação de esquivas.
- **Armadura derivada:** **Regalia do Coração Silvestre** — ombros com galhadas reduzidas, peitoral com núcleo luminoso protegido, placas de casca escura e detalhes de raiz. Silhueta majestosa e legível, não uma fantasia de árvore impossível de animar.

## 3. Drops — nove materiais exclusivos

As porcentagens representam **chances de rolagens independentes por vitória**, não parcelas de uma tabela que somam 100%; valores preliminares sujeitos a testes de balanceamento. O jogador pode receber mais de um material por caça.

| Criatura | Material comum | Chance | Material raro | Chance | Material épico | Chance |
| --- | --- | ---: | --- | ---: | --- | ---: |
| Virdrak | Escama Foliar | 75% | Garra de Seiva | 30% | Olho Âmbar | 8% |
| Mosskar | Placa Musgopétrea | 75% | Presa do Brejo | 30% | Coração de Esporos | 8% |
| Sylvarok | Madeira Primordial | 100% | Galhada de Cristal | 45% | Núcleo Silvestre | 12% |

**Diretriz visual de loot:** cada ícone deve ser reconhecível em 64×64 px. Materiais comuns com silhueta simples; raros com um ornamento; épicos com brilho discreto. Evitar ícones muito parecidos.

## 4. Mineração e transformação — seis itens

| Nó mineral | Leitura visual em campo | Produto transformado | Aplicação |
| --- | --- | --- | --- |
| Ferroverde | minério grafite com inclusões verdes | Barra de Ferroverde | componentes estruturais |
| Âmbar Fóssil | nódulo âmbar em casca petrificada | Resina de Âmbar Purificada | reforços e acabamentos |
| Cristal da Seiva | prisma translúcido turquesa | Liga de Seiva Cristalina | equipamentos avançados |

**Forja:** transformação separada da coleta; o jogador encontra o nó na ilha e processa o recurso na infraestrutura da Ordem dos Errantes. Receitas numéricas a serem balanceadas na fase jogável, sem prometer implementação existente.

## 5. Armaduras — três conjuntos de caçador

**Regra geral:** cada conjunto possui capacete, peitoral, braçadeiras, calças e botas (5 peças). São conceitos visuais ainda não modelados; manter juntas e volumes funcionais para rig R15. As propostas abaixo são identidades e não atributos de jogo já implementados.

| Conjunto | Origem | Perfil | Materiais predominantes | Linguagem visual |
| --- | --- | --- | --- | --- |
| Traje do Caçador Foliar | Virdrak | mobilidade | escamas, garras, Ferroverde | camadas leves, diagonais, linhas ágeis |
| Couraça Musgopétrea | Mosskar | resistência | placas, presas, âmbar | massas pesadas, ombros rochosos, casca |
| Regalia do Coração Silvestre | Sylvarok | recompensa do chefe | madeira, galhadas, cristal | verticalidade, raízes, peça central luminosa |

**Acabamentos opcionais futuros:** Natural, Divino, Sombrio e Elemental, todos preservando a mesma silhueta base e sem contar como novos conjuntos. Não iniciar esses acabamentos antes dos três modelos-base.

## 6. Estrutura dos arquivos e referências visuais

O primeiro arquivo da ilha permanece intocado: `catalogos/Ilha_01_Escarpas_Ancestrais.html`.

Para a Floresta, usar caminhos próprios:

```text
catalogos/
  Ilha_01_Escarpas_Ancestrais.html   # EXISTENTE — NÃO ALTERAR
  Ilha_02_Floresta_Ancestral.html   # catalogação visual FUTURA
assets/
  ilha_02_floresta_ancestral/
    cenario/
    criaturas/
      virdrak/
      mosskar/
      sylvarok/
    armaduras/
    drops/
    minerios/
    fundicao/
docs/
  Ilha_02_Floresta_Ancestral_Planejamento.md  # este documento
```

Cada categoria de arte deve ter **imagem geral reunindo tudo** e **imagens individuais**; separar visuais finais, recortes e estudos. Não chamar uma prancha de conceitos de “modelos 3D prontos”. Reaproveitar identidade visual e navegação do HTML da Ilha 01; criar novo arquivo, não sobrescrever os anteriores.

### Pacote visual antes da modelagem

- [ ] 1 imagem panorâmica do bioma, com leitura do relevo, raízes, ruínas e mineração
- [ ] 1 prancha geral contendo os 3 Leviantes, com escala humana e identidade distinta
- [ ] 3 imagens individuais de corpo inteiro dos Leviantes
- [ ] 1 prancha geral dos 3 conjuntos de armadura, corpo inteiro, vistas úteis
- [ ] 3 imagens individuais das armaduras com materiais e detalhes de modelagem
- [ ] 1 prancha geral com os 9 drops, os 3 minérios e os 3 produtos de fundição
- [ ] 15 imagens individuais desses itens (9 + 3 + 3)
- [ ] 1 HTML offline completo e navegável, com imagens incorporadas e receitas

## 7. Ordem de produção recomendada

1. **Fechar primeiro o estilo e as formas** dos três Leviantes (hoje há apenas conceito, sem rig 3D).
2. Gerar armaduras e materiais a partir dessas formas já aprovadas; nunca desenhar uma armadura antes de saber de que criatura saem suas peças.
3. Montar a prancha geral e o catálogo HTML da Ilha 02, mantendo imagens individuais, nomes e receitas juntos.
4. Paralelamente, montar **uma vertical slice jogável da Ilha 01**: uma arena pequena, um inimigo, esquiva, recompensa de caça, um recurso minerável e uma receita de forja.
5. Medir legibilidade, custo de renderização e facilidade de rig no Roblox Studio antes de expandir os modelos e sistemas.

**Orçamento de geometria:** evitar afirmar um “limite oficial de polígonos para Roblox” igual para todos os assets. Definir metas de triângulos por tipo de objeto apenas após teste real com dispositivo-alvo, rigs, texturas e número de instâncias. Preferir detalhe de textura, silhueta e materiais antes de excesso de malha.

---

**Nota de integridade:** projeto autoral inspirado apenas no gênero de jogos de caça. Não reproduzir nomes, designs, animações ou elementos protegidos de Dauntless. Esta ficha é planejamento da Floresta Ancestral e não substitui o catálogo final nem a implementação no Roblox Studio.
