# byOS Store Community (Público)

Repositório público da comunidade **byOS** para desenvolvedores autenticados via GitHub publicarem seus aplicativos `.byt` na loja **byStore**.

## Requisitos obrigatórios para publicar um app
Todo envio em `catalog.json` (e na pasta `submissions/` + `icons/`) precisa conter obrigatoriamente:
- `id`: identificador único do app (ex.: `com.exemplo.meuapp`)
- `title`: nome exibido na loja
- `version`: versão do aplicativo (usada pela `byStore` para detectar atualizações disponíveis)
- `icon`: ícone do app em `icons/<id>.png` ou `icons/<id>.svg` (ou URL HTTPS) para exibição imediata na vitrine da loja
- `min_byos_version` (e opcional `max_byos_version`): versão mínima/máxima suportada do **byOS** (ex.: `"2026.11"`)
- `sha256`, `size_bytes`, `download_url` e `publisher_github`
