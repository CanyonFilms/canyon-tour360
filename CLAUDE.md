# Site – Canyon Films Tour 360°

- Site estático: `index.html` + `assets/`. Sem build.
- Publicação: Cloudflare Pages (projeto `canyon-tour360`), automática a cada push na branch `main`.
  Endereço: https://canyon-tour360.pages.dev
- Para atualizar: editar `index.html`, fazer commit e push em `main`. O deploy leva cerca de 1 minuto.
- O tour de demonstração está incorporado por `<iframe>` no bloco `#demo` (link do PanoCool).
- Estilos responsivos e animações ficam no `<style>` do `<head>` (classes `.btn`, `.card`, `.hero-*`, `.h2`).
- Textos em português do Brasil. Paleta: #07315D, #041D38, #020D17, ciano #2AD3FF, verde-água #1AB499.
- Tours de clientes: uma pasta por cliente com `index.html`, servida em `/nome-da-pasta`. Partir de `modelo-cliente/index.html` (sem selo da Canyon: a página do cliente fica limpa) e trocar NOME-DO-CLIENTE e COLE-O-ID-AQUI (sem imagem de prévia e sem favicon da Canyon, por escolha do Luan). `rua-do-mathe/` é o tour de demonstração da Canyon e tem o selo no canto superior esquerdo. Essas páginas levam `noindex`.
