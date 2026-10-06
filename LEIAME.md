# Central Blue Door Imóveis

Página estática única (HTML/CSS/JS, sem dependências nem build). O logo já está embutido no `index.html`.

## Publicação (GitHub Pages)
1. Criar repositório (sugestão: `bluedoor-central`).
2. Enviar `index.html` para a raiz da branch `main`.
3. Settings > Pages > Source: branch `main`, pasta `/ (root)` > Save.
4. Endereço: `https://<usuario>.github.io/<repositorio>/`

## Domínio próprio (opcional)
Para usar um subdomínio (ex.: `central.bluedoorimoveis.com.br`):
1. No DNS, criar um registro CNAME do subdomínio apontando para `<usuario>.github.io`.
2. Em Settings > Pages > Custom domain, informar o subdomínio e ativar "Enforce HTTPS".

## Como editar
No final do `index.html`, na lista `AREAS`, ficam todas as áreas, seções, links e dados.
- `tipo:"dash"`: dashboard; `tipo:"link"`: link comum; `tipo:"soon"`: em breve; `copias`: botões que copiam o dado.
- Para ativar o dashboard de Atendimento: trocar `tipo:"soon"` por `tipo:"dash"` e adicionar `url:"..."`.
