# Reprodução e Expansão do Estudo Epidemiológico de Tumores Mamários Caninos nas Ilhas Canárias: Uma Aborgagem de Classificação Binária. 

Este repositório reúne análises sobre tumores mamários caninos com dois focos principais:

1. **Reprodução** do artigo *Epidemiology of canine mammary tumours on the Canary Archipelago in Spain*.
2. **Contribuições de modelagem preditiva** no notebook `notebooks/model.ipynb`.

> Este trabalho foi desenvolvido como **TCC do curso de Ciência da Computação da CESAR School**.

## Estrutura do projeto

- `/notebooks/reproduction.ipynb` — reprodução dos resultados epidemiológicos do artigo.
- `/notebooks/model.ipynb` — experimentos de modelagem estatística e de machine learning.
- `/figs/reprodução` — figuras geradas na etapa de reprodução.
- `/figs/modelo` — figuras e matrizes de confusão dos modelos.
- `/output` — saídas auxiliares de análise.

## Reprodução do artigo (resumo)

No notebook `reproduction.ipynb`, o projeto reproduz rapidamente os principais blocos analíticos do artigo:

- Tabelas descritivas epidemiológicas (proporções, distribuição por grupos e evolução temporal).
- Comparações de idade e status de castração.
- Estudo caso-controle com regressão logística para estimativa de risco (Odds Ratio) por raça e ilha.
- Métricas e visualizações comparáveis às figuras e tabelas reportadas no estudo original.

## Contribuições realizadas (`model.ipynb`)

Além da reprodução, o projeto amplia a análise com modelagem preditiva:

- Construção da base para classificação e análise exploratória da distribuição das classes.
- Treinamento e avaliação de modelos de regressão logística (com e sem penalização).
- Treinamento e ajuste de modelos baseados em árvores (**Random Forest** e **XGBoost**).
- Estratégias para desbalanceamento com **SMOTE**.
- Comparação de desempenho com métricas como acurácia, precisão, recall, F1, AUC e matriz de confusão.

## Bibliotecas utilizadas

Principais bibliotecas utilizadas no projeto:

- `pandas`
- `numpy`
- `scipy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `statsmodels`
- `imbalanced-learn` (SMOTE)
- `xgboost`

## Referência do artigo reproduzido

Silva, M. E., Pereira, A. S., & Balbinot, D. D. (2022). *Epidemiology of canine mammary tumors in the Canary Archipelago, Spain*. **BMC Veterinary Research**, 18, 132. https://doi.org/10.1186/s12917-022-03363-9

## Como citar este repositório

Você pode citar este repositório no formato sugerido abaixo:

**Formato textual (ABNT simplificado):**

> CARLOS3DU. *canine-mammary-tumors*. GitHub, 2026. Disponível em: <https://github.com/Carlos3du/canine-mammary-tumors>. Acesso em: 13 maio 2026.

**BibTeX:**

```bibtex
@misc{carlos3du_canine_mammary_tumors,
  author       = {Carlos3du},
  title        = {canine-mammary-tumors},
  year         = {2026},
  howpublished = {\url{https://github.com/Carlos3du/canine-mammary-tumors}},
  note         = {Repositório GitHub. Acesso em: 2026-05-13}
}
```
