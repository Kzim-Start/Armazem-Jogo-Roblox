# Lobby — Refúgio dos Errantes

> **Projeto:** Fragmentos do Infinito (Roblox)  
> **Fase:** documentação e referências; não equivale a modelos 3D ou mecânicas implementadas.  
> **Fonte:** atlas histórico de biomas, mobs, drops e armaduras fornecido no projeto.

## Visão geral

Área segura e centro de preparação dos jogadores. **Não há caças, Leviantes, drops ou minérios de combate no lobby.** Os dados de Gravalhor, Torogar e Brontar que apareciam marcados com `refugio` no atlas antigo foram realocados para a Ilha 01 (Escarpas Ancestrais), conforme a definição atual do projeto.

Cidade-base medieval de tecnologia recuperada; ponto inicial e centro de preparação das caçadas.

**Solo e relevo:** Base de terra batida e pedras irregulares; caminhos mais pisados perto de bancas e docas. Grama só nas bordas, vegetação controlada e pequenos desníveis.

**Ponto de atenção:** Marco principal: aeronave/dirigível medieval atracado ao lobby, com plataforma “Começar Caçada”, quadro de missões, forja e passarelas.

## Direção de arte e assets

### Natureza e relevo

- **Grama rasteira:** Nas bordas de caminhos e canteiros
- **Árvores de copa média:** Poucas, para não esconder bancas e NPCs
- **Arbustos de cerca:** Variedade de altura e tonalidade
- **Tufos secos:** Entre pedras e tábuas
- **Musgo e trepadeiras:** Junto às muralhas e pilares

### Construções e decoração

- **Aeronave / balão de caçadas:** Hub principal suspenso ou atracado
- **Plataforma de decolagem:** Portal físico para iniciar uma caçada
- **Forja e bigorna:** Equipamentos dos Leviantes
- **Quadro de missões:** Seleção de caçadas e contratos
- **Barris, caixas e cordas:** Preencher docas e armazéns
- **Postes, lampiões e bandeiras:** Dar identidade à Ordem dos Errantes
- **Passarelas e corrimões:** Conectar áreas do lobby

### Texturas e recursos

- **Terra batida:** Terreno / trilhas
- **Pedra de calçamento:** Textura / caminhos
- **Madeira envelhecida:** Construção / docas
- **Ferro escurecido:** Construção / ferragens
- **Tecido grosso:** Velas e balão da aeronave
- **Sucata tecnológica:** Coletável / reparos

## Checklist de implementação no Blender e Roblox Studio

- [ ] Aprovar direção de arte e escala do mapa.
- [ ] Modelar módulos ambientais reutilizáveis, materiais e pontos de interesse.
- [ ] Preparar área de spawn, painel de missões, forja e plataforma de caçada.
- [ ] Validar navegação e funcionamento como zona segura, sem inimigos.
- [ ] Testar orçamento de triângulos, colisões, UVs, materiais, LOD e desempenho nos dispositivos-alvo.
- [ ] Verificar o conteúdo em Roblox Studio antes de declarar qualquer elemento como pronto.

## Navegação

- [Índice dos biomas](INDEX_BIOMAS.md)

**Observação de consistência:** o Refúgio dos Errantes continua reservado ao lobby. Embora o atlas antigo agrupasse Gravalhor, Torogar e Brontar sob o identificador interno `refugio`, esses Leviantes pertencem às **Escarpas Ancestrais** no plano atual. Sempre distinguir referências conceituais de conteúdo já implementado.
