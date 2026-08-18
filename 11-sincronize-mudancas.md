# 11. Sincronize mudanças

> Registre um repositório remoto e troque o histórico de versão.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)

---

## Comandos desta seção (4)

### 1. `git fetch [nome-remoto]`

```bash
git fetch [nome-remoto]
```

**O que faz:**

Baixa o histórico de um repositório remoto sem alterar o branch local.

**Quando usar / observação:**

Use para consultar as alterações do repositório remoto antes de incorporá-las.

---

### 2. `git merge [nome-remoto]/[branch]`

```bash
git merge [nome-remoto]/[branch]
```

**O que faz:**

Combina as alterações do branch remoto com o branch local atual.

**Quando usar / observação:**

Use para incorporar alterações do repositório remoto ao branch atual.

---

### 3. `git push [alias] [branch]`

```bash
git push [alias] [branch]
```

**O que faz:**

Envia os commits do branch local para o repositório remoto.

**Quando usar / observação:**

Use para publicar suas alterações no GitHub.

---

### 4. `git pull`

```bash
git pull
```

**O que faz:**

Baixa o histórico do repositório remoto e incorpora as alterações ao branch local.

**Quando usar / observação:**

Use para atualizar seu repositório local com as alterações do remoto.

---

## Checklist deste arquivo

- [x] 1. `git fetch [nome-remoto]`
- [x] 2. `git merge [nome-remoto]/[branch]`
- [x] 3. `git push [alias] [branch]`
- [x] 4. `git pull`

---

[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)
