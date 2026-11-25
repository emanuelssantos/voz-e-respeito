# Voz e Respeito — Seu descanso também importa!

Página que toca uma mensagem em áudio para pacientes internados, com legenda sincronizada no estilo do Spotify (a frase falada fica em destaque), e ao final leva ao formulário de opinião.

Fluxo: o paciente lê o QR code → abre a página → ouve a mensagem com legenda → responde ao formulário.

## Arquivos
- `index.html` — a página (legenda e tempos de cada frase ficam no próprio arquivo, na constante `LINES`)
- `audio.mp3` — a narração (voz Giselli, ElevenLabs)

Para trocar a narração por uma gravação nova, substitua `audio.mp3` e ajuste os tempos (`s` = início, `e` = fim, em segundos) de cada frase em `LINES`.
