# Organização do GitHub — Grupo ERA&S

## Objetivo

Manter o GitHub simples de entender, fácil de manter e preparado para o crescimento da equipe.

## Padrão de nomes

Quando os projetos forem separados em repositórios próprios, usar nomes curtos, minúsculos e com hífen.

Exemplos:

- `site-grupo-eras`
- `site-leppurk`
- `site-zureta`
- `app-barbearia-real`

Evitar nomes como `projeto-final`, `teste2`, `site-novo` ou nomes de integrantes no nome definitivo do projeto.

## Situação atual

O repositório `profile` ainda funciona como um contêiner legado e contém vários projetos em pastas diferentes.

Essa estrutura será mantida temporariamente para evitar quebrar deploys ou perder contexto enquanto a equipe ainda está estudando Git e GitHub.

### Regra temporária

- Não iniciar novos projetos dentro de `profile`.
- Manter os projetos atuais funcionando onde estão.
- Documentar as pastas existentes com README.
- Não mover ou renomear projetos ligados a deploy sem antes conferir a configuração de hospedagem.

## O que foi organizado agora

- Perfil público da organização no local correto: `.github/profile/README.md`.
- Repositório `.github` como central de padrões.
- Repositório `profile` documentado como estrutura temporária.
- Modelo de README e orientações básicas compartilhadas.
- Projetos atuais documentados sem mudar caminhos de deploy.

## O que faremos depois do estudo de Git/GitHub

1. Separar cada projeto importante em um repositório próprio.
2. Conferir e ajustar os deploys após cada migração.
3. Definir padrão de branches.
4. Trabalhar mudanças por Pull Request.
5. Proteger a branch `main`.
6. Revisar e adotar templates de Pull Request e Issues.
7. Adotar um padrão simples de mensagens de commit.
8. Configurar responsáveis e revisão de código quando fizer sentido.
9. Arquivar repositórios de demonstração ou testes que não forem mais necessários.

## Princípio

A organização deve ajudar a equipe a entender o projeto. Se uma regra cria burocracia sem ajudar os três integrantes, ela não deve ser adicionada ainda.
