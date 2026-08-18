# 02. Configure a ferramenta

> Configure informações de usuário para todos os repositórios locais.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Instale o Git](01-instale-o-git.md) · [Índice](../README.md) · [Crie repositórios ➡](03-crie-repositorios.md)

---

## Comandos desta seção (2)

### 1. `git config --global user.name "[nome]"`

```bash
git config --global user.name "[nome]"
```

**O que faz:**

Define seu nome no Git.
Esse nome é gravado em cada commit, identificando a autoria.

**Quando usar / observação:**

--global vale para todos os repositórios da máquina e pode ser sobrescrito por repositório.

---

### 2. `git config --global user.email "[endereco-de-email]"`

```bash
git config --global user.email "[endereco-de-email]"
```

**O que faz:**

Define seu e-mail no Git.
Esse e-mail é gravado em cada commit, identificando a autoria.

**Quando usar / observação:**

O e-mail é usado para vincular o commit à sua conta do GitHub.

---

## Checklist deste arquivo

- [x] 1. `git config --global user.name "[nome]"`
- [x] 2. `git config --global user.email "[endereco-de-email]"`

---

[⬅ Instale o Git](01-instale-o-git.md) · [Índice](../README.md) · [Crie repositórios ➡](03-crie-repositorios.md)
