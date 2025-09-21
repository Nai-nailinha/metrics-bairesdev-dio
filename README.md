# Cálculo de Métricas de Avaliação (Classificação)

Projeto do bootcamp para calcular, a partir de uma matriz de confusão (VP, VN, FP, FN), as principais métricas de avaliação de modelos de classificação:

- **Acurácia** = (VP + VN) / (VP + VN + FP + FN)
- **Precisão (PPV)** = VP / (VP + FP)
- **Sensibilidade / Recall (TPR)** = VP / (VP + FN)
- **Especificidade (TNR)** = VN / (VN + FP)
- **F1-Score** = 2 * (Precisão * Recall) / (Precisão + Recall)
- (Opcional) **Fallout (FPR)** = FP / (FP + VN)  
- (Opcional) **NPV** = VN / (VN + FN)  
- (Opcional) **Prevalência** = (VP + FN) / Total

## Como usar
1. Abra o `metrics.ipynb` no Google Colab (ou rode `metrics.py` localmente).
2. Edite os valores de `VP`, `VN`, `FP`, `FN` no bloco “Exemplo rápido”.
3. Execute as células. O script imprime a matriz de confusão formatada e todas as métricas.

## Exemplo de matriz (ajuste como quiser)
VP=90, VN=50, FP=10, FN=20

## Estrutura sugerida
```
├── metrics.ipynb
├── README.md
└── (opcional) results.txt
```


Este projeto tem caráter didático: a matriz de confusão pode ser escolhida de forma **arbitrária**, conforme orientado no enunciado, para focar no entendimento das fórmulas.
Feito por: 
**Enaile Lopes**
