# 09. Revise o histórico

> Navegue e inspecione a evolução dos arquivos do projeto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)

---

## Comandos desta seção (4)

### 1. `git log`

```bash
git log
```

**O que faz:**

Lista o histórico de versões do branch atual.

**Quando usar / observação:**

Use para consultar os commits já realizados.

---

### 2. `git log --follow [arquivo]`

```bash
git log --follow [arquivo]
```

**O que faz:**

Lista o histórico de versões de um arquivo, incluindo mudanças de nome.

**Quando usar / observação:**

Use para acompanhar a evolução de um arquivo específico.

---

### 3. `git diff [primeiro-branch]...[segundo-branch]`

```bash
git diff [primeiro-branch]...[segundo-branch]
```

**O que faz:**

Mostra as diferenças de conteúdo entre dois branches.

**Quando usar / observação:**

Use para comparar as alterações entre branches.

---

### 4. `git show [commit]`

```bash
git show [commit]
```

**O que faz:**

Mostra as alterações de metadados e conteúdo do commit especificado.

**Quando usar / observação:**

Use para verificar o que foi alterado em um commit específico.

---

## Checklist deste arquivo

- [x] 1. `git log`
- [x] 2. `git log --follow [arquivo]`
- [x] 3. `git diff [primeiro-branch]...[segundo-branch]`
- [x] 4. `git show [commit]`

---

[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)
