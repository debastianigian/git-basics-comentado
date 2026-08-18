# 06. Refatore nomes de arquivos

> Mude e remova os arquivos versionados.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)

---

## Comandos desta seção (3)

### 1. `git rm [arquivo]`

```bash
git rm [arquivo]
```

**O que faz:**

Remove o arquivo do diretório de trabalho e prepara sua remoção para o commit.

**Quando usar / observação:**

Use quando quiser remover um arquivo que está sendo versionado.

---

### 2. `git rm --cached [arquivo]`

```bash
git rm --cached [arquivo]
```

**O que faz:**

Remove o arquivo do controle de versão, mas preserva o arquivo localmente.

**Quando usar / observação:**

Use quando quiser parar de versionar um arquivo sem apagá-lo do computador.

---

### 3. `git mv [arquivo-original] [arquivo-renomeado]`

```bash
git mv [arquivo-original] [arquivo-renomeado]
```

**O que faz:**

Renomeia ou move o arquivo e prepara a alteração para o commit.

**Quando usar / observação:**

Use quando quiser renomear ou mover um arquivo versionado.

---

## Checklist deste arquivo

- [x] 1. `git rm [arquivo]`
- [x] 2. `git rm --cached [arquivo]`
- [x] 3. `git mv [arquivo-original] [arquivo-renomeado]`

---

[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)
