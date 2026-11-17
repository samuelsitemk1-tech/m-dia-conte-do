# Mídia de conteúdo · @osamuestrategista

Imagens dos posts e fila de publicação automática no Instagram.

## Estrutura
- `carrosseis/<data>-<tema>/` – slides em JPEG 1080x1350, nomeados `...-01.jpg`, `...-02.jpg`…
- `fila/fila.json` – a fila de posts.

## Status de cada post na fila
- `rascunho` – ainda não aprovado. Nunca é publicado.
- `aprovado` – aprovado pelo Samuel; sai no `data_hora` marcado.
- `publicado` – já foi ao ar (tem `media_id`).
- `erro` / `atrasado` – não publicou; ver o campo `observacao`.

## Horários
Todos os dias, por volta de 12h, 17h e 19h (horário de Brasília).
