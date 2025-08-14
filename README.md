# Transfer-Learning-Project-Python


# 🧠 Transfer Learning em Python — Classificação Carro vs Moto

![Capa](results/grafico_acuracia.png)

---

## 🏅 Badges

- 📦 Tamanho do repositório / Repository Size:  
  ![GitHub repo size](https://img.shields.io/github/repo-size/Rogerio5/Transfer-Learning-Project-in-Python)

- 📄 Licença do projeto / Project License:  
  ![GitHub license](https://img.shields.io/github/license/Rogerio5/Transfer-Learning-Project-in-Python)

- 📊 Acurácia Final / Final Accuracy:  
  ![Accuracy](https://img.shields.io/badge/accuracy-atualizar%20ap%C3%B3s%20treino-blue)

---

## 📋 Índice / Table of Contents

- [📖 Descrição / Description](#📖-descrição--description)
- [🚧 Status / Status](#🚧-status--status)
- [⚙️ Funcionalidades / Features](#⚙️-funcionalidades--features)
- [🌐 Acesso / Access](#🌐-acesso--access)
- [🧰 Tecnologias / Technologies](#🧰-tecnologias--technologies)
- [📦 Dataset](#📦-dataset)
- [🧪 Como Executar / How to Run](#🧪-como-executar--how-to-run)
- [📊 Resultados / Results](#📊-resultados--results)
- [👨‍💻 Pessoa Desenvolvedora / Project Developer](#👨‍💻-pessoa-desenvolvedora--project-developer)
- [📜 Licença / License](#📜-licença--license)
- [🏁 Conclusão / Conclusion](#🏁-conclusão--conclusion)

---

## 📖 Descrição / Description

**PT:**  
Projeto de classificação binária **Carro vs Moto** usando **Transfer Learning** com **MobileNetV2**, aumento de dados (data augmentation) e TensorFlow/Keras. O objetivo é treinar rapidamente um modelo eficiente com baixo custo computacional, pronto para inferência em imagens externas.

**EN:**  
Binary classification **Car vs Motorcycle** using **Transfer Learning** with **MobileNetV2**, data augmentation, and TensorFlow/Keras. The goal is to train an efficient model quickly with low computational cost, ready for inference on external images.

---

# 📊 Resultados do Modelo

Este projeto apresenta os resultados de classificação para duas classes: **Carro** e **Moto**. Abaixo estão as métricas de desempenho obtidas a partir da matriz de confusão e avaliação por classe.

## 🔢 Tabela de Métricas

| Métrica (PT)         | Metric (EN)       | Valor / Value | 🔍 Desempenho |
|----------------------|-------------------|----------------|----------------|
| **Acurácia**         | Accuracy          | 85.0%          | 🟨 Bom         |
| **Precisão Carro**   | Precision (Car)   | 81.8%          | 🟨 Bom         |
| **Recall Carro**     | Recall (Car)      | 90.0%          | 🟩 Excelente   |
| **F1-Score Carro**   | F1-Score (Car)    | 85.7%          | 🟨 Bom         |
| **Precisão Moto**    | Precision (Moto)  | 88.9%          | 🟩 Excelente   |
| **Recall Moto**      | Recall (Moto)     | 80.0%          | 🟨 Bom         |
| **F1-Score Moto**    | F1-Score (Moto)   | 84.2%          | 🟨 Bom         |

## 📈 Visualizações

![Matriz de Confusão](resultados/matriz_confusao.png)
![Métricas por Classe](resultados/metricas_por_classe.png)


---
✅ **Interpretação**: O modelo apresenta desempenho geral **bom**, com destaque para o recall da classe "Carro" e a precisão da classe "Moto". A acurácia total foi de **85%**, indicando uma boa capacidade de classificação.

---

## 🛠️ Como Executar

1. Clone o repositório
2. Instale as dependências
3. Execute o notebook `modelo_classificacao.ipynb`

---

## 🚧 Status / Status

✅ Finalizado e funcional. Você pode treinar, avaliar e prever com imagens novas.

---

## ⚙️ Funcionalidades / Features

| 🧩 PT                          | 💡 EN                               |
|-------------------------------|--------------------------------------|
| 📂 Leitura de pastas locais   | 📂 Load images from local folders    |
| 🖼️ Data augmentation          | 🖼️ Data augmentation pipeline        |
| 🧠 Transfer Learning          | 🧠 MobileNetV2 pretrained backbone   |
| 📊 Treino e validação         | 📊 Training and validation           |
| 📈 Gráficos de métricas       | 📈 Accuracy/Loss charts              |
| 🧾 Matriz de confusão         | 🧾 Confusion matrix                  |
| 💾 Salvamento do modelo       | 💾 Save trained model (.keras)       |
| 🔍 Inferência em nova imagem  | 🔍 Single-image inference            |

---

## 🌐 Acesso / Access

- 🔗 Repositório GitHub / GitHub Repository:  
  https://github.com/Rogerio5/Transfer-Learning-Project-in-Python

---

## 🧰 Tecnologias / Technologies

<p>
  <img align="left" alt="Python" title="Python" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" />
  <img align="left" alt="TensorFlow" title="TensorFlow" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tensorflow/tensorflow-original.svg" />
  <img align="left" alt="Google Colab" title="Google Colab" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/googlecolab/googlecolab-plain.svg" />
  <img align="left" alt="NumPy" title="NumPy" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" />
  <img align="left" alt="Pandas" title="Pandas" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg" />
  <img align="left" alt="Matplotlib" title="Matplotlib" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original.svg" />
</p>

<br clear="all"/>

---

## 📦 Dataset

**Estrutura esperada:**

---

## 👨‍💻 Pessoa Desenvolvedor / Project Developer

- [Rogerio](https://github.com/Rogerio5)

---

## 📜 Licença / License

**PT:** Este projeto está sob licença MIT. Para mais detalhes, veja o arquivo `LICENSE`.  
**EN:** This project is under the MIT license. For more details, see the `LICENSE` file.

---

## 🏁 Conclusão / Conclusion

**PT:**  
Este projeto demonstra como aplicar Transfer Learning de forma eficiente para classificação de imagens, alcançando alta acurácia com baixo custo computacional.

**EN:**  
This project demonstrates how to apply Transfer Learning effectively for image classification, achieving high accuracy with low computational cost.

