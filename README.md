# RepositorioTemplate

Repositório que deve ser utilizado como template inicial pelos grupos da matéria de Arquitetura e Desenho de Software.

## Introdução

Este repositório traz um template de repo de documentação a ser seguido pelos grupos de arquitetura e desenho de software.

## Tecnologia

A geração do site estático é realizada utilizando o [MkDocs](https://www.mkdocs.org/) com o tema [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

MkDocs é um gerador de sites estáticos rápido e simples, voltado para documentação de projetos. Os arquivos de origem são escritos em Markdown e configurados com um único arquivo de configuração YAML.

### Instalando o MkDocs

Execute os comandos:

```shell
pip install mkdocs
pip install mkdocs-material
```

### Executando localmente

Para iniciar o site localmente, utilize o comando:

```shell
mkdocs serve
```

O site estará disponível em `http://127.0.0.1:8000/`

### Deploy para GitHub Pages

O deploy é automatizado via GitHub Actions. Toda vez que você fizer push para a branch `main`, o site será atualizado automaticamente.

**Site publicado em:** https://unbarqdsw2025-2-turma01.github.io/2025.2-T01-G1_JogoDigital_Entrega_04/

Para fazer deploy manual:

```shell
mkdocs gh-deploy
```
