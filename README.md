# City Rivals

Versão 0.2 — jogo de estratégia urbana no navegador.

Jogar: https://jhonpires.github.io/cityrivals/

Este repositório contém o build estático. GitHub Pages publica a branch `main`, pasta raiz. Os arquivos em `assets/` e `.nojekyll` precisam acompanhar `index.html`.

A cidade tem pedestres, veículos, obras animadas, iluminação, avisos e prévia de cobertura. O tema usa azul; grama, árvores e telhados residenciais permanecem verdes.

Prática contra bot funciona localmente. Multiplayer de 2–4 jogadores usa um jogador como host e PeerJS/WebRTC; ainda exige validação em dispositivos e redes reais. Mantenha a aba do host aberta.

Origem do build: código City Rivals, commit `35a36d1ee3994e2d715045084ae206a15f3cdc86`. Verificação: 33 testes aprovados, TypeScript, build e fluxo Chromium/Playwright.
