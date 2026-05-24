# Aprovação de Postagens — Instagram da Mel

Página para a Mel revisar e aprovar as postagens planejadas para o Instagram.
Abra o arquivo **`index.html`** no navegador.

## O que tem na página

- **Revisar postagens** — as 20 postagens na ordem de publicação (carrossel, card único, carrossel, card único…). Em cada uma a Mel marca o status (Aprovado / Ajustes / Pendente) e escreve observações.
- **Prévia do feed** — simulação de como o feed do Instagram vai ficar.
- **Exportar respostas** — gera um arquivo `.txt` com todas as decisões da Mel, para ela enviar de volta.

As respostas ficam salvas automaticamente no navegador de quem está usando.

## Como publicar no GitHub Pages (passo a passo)

1. Acesse <https://github.com> e faça login (crie uma conta gratuita se não tiver).
2. Clique em **New** para criar um repositório novo. Dê um nome (ex.: `feed-mel`) e marque **Public**. Clique em **Create repository**.
3. Na página do repositório vazio, clique em **uploading an existing file**.
4. Arraste para a janela **estes itens**: o `index.html`, o `.nojekyll`, o `README.md` e a pasta `fotos` (com as 108 imagens dentro). As pastas numeradas `01` a `11` **não precisam ir** — pode ignorá-las ou apagá-las.
5. Clique em **Commit changes**.
6. No repositório, vá em **Settings → Pages**.
7. Em **Branch**, escolha `main` e a pasta `/ (root)`. Clique em **Save**.
8. Aguarde 1–2 minutos. O GitHub vai mostrar o link público, algo como:
   `https://SEU-USUARIO.github.io/feed-mel/`
9. Envie esse link para a Mel. Ela abre no celular ou no computador, revisa tudo e clica em **Exportar respostas**.

## Quer gerar um .zip da pasta?

No Mac: clique com o botão direito na pasta `postagens` → **Comprimir "postagens"**.
No Windows: clique com o botão direito → **Enviar para → Pasta compactada**.
Isso cria o `.zip` com tudo dentro, pronto para guardar ou compartilhar.

## Observações

- Todas as 108 imagens estão na pasta única `fotos`. Os dois HTMLs já apontam para ela.
- O arquivo `.nojekyll` garante que o GitHub Pages sirva todas as imagens corretamente. Não apague.
- O arquivo `aprovacao-feed-mel.html` é uma cópia idêntica do `index.html` (caso queira manter uma versão local). Para o GitHub Pages, o que vale é o `index.html`.
- As pastas `01` a `11` ainda têm as imagens originais (foram copiadas, não movidas). Pode apagá-las quando quiser — não fazem parte do site.
