# 07. Suprima o monitoramento

> Ignore arquivos e diretórios temporários.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)

---

## Itens desta seção (2)

### 1. Arquivo `.gitignore`

```gitignore
*.log
build/
temp-*
```

**O que este arquivo faz:**

Ignora arquivos e diretórios que correspondem aos padrões especificados.

**Quando usar / observação:**

Use para evitar o versionamento acidental de arquivos temporários ou desnecessários.

---

### 2. `git ls-files --others --ignored --exclude-standard`

```bash
git ls-files --others --ignored --exclude-standard
```

**O que faz:**

Lista os arquivos não monitorados que estão sendo ignorados pelo Git.

**Quando usar / observação:**

Use para verificar quais arquivos estão sendo ignorados pelo .gitignore.

---

## Checklist deste arquivo

- [x] 1. Arquivo `.gitignore`
- [x] 2. `git ls-files --others --ignored --exclude-standard`

---

[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)
