# Heart Attack Dataset - Análise Exploratória dos Dados (EDA) com foco em Saúde Cardíaca

## Qual meu intuito?
Este é um projeto que iniciei com o objetivo de colocar em prática e consolidar meus conhecimentos em **Pandas** e **análise exploratória de dados (EDA)**.  
Utilizei um dataset contendo informações clínicas relacionadas a ataques cardíacos. A ideia é analisar de forma crítica e gerar insights com relação à saúde cardíaca, entendendo como diferentes variáveis podem influenciar nesses eventos.

---

## O que foi feito?

### Importação e visualização inicial da base de dados
- Leitura do dataset e visualização das primeiras entradas
- Verificação do formato, tipo dos dados, valores nulos e linhas duplicadas
- Análise estatística básica com `.describe()` e `.info()`

### Tratamento de Dados
- Verificação de linhas duplicadas
- Verificação de valores nulos
- Análise de correlação entre variáveis numéricas

### Análises específicas realizadas
- **Distribuição de ataques cardíacos por gênero**  
  Comparação entre homens e mulheres, destacando a proporção de casos em cada grupo

- **Distribuição por idade**  
  Análise da frequência de ataques cardíacos em diferentes faixas etárias

### 📈 Visualizações
- Gráficos de barras

### Treinamento de Modelo de Machine Learning: XGBoost
- Validação Cruzada para obtenção de hiperparâmetros
- Após validação cruzada, realização do treinamento do modelo XGBoost

### Análises Extras:
- Curva de Aprendizado para verificar se há underfitting ou overfitting
- Curva ROC e AUC para verificar se o modelo pode distinguir corretamente a classe positiva e negativa

---

## Tecnologias utilizadas
- **Pandas** – Manipulação e análise de dados
- **Matplotlib** – Criação de gráficos e visualizações
- **Numpy** - Manipulação matemática (especificamente: média para curva ROC e AUC)
- **Sklearn** - Modelos e métricas
- **Jupyter Notebook** – Ambiente de desenvolvimento interativo
