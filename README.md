# Meu Dicionário Pessoal

Aplicativo web responsivo em HTML, CSS e JavaScript. O arquivo index.html funciona diretamente no navegador e dispensa instalação e compilação.

## Publicar no GitHub Pages

1. Crie um repositório público separado, por exemplo, meu-dicionario-web. Preserve a visibilidade do seu repositório privado atual.
2. Envie os arquivos deste pacote para a raiz da branch main. O arquivo index.html deve ficar na raiz.
3. Abra Settings → Pages. Em Source, selecione Deploy from a branch, escolha main e /(root), e clique em Save.
4. Quando o GitHub informar o endereço na tela de Pages, abra esse endereço no celular.

Documentação: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Publicar no Netlify Drop

Extraia o ZIP e arraste a pasta que contém index.html para https://app.netlify.com/drop. Use o endereço informado pelo Netlify para abrir o dicionário no celular.

## Levar as fichas para o celular

No dicionário que já contém suas fichas, clique em Exportar backup. Transfira o JSON para o celular e abra o endereço publicado. Selecione Importar backup e escolha o JSON. A importação acrescenta fichas novas e preserva as fichas que já têm o mesmo termo.

O endereço publicado distribui o aplicativo e as fichas de exemplo. As fichas que você cria ficam no armazenamento local do navegador, por endereço. Para sincronização automática entre dispositivos, será necessário adicionar autenticação e um banco online. Guarde os JSONs pessoais fora do repositório público.
