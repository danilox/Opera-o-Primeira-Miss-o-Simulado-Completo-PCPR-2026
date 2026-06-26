# Simulado PC PR 2026 — Layout responsivo com áudio embutido V2

Esta versão corrige o problema de áudio não atualizado.

## O que mudou

- Os áudios foram embutidos diretamente dentro do `index.html`.
- Não depende mais da pasta `audio/` para tocar as frases.
- Não usa mais o fallback antigo de fala sintetizada.
- Acerto toca frase de acerto.
- Erro toca frase de erro.
- Os botões de teste usam a versão nova embutida.

## Como subir mantendo o mesmo link

Substitua o arquivo `index.html` atual do repositório por este novo arquivo.
Mantenha o repositório, a branch `main` e o GitHub Pages como estão.

Depois do commit, aguarde o Actions ficar verde e abra o site com Ctrl + F5 ou em janela anônima.

## Estrutura mínima

```
index.html
README.md
.nojekyll
```

A pasta `audio/` não é obrigatória nesta versão, pois os sons estão embutidos.
