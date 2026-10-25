# Política de Segurança

A landing page do EcoCiente é um site estático (HTML e CSS) sem formulários, scripts próprios, autenticação ou coleta de dados pessoais; carrega apenas fontes do Google Fonts.

## Versões suportadas

| Versão | Suporte |
| --- | --- |
| `main` (mais recente) | Sim |
| Demais branches | Não |

## Reportando uma vulnerabilidade

**Não abra issue, Pull Request ou discussão pública** para relatar vulnerabilidades.

Use o relato privado do GitHub: <https://github.com/EcoCiente-Instituto-J-F/landing-page/security/advisories/new> (Security → Advisories → Report a vulnerability).

> Mantenedores: ative *Private vulnerability reporting* em Settings → Code security.

Inclua no relato:

- o impacto da falha;
- os passos para reproduzir, usando **dados fictícios**;
- o commit testado e a configuração;
- se possível, uma ideia de correção.

Depois do relato: confirmaremos o recebimento, corrigiremos de forma privada e publicaremos um advisory com crédito a quem reportou, se desejado. Pedimos um prazo razoável para a correção antes de qualquer divulgação pública.

## Escopo

**Dentro do escopo**

- Injeção de conteúdo ou de scripts no site publicado
- Links ou recursos externos maliciosos ou comprometidos
- Segredos ou dados pessoais commitados no repositório

**Fora do escopo**

- Bugs visuais ou de acessibilidade sem impacto de segurança
- Falhas em serviços de terceiros (Google Fonts, hospedagem, GitHub)
- Negação de serviço na hospedagem

## Como o sistema protege os dados

O site não coleta nem armazena dados: não há formulários, cookies próprios, scripts ou back-end neste repositório.

## Checklist de deploy

- Publicar somente por HTTPS.
- Revisar qualquer link externo ou recurso de terceiros antes de adicioná-lo.
- Configurar cabeçalhos de segurança (por exemplo, `Content-Security-Policy`) na hospedagem.
