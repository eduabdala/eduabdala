# Project Status Badges - Standards

Este README documenta o padrão de utilização de **badges de status** para projetos no meu perfil. Elas servem para indicar rapidamente o estado atual do projeto, ajudando colaboradores e visitantes a entenderem a maturidade ou disponibilidade do projeto.

---

## Status do Projeto

Para indicar o **estado atual do projeto**, utilizamos badges genéricas do [Shields.io](https://shields.io/). Abaixo estão os estados possíveis, com cores padrão recomendadas:

| Estado                | Badge Markdown                                                                                   | Cor sugerida     | Descrição                                                                 | Exemplo |
|-----------------------|--------------------------------------------------------------------------------------------------|-----------------|---------------------------------------------------------------------------|---------|
| Pronto                | `![Status do Projeto](https://img.shields.io/badge/status-pronto-brightgreen)`                  | brightgreen     | Projeto concluído e estável.                                             | ![Status do Projeto](https://img.shields.io/badge/status-pronto-brightgreen) |
| Em Desenvolvimento    | `![Status do Projeto](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)`         | yellow          | Projeto ativo, ainda em evolução.                                         | ![Status do Projeto](https://img.shields.io/badge/status-em%20desenvolvimento-yellow) |
| Pausado               | `![Status do Projeto](https://img.shields.io/badge/status-pausado-orange)`                        | orange          | Desenvolvimento temporariamente suspenso.                                 | ![Status do Projeto](https://img.shields.io/badge/status-pausado-orange) |
| Parado                | `![Status do Projeto](https://img.shields.io/badge/status-parado-red)`                            | red             | Projeto interrompido, não receberá atualizações em breve.                 | ![Status do Projeto](https://img.shields.io/badge/status-parado-red) |
| Descontinuado         | `![Status do Projeto](https://img.shields.io/badge/status-descontinuado-lightgrey)`              | lightgrey       | Projeto oficialmente encerrado ou não mantido.                             | ![Status do Projeto](https://img.shields.io/badge/status-descontinuado-lightgrey) |

---

## Outras Badges Úteis

Além do status, é recomendado adicionar algumas badges que indicam informações importantes sobre o projeto:

| Categoria             | Badge Markdown | Descrição | Exemplo |
|-----------------------|----------------|-----------|---------|
| Versão                | `![Version](https://img.shields.io/badge/version-1.0.0-blue)` | Versão atual do projeto. | ![Version](https://img.shields.io/badge/version-1.0.0-blue) |
| Licença               | `![License](https://img.shields.io/badge/license-MIT-green)` | Tipo de licença do projeto. | ![License](https://img.shields.io/badge/license-MIT-green) |
| Build / CI            | `![Build](https://img.shields.io/badge/build-passing-brightgreen)` | Status do build em GitHub Actions ou outra CI. | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| Cobertura de Testes   | `![Coverage](https://img.shields.io/codecov/c/github/usuario/repositorio)` | Percentual de cobertura de testes. | ![Coverage](https://img.shields.io/codecov/c/github/usuario/repositorio) |
| Dependências          | `![Dependencies](https://img.shields.io/librariesio/github/usuario/repositorio)` | Estado das dependências do projeto. | ![Dependencies](https://img.shields.io/librariesio/github/usuario/repositorio) |
| Issues abertas        | `![Issues](https://img.shields.io/github/issues/usuario/repositorio)` | Número de issues abertas no GitHub. | ![Issues](https://img.shields.io/github/issues/usuario/repositorio) |
| Pull Requests         | `![PRs](https://img.shields.io/github/issues-pr/usuario/repositorio)` | Número de PRs abertas. | ![PRs](https://img.shields.io/github/issues-pr/usuario/repositorio) |
| Contribuidores        | `![Contributors](https://img.shields.io/github/contributors/usuario/repositorio)` | Número de contribuidores ativos. | ![Contributors](https://img.shields.io/github/contributors/usuario/repositorio) |
| Linguagens / Stack    | `![Python](https://img.shields.io/badge/python-3.12-blue)` `![Flutter](https://img.shields.io/badge/flutter-3.13-blue)` | Linguagens ou frameworks usados no projeto. | ![Python](https://img.shields.io/badge/python-3.12-blue) ![Flutter](https://img.shields.io/badge/flutter-3.13-blue) |
| Popularidade          | `![Stars](https://img.shields.io/github/stars/usuario/repositorio?style=social)` | Estrelas do projeto no GitHub. | ![Stars](https://img.shields.io/github/stars/usuario/repositorio?style=social) |
| Forks                 | `![Forks](https://img.shields.io/github/forks/usuario/repositorio?style=social)` | Número de forks do projeto. | ![Forks](https://img.shields.io/github/forks/usuario/repositorio?style=social) |

---

## Como usar no README do projeto

As badges devem ser colocadas no **topo do README**, logo abaixo do título, por exemplo:

```markdown
# Nome do Projeto

![Status do Projeto](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Build](https://github.com/usuario/repositorio/actions/workflows/main.yml/badge.svg)
