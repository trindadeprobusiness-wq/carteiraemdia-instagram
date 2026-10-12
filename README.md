# Carteira em Dia · Instagram

Artes, Reels e calendário que o publicador do n8n usa para postar no Instagram @carteiraemdia.com.br.

- `carteira-em-dia.json`: calendário com 90 peças (12/10 a 10/11/2026), 3 por dia
  - 10h: story
  - 12h e 18h: feed (carrossel, estático ou Reels, alternando)
- `Dia-XX_AAAA-MM-DD/MANHA` e `TARDE`: as mídias de cada dia (JPEG e MP4)

O n8n lê este repositório pelo jsDelivr. Para aprovar, trocar ou adiar uma peça, edite o
`carteira-em-dia.json` (campo `status`, `data` ou `legenda`). Só sai o que estiver com
`status: pronto_para_postar`.

Conteúdo educativo. Não é recomendação de investimento.
