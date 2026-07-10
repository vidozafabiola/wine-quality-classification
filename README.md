# wine-quality-classification
Wine Quality Classification using Machine Learning | FIAP Pós-Tech Data Analytics - Tech Challenge- Fase 2

# 🍷 Wine Quality Classification using Machine Learning

Projeto desenvolvido para o **Tech Challenge – Fase 2** da Pós-Graduação em Data Analytics da FIAP.

## 🎥 Vídeo Executivo

▶️ **Assista à apresentação do projeto:**

[🎬 Assistir ao vídeo executivo](https://youtu.be/IarhLVRQj0w)

📄 **Apresentação Executiva**

➡️ [Clique aqui para acessar a apresentação](results/apresentacao_executiva.pdf)

O objetivo deste projeto foi desenvolver modelos de Machine Learning capazes de classificar vinhos tintos em duas categorias de qualidade (baixa e alta), utilizando características físico-químicas da bebida.

---

# 🎯 Objetivo

Desenvolver uma solução baseada em Machine Learning para apoiar a classificação da qualidade dos vinhos, auxiliando especialistas na tomada de decisão e contribuindo para um processo mais rápido, padronizado e orientado por dados.

---

# 📊 Base de Dados

Foi utilizada a base **Wine Quality Dataset (Red Wine)**, disponível no UCI Machine Learning Repository.

A base contém **1.143 amostras** de vinhos tintos e **11 variáveis físico-químicas**, incluindo:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

A variável **Quality** foi transformada em um problema de classificação binária:

- Baixa qualidade
- Alta qualidade

---

# 📁 Estrutura do Projeto

```text
wine-quality-classification/

├── data/
│   └── Base de dados utilizada
│
├── notebooks/
│   └── Notebook com toda a análise
│
├── results/
│   ├── EDA/
│   ├── ML/
│   └── Apresentação Executiva
│
├── src/
│   └── Scripts auxiliares
│
├── requirements.txt
└── README.md
```

---

# 🔍 Metodologia

O projeto foi desenvolvido seguindo as seguintes etapas:

1. Compreensão do problema de negócio.
2. Análise Exploratória dos Dados (EDA).
3. Pré-processamento dos dados.
4. Desenvolvimento dos modelos de Machine Learning.
5. Avaliação e comparação dos modelos.
6. Interpretação dos resultados.

---

# 📈 Principais Insights

Durante a análise exploratória foram identificados alguns resultados relevantes:

- A base apresentou classes desbalanceadas.
- O teor de álcool apresentou relação positiva com a qualidade dos vinhos.
- Variáveis relacionadas à acidez também demonstraram influência importante na classificação.
- Foram identificados outliers em diferentes variáveis, porém considerados compatíveis com dados reais do processo produtivo.

---

# 🤖 Modelos Desenvolvidos

Foram avaliados três modelos de classificação:

- Logistic Regression
- Decision Tree
- Random Forest

---

# 🏆 Resultado Final

Após a comparação entre os modelos, o **Random Forest** apresentou o melhor desempenho geral, demonstrando maior capacidade para classificar corretamente a qualidade dos vinhos.

Além do desempenho obtido, o modelo permitiu identificar as variáveis mais relevantes para a classificação, fornecendo informações úteis para apoiar o controle da qualidade do processo produtivo.

---

# 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Imbalanced-Learn
- Google Colab
- GitHub

---

# ▶️ Como Executar

1. Clone este repositório.

```bash
git clone https://github.com/vidozafabiola/wine-quality-classification.git
```

2. Instale as dependências.

```bash
pip install -r requirements.txt
```

3. Execute o notebook localizado na pasta:

```text
notebooks/
```

---

# 📑 Apresentação Executiva

A apresentação executiva utilizada neste projeto encontra-se disponível em:

```text
results/apresentacao_executiva.pdf
```

---

# 👩‍💻 Autora

**Fabiola Andrea Vidoza Fernandez**

Pós-Tech Data Analytics – FIAP

Tech Challenge – Fase 2
