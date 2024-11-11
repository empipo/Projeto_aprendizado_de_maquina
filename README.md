# Projeto de Aprendizado de Máquina - Modelos Preditivos da Resistência à Compressão do Concreto 🧱🖥️
 
## Descrição 📄
 
Este trabalho é o projeto final da disciplina de Aprendizado de Máquina ministrada pelo professor Dr. Daniel Cassar na instituição de ensino superior: Ilum - Escola de Ciência, anexa ao Centro Nacional de Pesquisa em Energia e Materiais (CNPEM). Esse trabalho se propõem a realizar modelos preditivos sobre um dataset de Concreto, no qual foi previsto a resistência à compressão (target) com as seguintes features: Cement, Blast Furnace Slag, Fly Ash, Water, Superplasticizer, Coarse Aggregate, Fine Aggregate, Age (day). Os modelos preditivos realizados no trabalho foram:
- Baseline
- Regressão Linear Múltipla
- K-Viznhos mais próximos
- Árvores de Decisão
- Floresta Aleatória
Além disso, foi feito a normalização padrão, pelo mínimo e máximo, e pelo máximo absoluto. Foi utilizado da seleção de atributos para verificar se a redução de atributos era benéfica ou não para o modelo

## 🤖 Algoritmos de Aprendizado de Máquina

### 1. **Baseline**
- **Objetivo**: Estabelecer um modelo simples de referência para comparar com modelos mais complexos.
- **Utilidade**:
  - Serve como ponto de partida para avaliar a eficácia de modelos mais sofisticados.
  - Pode ser uma média ou uma simples previsão, ajudando a verificar se modelos mais complexos realmente oferecem melhorias significativas.

### 2. **Regressão Linear Múltipla**
- **Objetivo**: Modelar a relação entre uma variável dependente e várias variáveis independentes.
- **Utilidade**:
  - Usada para prever valores contínuos.
  - Permite entender a contribuição de cada variável independente para a previsão da variável dependente.

### 3. **K-Vizinhos Mais Próximos (K-NN)**
- **Objetivo**: Classificar ou prever o valor de uma observação com base nos k vizinhos mais próximos no espaço de características.
- **Utilidade**:
  - Utilizado para problemas de classificação e regressão.
  - Não requer um modelo explícito de treinamento, baseando-se diretamente nas observações do conjunto de dados.

### 4. **Árvores de Decisão**
- **Objetivo**: Construir um modelo de decisão em forma de árvore para prever o valor de uma variável de saída com base em variáveis de entrada.
- **Utilidade**:
  - Intuitivo e fácil de interpretar, ideal para visualização de decisões e regras.
  - Usado para problemas de classificação e regressão.
  - Lida bem com dados não lineares e pode capturar interações entre variáveis.

### 5. **Floresta Aleatória (Random Forest)**
- **Objetivo**: Melhorar o desempenho das Árvores de Decisão, criando uma coleção de árvores e combinando seus resultados (ensemble learning).
- **Utilidade**:
  - Aumenta a precisão do modelo ao reduzir o risco de overfitting.
  - Ideal para grandes conjuntos de dados e é robusto a dados ruidosos e desbalanceados.
  - Pode ser usado tanto para classificação quanto para regressão.

## 📊 PCA (Principal Component Analysis) e Matriz de Correlação

### 1. **PCA (Análise de Componentes Principais)**
- **Objetivo**: Reduzir a dimensionalidade de um conjunto de dados, mantendo as características mais importantes.
- **Utilidade**:
  - Facilita a visualização de dados de alta dimensão (em 2D ou 3D).
  - Melhora a performance de modelos de aprendizado de máquina ao eliminar variáveis irrelevantes ou redundantes.
  - Remove a multicolinearidade, ao combinar variáveis correlacionadas em componentes independentes.

### 2. **Matriz de Correlação**
- **Objetivo**: Medir o grau de correlação entre as variáveis em um conjunto de dados.
- **Utilidade**:
  - Identifica relações entre variáveis, ajudando a entender padrões nos dados.
  - Prevê problemas de multicolinearidade, permitindo a escolha de variáveis mais relevantes para modelos de aprendizado.
  - Facilita a análise exploratória, destacando quais variáveis estão fortemente correlacionadas.
 
## Pré-requisitos 🔍

-**Software:** 🖥️
  - Bibliotecas Python: Bibliotecas
    [![pandas](https://img.shields.io/badge/pandas-Latest-yellow)](https://pandas.pydata.org/)
    [![seaborn](https://img.shields.io/badge/seaborn-Latest-teal)](https://seaborn.pydata.org/)
    [![os](https://img.shields.io/badge/os-Latest-gray)](https://docs.python.org/3/library/os.html)
    [![numpy](https://img.shields.io/badge/numpy-Latest-orange)](https://numpy.org/)
    [![scikit-learn](https://img.shields.io/badge/scikit--learn-Latest-blue)](https://scikit-learn.org/)
    [![optuna](https://img.shields.io/badge/optuna-Latest-green)](https://optuna.org/)
## Instalação 🔧
 
1. **Clone o repositório:**
 
   ```bash
   git clone https://github.com/empipo/Projeto_aprendizado_de_maquina
   cd Projeto_aprendizado_de_maquina

 
2. **Instale as dependências Python:**
 
    ```bash
    !pip install pandas seaborn numpy scikit-learn optuna

 

{comentar sobre o projeto, citando os algoritimos usados e as formas de visualização}


 
## Contribuição
 
Se você deseja contribuir com este projeto, siga os passos abaixo:
 
1. Faça um fork do repositório.
2. Crie um branch para a sua feature (\`git checkout -b feature/nova-feature\`).
3. Commit suas alterações (\`git commit -am 'Adiciona nova feature'\`).
4. Push para o branch (\`git push origin feature/nova-feature\`).
5. Crie um novo Pull Request.
 
## Colaboradores
 
## Nome dos colaboradores
</div>
 
- Emanuel Piveta Pozzobon
- Adrian Lincoln Paz Silva
- José Victor da Silva Izidorio
 
<br>
 
  
 
<p align="center">
<img src="https://github.com/JVictor1604/Otimiza-o_do_Espalhamento_Rayleight_PCD/assets/171518829/fe1b443f-1c9e-42f2-88e8-85e1b4400fd0" alt="Descrição da imagem">
</p>
 
## Licença
Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).
EOF
