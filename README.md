# Projeto Final – Visão Computacional  
Classificação de Imagens com CNNs Pré-treinadas (MobileNetV3 vs ResNet18)

## 📌 Descrição do Projeto
Este projeto foi desenvolvido para a disciplina de **Visão Computacional** e tem como objetivo treinar e comparar modelos de deep learning para **classificação de imagens** utilizando arquiteturas pré-treinadas.

Foram avaliadas duas redes neurais amplamente utilizadas em visão computacional:

- **MobileNetV3-Small**
- **ResNet18**

O projeto realiza:
- Carregamento e preparação do conjunto de dados.
- Aplicação de transformações e data augmentation.
- Treinamento supervisionado usando transfer learning.
- Avaliação de acurácia e perda durante as épocas.
- Comparação entre os modelos ao final do treinamento.

Ao final, gráficos de desempenho são gerados para facilitar a análise dos resultados.

---

## 🧰 Tecnologias e Bibliotecas Utilizadas

- **Python 3**
- **PyTorch**
- **Torchvision**
- **Matplotlib**
- **Scikit-learn**
- **Google Colab** (opcional para GPU gratuita)

---

### 1. **Pré-requisitos**

Instalar as dependências abaixo:

```bash
pip install torch torchvision matplotlib scikit-learn

