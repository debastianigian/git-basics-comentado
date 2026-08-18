# 10. Desfaça commits

> Apague enganos e crie um histórico substituto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)

---

## Comandos desta seção (2)

### 1. `git reset [commit]`

```bash
git reset [commit]
```

**O que faz:**

Desfaz os commits posteriores ao commit especificado, preservando as alterações locais.

**Quando usar / observação:**

Use para voltar o histórico para um commit anterior sem perder as alterações.

---

### 2. `git reset --hard [commit]`

```bash
git reset --hard [commit]
```

**O que faz:**

Desfaz os commits e descarta as alterações posteriores ao commit especificado.

**Quando usar / observação:**

Use com cuidado, pois as alterações descartadas podem ser perdidas.

---

## Checklist deste arquivo

- [x] 1. `git reset [commit]`
- [x] 2. `git reset --hard [commit]`

---

[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)
