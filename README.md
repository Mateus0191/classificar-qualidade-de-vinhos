# classificar-qualidade-de-vinhos
# Classificador de Qualidade de Vinhos com Redes Neurais (MLP)

Este projeto utiliza Machine Learning para prever a qualidade de vinhos tintos com base em características químicas. O objetivo principal foi aplicar uma rede neural artificial do tipo **Multi-layer Perceptron (MLP)** para realizar uma classificação binária.

## 🚀 Sobre o Projeto

A ideia do projeto é transformar um problema de notas (3 a 8) num problema de classificação:
- **Vinho Bom (Classe 1):** Nota igual ou superior a 6.
- **Vinho Ruim (Classe 0):** Nota inferior a 6.

### Tecnologias Utilizadas
* **Python 3**
* **Pandas**: Para manipulação e limpeza dos dados.
* **Scikit-Learn**: Para normalização (`StandardScaler`), divisão de dados (`train_test_split`) e o modelo de IA (`MLPClassifier`).

## 🧠 Lógica de Desenvolvimento

1.  **Pré-processamento:** Como as variáveis químicas (pH, álcool, açúcar) possuem escalas muito diferentes, utilizei o `StandardScaler` para normalizar os dados. Sem isso, a rede neural poderia dar importância indevida a números maiores.
2.  **Arquitetura da Rede:** Configurei a rede com **duas camadas ocultas de 10 neurónios cada**. Esta é uma arquitetura eficiente para o tamanho deste dataset, evitando o *overfitting*.
3.  **Avaliação:** O modelo é avaliado através de um relatório de classificação que analisa a precisão e a capacidade da rede de identificar corretamente os vinhos de qualidade.

## 🛠️ Como correr o projeto

1. Clone o repositório:
   ```bash
   git clone [https://github.com/teu-utilizador/nome-do-repositorio.git](https://github.com/teu-utilizador/nome-do-repositorio.git)
