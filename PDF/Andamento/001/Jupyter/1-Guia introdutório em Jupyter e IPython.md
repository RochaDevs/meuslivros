# 📓 Jupyter / IPython — Guia Rápido

---

## 🧠 Recursos úteis do Jupyter/IPython

---

## 🔍 1. Ajuda rápida com `?`

Use `?` para acessar a documentação de funções, métodos ou objetos.

### 📌 Exemplos

```python
len?
```

```python
minha_func?
```

> ⚠️ Para funções próprias, é necessário definir uma **docstring**

### 💡 Exemplo completo

```python
def soma(a, b):
    """Soma dois números"""
    return a + b

soma?
```

---

## ⚡ 2. Autocomplete com `TAB`

Use `TAB` para descobrir métodos e atributos disponíveis.

### 📌 Como usar

```python
obj.<TAB>
```

👉 Mostra tudo que pode ser usado no objeto

### 🔍 Atributos "ocultos"

```python
obj._<TAB>
```

---

## 📦 3. Autocomplete em imports

Facilita encontrar módulos e pacotes rapidamente.

### 📌 Exemplo

```python
import nump<TAB>
```

---

## 🎯 4. Wildcard matching (`*`)

Permite buscar métodos por padrão (parte do nome).

### 📌 Exemplo

```python
str.*find*
```

👉 Retorna tudo que contém `"find"`

---

## 🚀 Resumo geral

| Comando        | Função                  |
| -------------- | ----------------------- |
| `?`            | Documentação rápida     |
| `TAB`          | Autocomplete            |
| `import + TAB` | Autocomplete de módulos |
| `*`            | Busca por padrão        |

---

## 💡 Dica final

> Use esses recursos constantemente — eles aceleram MUITO seu aprendizado e produtividade no Python.

---
