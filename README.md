# MAZORA RUN

Jogo arcade 2D em Pixel Art com movimentação de deslize contínuo em grade (estilo *Tomb of the Mask*), 20 fases matematicamente verificadas por BFS, 5 biomas, loja de personagens e áudio procedural via Web Audio API.

## Funcionalidades
- **20 Fases em 5 Biomas:** Ruínas Antigas, Cavernas de Cristais, Templo Esquecido, Fortaleza Sombria e Labirinto Tecnológico.
- **Auditoria BFS Integrada (`MazeAuditorBFS`):** Todas as 20 fases são validadas sobre o grafo real `(x, y, hasKey)`, incluindo rota visual (`H`) e Bot Auto-Play (`B`).
- **Controles:** Setas / `WASD` no PC, gestos de deslizar (Swipe contínuo) no celular e D-Pad opcional nas Configurações.
- **Zero Dependências:** Funciona diretamente no navegador e no GitHub Pages sem build.

## Como Publicar no GitHub Pages
1. Crie um repositório no GitHub (ex.: `mazora-run`).
2. Envie os arquivos deste pacote (`index.html`, `README.md`, `.gitignore`, `LICENSE`) para a branch `main`:
   ```bash
   git init
   git add .
   git commit -m "Release MAZORA RUN v1.0"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/mazora-run.git
   git push -u origin main
   ```
3. No GitHub, acesse **Settings → Pages**, selecione a branch `main` e a pasta `/ (root)`, e clique em **Save**.
4. Em poucos segundos seu jogo estará online em `https://SEU_USUARIO.github.io/mazora-run/`.
