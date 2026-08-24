# Landing Page - AUNI

Repositório da página inicial oficial do Instituto AUNI.

## Estrutura e Rotas

Este repositório contém a página de captação e cadastro de novos participantes do AUNI (index.html). O formulário aqui contido está integrado diretamente ao banco de dados (Supabase) e aos webhooks (n8n).

## Navegação

O ecossistema do AUNI é unificado pela Plataforma Integra. O fluxo ocorre da seguinte maneira:

1. **Cadastro Novo:** Ao concluir o cadastro em index.html, o usuário é redirecionado para o sistema principal.
2. **Login Existente:** O botão de Login redireciona diretamente para a central de acesso isolada do AUNI: https://plataformaintegra.com.br/auni/login.

Dessa forma, a autenticação, segurança e área do aluno ficam isolados e protegidos na plataforma central, mantendo esta landing page leve e focada apenas na captação.
