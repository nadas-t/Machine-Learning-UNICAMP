# Machine-Learning-UNICAMP

## 📖 Descrição

Este repositório contém atividades, experimentos e implementações desenvolvidas na disciplina **MC886 - Machine Learning**, oferecida pela **Unicamp**.

O objetivo é aplicar conceitos teóricos de aprendizado de máquina na prática utilizando notebooks interativos.

---

## ⚙️ Pré-requisitos

* Python 3.x
* Visual Studio Code
* Extensões no VSCode:

  * Python
  * Jupyter

---

## 🚀 Setup (primeira vez rodando o projeto)

### 1. Clonar o repositório

```bash
git clone git@github.com:nadas-t/Machine-Learning-UNICAMP.git
cd Machine-Learning-UNICAMP
```

### 2. Criar ambiente virtual

```bash
python3 -m venv venv
```

### 3. Ativar o ambiente

Mac/Linux:

```bash
source venv/bin/activate
```

Windows:

```bash
venv\Scripts\activate
```

### 4. Instalar dependências

```bash
pip install -r requirements.txt
```

---

## 📦 Requirements

As dependências do projeto estão listadas em:

```bash
requirements.txt
```

Se novas bibliotecas forem adicionadas:

```bash
pip freeze > requirements.txt
```

---

## ▶️ Como usar

* Abra o projeto no VSCode
* Abra qualquer arquivo `.ipynb`
* Selecione o kernel do ambiente virtual (`venv`)
* Execute as células normalmente

---

## 🔁 Sempre que for rodar o projeto

1. Ativar o ambiente virtual:

```bash
source venv/bin/activate
```

2. Abrir o VSCode

3. Rodar os notebooks normalmente

---

## ⚠️ Boas práticas

* Não versionar a pasta `venv/`
* Manter o `requirements.txt` atualizado
* Evitar commits com outputs desnecessários nos notebooks

---

## 📁 Estrutura do projeto

```bash
.
├── notebooks/
├── venv/
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🎯 Objetivo

Consolidar o aprendizado em Machine Learning por meio de prática e experimentação em notebooks.
