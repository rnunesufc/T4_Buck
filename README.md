# Trabalho 4 — Análise, Modelagem e Controle de Conversor Buck

Este repositório contém o desenvolvimento completo de um estudo envolvendo:
- modelagem matemática do conversor *Buck* em regime contínuo;
- linearização e obtenção de função de transferência;
- discretização da planta via diferentes métodos (ZOH, Tustin, Euler backward/forward);
- análise de estabilidade e comportamento dinâmico;
- escolha adequada da taxa de amostragem;
- projeto e avaliação de controlador digital PI;
- simulações comparativas em domínio do tempo e frequência.

Todo o fluxo foi implementado em ambiente `Jupyter Notebook`, visando suporte acadêmico ao estudo de Eletrônica de Potência e Controle Digital.

---

## ▶️ Executar no Google Colab

Clique no botão abaixo para executar **online** (sem instalar nada):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rnunesufc/T4_Buck/blob/main/Trabalho4_buck_revisado.ipynb)

---

## 📘 Arquivo principal

| Arquivo | Descrição |
|---------|-----------|
| `Trabalho4_buck_revisado.ipynb` | Notebook contendo modelagem, análise, discretização e projeto do controlador para o conversor Buck. |

---

## 🧰 Dependências

As bibliotecas utilizadas são:

```bash
python>=3.9
numpy
matplotlib
scipy
control
