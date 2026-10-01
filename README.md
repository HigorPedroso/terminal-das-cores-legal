# Páginas legais (GitHub Pages)

Política de Privacidade, Termos de Uso e página de suporte do Terminal das Cores.
O repositório do jogo é privado; esta pasta é publicada sozinha no repositório
público `HigorPedroso/terminal-das-cores-legal`, servido pelo GitHub Pages:

- https://higorpedroso.github.io/terminal-das-cores-legal/ (suporte)
- https://higorpedroso.github.io/terminal-das-cores-legal/privacidade/
- https://higorpedroso.github.io/terminal-das-cores-legal/termos/

Os links também ficam em `app.config.ts` (`extra.privacyUrl` / `extra.termsUrl`)
e aparecem em Configurações no app.

## Atualizar

1. Edite os arquivos aqui e atualize a data/versão no topo da página alterada.
2. Faça o commit no repositório do jogo.
3. Publique só esta pasta:

```bash
git subtree push --prefix legal legal main
```

(o remoto `legal` aponta para `https://github.com/HigorPedroso/terminal-das-cores-legal.git`).

Ao adicionar um SDK que coleta dados (analytics, outra rede de anúncios…),
atualize a seção 2 e a tabela de parceiros da política **e** o App Privacy na
App Store Connect / Data safety no Google Play.
