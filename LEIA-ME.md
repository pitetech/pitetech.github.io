# Site Pitetech

Site estático (um `index.html`, sem build). Fontes via Google Fonts (Space Grotesk, Inter, JetBrains Mono).

## Testar localmente
Abra `index.html` no navegador, ou rode `python -m http.server 8080` nesta pasta e acesse http://localhost:8080.

## Publicar no GitHub Pages (grátis)
1. Na organização `pitetech`, crie o repositório **`pitetech.github.io`** (público).
2. Envie o conteúdo desta pasta (`index.html`, `favicon.*`, `apple-touch-icon.png`) para a raiz.
3. Em *Settings → Pages*, escolha **Deploy from a branch → main / (root)**.
4. O site fica em `https://pitetech.github.io`.

## Domínio próprio (depois de registrar `pitetech.com.br`)
- Em *Settings → Pages → Custom domain*, informe `pitetech.com.br`.
- No registro.br, aponte o DNS conforme as instruções do GitHub (registros `A` para o apex e `CNAME` do `www` para `pitetech.github.io`).
- Depois, complete o `<head>`: `canonical`, `og:url` e `og:image` (1200×630).

## Pendências no conteúdo
- Seção **Stack**: acrescentar as tecnologias reais.
- Seção **Projetos**: trocar o "Em breve" por cards quando houver repositórios públicos.
- **Contato**: adicionar e-mail público do domínio e LinkedIn.
