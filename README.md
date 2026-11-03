# Platina Advocacia — Página de links para NFC

Página estática, responsiva e sem anúncios. Desenvolvida com HTML, CSS e JavaScript puro, sem serviços externos e sem necessidade de banco de dados.

## Arquivos
- `index.html`: conteúdo e links.
- `styles.css`: identidade visual e responsividade.
- `script.js`: atualização automática do ano no rodapé.
- `assets/logo-platina.png`: logotipo extraído da captura de tela fornecida (substituir quando tiver o arquivo original, pois a resolução da captura é limitada).
- `assets/icons.svg` e `assets/favicon.svg`: ícones vetoriais locais.

## Como testar
Abra `index.html` no navegador. Para desenvolvimento, pode utilizar a extensão Live Server no VS Code.

## Publicar gratuitamente no GitHub Pages
1. Crie um repositório público (por exemplo, `platina-contatos`) na conta escolhida.
2. Envie **o conteúdo desta pasta** para a raiz do repositório, incluindo `index.html`.
3. No GitHub, acesse **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**; use a branch `main` e a pasta `/(root)`; salve.
5. Quando publicado, o endereço normalmente será `https://USUARIO.github.io/platina-contatos/` (substitua USUARIO pelo nome real da conta e o nome do repositório, se diferente).
6. Abra o endereço em um celular e teste cada link antes de gravá-lo na tag NFC.

## Configurar a tag NFC
Grave na tag um registro do tipo **URL/URI** com o endereço HTTPS publicado no GitHub Pages. Teste a leitura nos aparelhos usados pelos clientes. A tag guarda o **link**, e não os arquivos do site; assim, é possível atualizar contatos e aparência sem regravar a tag, desde que o endereço da página permaneça o mesmo.

## Personalização
- Altere os links e textos em `index.html`.
- Altere as cores nas variáveis `:root` do arquivo `styles.css`.
- Substitua `assets/logo-platina.png` pelo logo oficial em alta resolução (preferencialmente PNG transparente).
- Os números foram identificados como **Atendimento 1** e **Atendimento 2** porque não foi informado qual pertence a cada advogado.

## Observações
O GitHub Pages é gratuito para repositórios públicos compatíveis com os termos e limites do serviço. Não inclui caixa de e-mail profissional nem domínio personalizado; o endereço padrão é `github.io`. Um site estático não coleta dados dos visitantes por conta própria, mas links externos seguem as políticas dos respectivos serviços. Evite publicar dados pessoais sem autorização do escritório.
