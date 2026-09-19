# Introdução e Boas Práticas a Git e GitHub

Material didático interativo em formato de slides web (HTML, CSS e JavaScript) desenvolvido para guiar o minicurso prático de Git e GitHub.

## Equipe

- Icaro Vinicius
- Luigi Eliabe
- Vinicius Macedo

## Visão Geral do Projeto

Diferente de uma apresentação de slides tradicional estática, este projeto atua simultaneamente como o material de apoio visual da aula e como o próprio repositório hands-on onde os participantes executam o fluxo de trabalho colaborativo em um cenário simulado de empresa.

Os participantes aprendem a:
- Versionar um projeto local com boas práticas e segurança.
- Configurar identidade de autor (`git config`).
- Compreender a arquitetura de branches e commits através da metáfora da planta.
- Rastrear estados de arquivos (`Untracked`, `Modified`, `Staged`) com `git status` e `git log`.
- Inspecionar mudanças (`git diff`), isolar arquivos (`.gitignore`) e criar commits semânticos.
- Resolver um bug real no código (Slide 12), removendo o problema e comitando a correção.
- Autenticar o terminal com Personal Access Token (PAT) para realizar `git push`.
- Integrar a solução via Pull Request no GitHub.

## Estrutura do Conteúdo

1. Apresentação da Equipe
2. Objetivos do Minicurso
3. Conteúdo Programático
4. Fundamentos Git vs GitHub e Criação de Conta
5. Storytelling: Cenário de Desenvolvimento e Alerta de Bug
6. Fork do Repositório e Clone Local
7. Identidade e Configuração (`git config`)
8. Ramificação: A Metáfora da Planta (Tronco, Ramos e Folhas)
9. Inspeção e Radar do Projeto (`git status`)
10. Histórico e Linha do Tempo (`git log`)
11. Mão na Massa: Ciclo de Correção (`.gitignore`, `git diff`, `git add`, `git commit`)
12. O Bug do Projeto (Slide a ser corrigido e removido pelos alunos)
13. Autenticação via Token de Acesso (PAT) e `git push`
14. Entrega: Abertura e Boas Práticas de Pull Request
15. Encerramento e Sessão de Dúvidas

## Como Executar Localmente

O projeto não requer dependências pesadas, servidores complexos ou ferramentas de build.

1. Clone o repositório em sua máquina:
```bash
git clone https://github.com/ViniciusMBotelho/minicurso-git-github.git
cd minicurso-git-github
```

2. Abra o arquivo `index.html` diretamente no seu navegador preferido ou utilize uma extensão de servidor local (ex: Live Server do VS Code).

## Controles de Navegação dos Slides

- Avancar slide: Seta Direita (`->`), Barra de Espaco ou `PageDown`
- Voltar slide: Seta Esquerda (`<-`) ou `PageUp`
