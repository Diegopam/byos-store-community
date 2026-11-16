# byOS Store Community (Público)

Repositório público da comunidade **byOS** para desenvolvedores autenticados via GitHub publicarem seus aplicativos `.byt` na loja **byStore**.

## Como funciona a detecção de versão e compatibilidade
Cada entrada em `catalog.json` informa:
- `version`: versão semântica do aplicativo (ex.: `1.0.0`). Quando `version` no catálogo for maior que a versão instalada no byOS, a **byStore** exibe o botão **Atualizar**.
- `min_byos_version` / `max_byos_version`: faixa de versões do **byOS** suportadas pelo pacote (ex.: `"2026.11"`).
- `sha256` e `size_bytes`: verificação de integridade antes da instalação/atualização.
- `publisher_github`: usuário GitHub autenticado que publicou o app.
