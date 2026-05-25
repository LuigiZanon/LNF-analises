# LNF-analises

Análise estatística (regressão linear multivariada e PCA) dos dados de quarterbacks da NFL 2008.

## Pré-requisitos

- `python3` disponível no `PATH` (o módulo `venv` é parte da biblioteca padrão; em algumas distribuições é necessário instalar `python3-venv` à parte).

## 1. Criar o ambiente local

Na raiz do projeto (`LNF-analises/`):

```bash
python3 -m venv .venv
.venv/bin/pip install --upgrade pip
.venv/bin/pip install -r requirements.txt
```

O diretório `.venv/` já está coberto pelo `.gitignore`.

## 2. Levantar o ambiente para executar

Ative o ambiente na sessão do shell:

```bash
source .venv/bin/activate
```

A partir daí, `python` e `pip` apontam para o ambiente isolado. Para sair, basta `deactivate`.

### Rodar o notebook

- **VS Code:** abra `analise.ipynb` e, no seletor de kernel (canto superior direito), escolha o interpretador `.venv/bin/python`.
- **Jupyter no navegador:**

  ```bash
  jupyter notebook analise.ipynb
  ```

  (caso `jupyter` não esteja disponível, instale com `pip install notebook` dentro do ambiente).
