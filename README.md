# 🍰 WMK Fábrica de Doces

Jogo infantil de confeitaria com esteira animada e quatro estações: **forma, massa, cobertura e decoração**.

Inspirado no gênero de jogos de montagem de pedidos em esteira, especialmente no conceito de *Comfy Cakes*, de *Purble Place*. É um jogo original, com gráficos, código e identidade visual próprios, sem reutilização de conteúdo protegido de terceiros.

## Como jogar

1. Abra `index.html` no Chrome, Edge ou Firefox.
2. Escolha a dificuldade e inicie a partida.
3. Observe o **pedido do cliente** no painel direito.
4. Selecione a **forma**, clique em **Próxima estação**.
5. Selecione a **massa**, depois a **cobertura** e a **decoração**.
6. Clique **Entregar pedido**. Cada pedido correto vale pontos; erros consomem vidas.

## Recursos

- Gráficos desenhados em **Canvas e CSS**, sem imagens externas.
- Esteira de produção, bolo ilustrado, ingredientes e interface responsiva.
- Sons sintetizados pelo navegador (podem ser desligados).
- Dificuldades fácil, normal e desafio.
- Pedidos gerados por combinações matemáticas.
- Placar, cronômetro, vidas e recorde salvo em `localStorage`.
- Dados de formato, massa, cobertura, enfeite e dificuldade em `data/game.json`.
- Não precisa de Python, IA, API ou instalação.
- Publicável diretamente no GitHub Pages.

## Personalizar os dados

Edite `data/game.json` para ajustar opções e níveis. No **GitHub Pages**, o jogo carrega automaticamente esse JSON. O arquivo `data/game.js` é uma cópia de reserva em JavaScript para permitir abrir o jogo pelo `file://`, sem servidor. **Se quiser testar as alterações de JSON abrindo `index.html` diretamente, atualize também `game.js`**. No site publicado, o JSON tem prioridade.

## Créditos

**Walney Moreira Klein — walneyk@hotmail.com**

© 2026 Walney Moreira Klein. Licença MIT (ver `LICENSE`).
