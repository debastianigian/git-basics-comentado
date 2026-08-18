# 04. Faça mudanças

> Revise edições e crie uma transação de commit.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)

---

## Comandos desta seção (6)

### 1. `git status`

```bash
git status
```

**O que faz:**

Lista os arquivos novos ou modificados que podem ser commitados.

**Quando usar / observação:**

Use para verificar o estado atual dos arquivos antes de fazer alterações ou commits.

---

### 2. `git diff`

```bash
git diff
```

**O que faz:**

Mostra as diferenças nos arquivos que ainda não foram preparados.

**Quando usar / observação:**

Use para revisar as alterações antes de usar git add.

---

### 3. `git add [arquivo]`

```bash
git add [arquivo]
```

**O que faz:**

Coloca um arquivo na área de preparação para ser versionado.

**Quando usar / observação:**

Use para preparar as alterações que entrarão no próximo commit.

---

### 4. `git diff --staged`

```bash
git diff --staged
```

**O que faz:**

Mostra as diferenças entre os arquivos preparados e suas últimas versões.

**Quando usar / observação:**

Use para conferir o que será incluído no próximo commit.

---

### 5. `git reset [arquivo]`

```bash
git reset [arquivo]
```

**O que faz:**

Retira o arquivo da área de preparação, mas preserva seu conteúdo.

**Quando usar / observação:**

Use quando quiser tirar um arquivo do staging sem perder suas alterações.

---

### 6. `git commit -m "[mensagem descritiva]"`

```bash
git commit -m "[mensagem descritiva]"
```

**O que faz:**

Grava permanentemente um snapshot das alterações no histórico de versões.

**Quando usar / observação:**

Use depois de preparar os arquivos com git add.

---

## Checklist deste arquivo

- [x] 1. `git status`
- [x] 2. `git diff`
- [x] 3. `git add [arquivo]`
- [x] 4. `git diff --staged`
- [x] 5. `git reset [arquivo]`
- [x] 6. `git commit -m "[mensagem descritiva]"`

---

[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)
