# uma-animacao-do-buck-por-favor

Skill do Claude Code que faz uma animação original a partir de referências de estilo e de uma ideia: cada quadro é desenhado em JavaScript num canvas, renderizado no Chrome instalado e codificado com ffmpeg, com som sintetizado em Node.

## Origem
Adaptação da skill "Motion Studio by Buck", publicada por @buck.the.aikami. O método e o texto principal são dele. As alterações desta versão:
- responde em pt-BR;
- `scripts/frozen-time.sh` mede os trechos parados do vídeo;
- `scripts/loudness.sh` mede o volume final (LUFS, pico e nível por segundo).

## Instalar
Copie a pasta para `~/.claude/skills/uma-animacao-do-buck-por-favor/` e peça ao Claude Code uma animação a partir de referências.

Precisa de Node 18+, Google Chrome (ou Edge) e ffmpeg.
