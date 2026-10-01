# Automotive Video Engine — assets

Pacotes do acervo visual (peças, personagens, biblioteca visual, vozes e papel)
baixados pelo app desktop do Automotive Video Engine na primeira execução.

Os arquivos ficam nos **Releases** deste repositório, não no git:

- `ave-assets.tar.gz` — o pacote (gerado por `npm run pack:assets` em `desktop-app/`)
- `ave-assets.tar.gz.sha256` — conferido pelo app depois do download
- `ave-assets.tar.gz.json` — nome original, tamanho e pastas incluídas

O app baixa sempre o release mais recente:
`https://github.com/yMarceloMaia/assets/releases/latest/download/ave-assets.tar.gz`

Para publicar uma versão nova: gere o pacote e crie um release com os três
arquivos usando esses mesmos nomes.
