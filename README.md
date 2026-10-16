# Canal OTA da Boltkeep v2

Branch de distribuição de patches de conteúdo (PCK) da v2 — **não é código**.
Publicado por `tools/ota/publish.sh` do repo `boltkeep` (branch do overhaul v2).

- `manifest.json`: versão de conteúdo, URL e SHA-256 do PCK, `min_apk_code`.
- `content.pck`: conteúdo do jogo (scripts + arte + áudio).

O app (`com.monzato.boltkeep.v2`) lê `manifest.json` deste branch pelo raw do GitHub.
