# Previsão de Preços de Carros Usados

## Descrição

Este projeto utiliza o `ExtraTreesRegressor` para prever o preço de carros usados com base em suas características. O modelo é treinado usando dados com features processadas por `PolynomialFeatures` e normalizadas com `StandardScaler`. O tuning dos hiperparâmetros é realizado com `GridSearchCV`, e o modelo é avaliado com métricas como R², RMSE, MAE e Explained Variance Score.

## Características

- **Pré-processamento de Dados:** 
  - Seleção de características e variável alvo.
  - Aplicação de `PolynomialFeatures` e `StandardScaler`.
  - Divisão em conjuntos de treinamento e teste.

- **Treinamento do Modelo:**
  - `ExtraTreesRegressor` com tuning de hiperparâmetros.

- **Avaliação do Modelo:**
  - Métricas: R² Score, RMSE, MAE e Explained Variance Score.

- **Persistência do Modelo:**
  - Salvamento e carregamento com `joblib`.

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
