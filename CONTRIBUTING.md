# Contribuindo com o landing-page

Ao participar, você concorda em seguir o [Código de Conduta](CODE_OF_CONDUCT.md). Para reportar um problema de segurança, **não** abra uma issue — siga o [SECURITY.md](SECURITY.md).

## Idioma

Documentação, issues, Pull Requests e mensagens ao usuário em português do Brasil.

## Configurando o ambiente

1. Clone o repositório:
   ```bash
   git clone https://github.com/EcoCiente-Instituto-J-F/landing-page.git\n   cd landing-page\n   ```\n2. Não há dependências nem build: o site é HTML e CSS puros (`index.html` e `style.css`).\n3. Abra o `index.html` no navegador, ou sirva a pasta localmente (por exemplo, `python -m http.server 8000`) para testar.

## Testando sua mudança

Não há testes automatizados nem CI. Antes de abrir a PR, confira manualmente no navegador:

- o layout em desktop e em celular (largura de 360 px);
- a navegação da navbar e os links âncora;
- as imagens carregando (caminhos relativos em `assets/`);
- foco visível, textos alternativos (`alt`) e contraste.

Mudanças visuais devem vir com uma captura de tela na PR.

## Regras do projeto

- Nenhum segredo (chaves, tokens, senhas) no repositório.
- Nenhum dado pessoal real em testes, fixtures ou exemplos.
- Nenhuma dependência nova sem discussão prévia.
- Somente HTML e CSS: sem frameworks nem dependências novas sem discussão.
- Imagens e ícones ficam em `assets/`; otimize o tamanho antes de adicionar.
- Todo texto de imagem relevante tem `alt`; mantenha a navegação por teclado funcionando.
- Preencha o `.github/pull_request_template.md` ao abrir a PR.

## Pull requests

1. Crie uma branch a partir da `main` (ex.: `feat/nome-da-mudanca`).
2. Faça commits focados com prefixos `feat:`, `fix:`, `chore:`, `docs:`, `test:` ou `refactor:`.
3. Abra a PR para a `main`. Descreva o que mudou e por quê.
4. O CI precisa passar (quando houver) e um mantenedor revisa antes do merge.

## Reportando bugs e propondo funcionalidades

Abra uma issue com o comportamento esperado, o observado, os passos para reproduzir e a versão. Use dados fictícios. Para vulnerabilidades, siga o [SECURITY.md](SECURITY.md).
