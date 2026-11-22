
## Como Publicar no GitHub Pages

1. Extraia os arquivos na raiz do repositório `mazora-run` (`index.html`, `README.md`, `.gitignore`, `LICENSE`).
2. Faça commit e push na branch `main`:

   ```bash
   git add .
   git commit -m "Fix viewport canvas sizing v1.1"
   git push origin main
   ```

3. Acesse [https://allyxzs.github.io/mazora-run/](https://allyxzs.github.io/mazora-run/) (pressione `Ctrl + Shift + R` para limpar o cache).

## Funcionalidades

- **20 Fases em 5 Biomas:** Ruínas Antigas, Cavernas de Cristais, Templo Esquecido, Fortaleza Sombria e Labirinto Tecnológico.
- **Auditoria BFS Integrada (`MazeAuditorBFS`):** Todas as 20 fases são validadas sobre o grafo real `(x, y, hasKey)`, incluindo rota visual (`H`) e Bot Auto-Play (`B`).
- **Controles:** Setas / `WASD` no PC, gestos de deslizar (Swipe contínuo) no celular e D-Pad opcional nas Configurações.
- **Zero Dependências:** Funciona diretamente no navegador e no GitHub Pages sem build.
