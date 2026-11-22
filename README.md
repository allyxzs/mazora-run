# MAZORA RUN

Jogo arcade 2D em Pixel Art com movimentação de deslize contínuo em grade (estilo *Tomb of the Mask*), 20 fases matematicamente verificadas por BFS, 5 biomas, loja de personagens e áudio procedural via Web Audio API.

## Funcionalidades
- **20 Fases em 5 Biomas:** Ruínas Antigas, Cavernas de Cristais, Templo Esquecido, Fortaleza Sombria e Labirinto Tecnológico.
- **Auditoria BFS Integrada (`MazeAuditorBFS`):** Todas as 20 fases são validadas sobre o grafo real `(x, y, hasKey)`, incluindo rota visual (`H`) e Bot Auto-Play (`B`).
- **Controles:** Setas / `WASD` no PC, gestos de deslizar (Swipe contínuo) no celular e D-Pad opcional nas Configurações.
- **Zero Dependências:** Funciona diretamente no navegador e no GitHub Pages sem build.
