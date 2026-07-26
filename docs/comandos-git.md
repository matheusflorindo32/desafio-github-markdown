# Principais comandos Git

| Comando | Finalidade |
|---|---|
| `git init` | Inicia um repositório local |
| `git clone URL` | Clona um repositório remoto |
| `git status` | Mostra o estado dos arquivos |
| `git add .` | Prepara as alterações |
| `git commit -m "mensagem"` | Registra uma versão |
| `git branch` | Lista as branches |
| `git checkout -b nome` | Cria e acessa uma branch |
| `git switch -c nome` | Alternativa moderna para criar uma branch |
| `git push origin branch` | Envia commits ao GitHub |
| `git pull` | Atualiza o repositório local |
| `git merge branch` | Integra uma branch |
| `git log --oneline` | Exibe o histórico resumido |

## Fluxo básico

```bash
git clone https://github.com/matheusflorindo32/desafio-github-markdown.git
cd desafio-github-markdown
git checkout -b docs/exemplo
git add .
git commit -m "docs: adiciona exemplo"
git push origin docs/exemplo
```

Depois do `push`, o pull request pode ser aberto no GitHub.
