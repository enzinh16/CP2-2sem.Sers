# **CP2 2ºsem - SERS**

# **Integrantes do grupo:**
- Bruno Soares RM: 562235
- Enzo Yokokura Araujo RM: 564177
- Kaua Peres de Macedo RM: 563977
- Marco Antonio Ferreira Fonseca RM: 566434

# **Conclusões**
## - Classificação (Solar)
Random Forest foi o modelo com melhor desempenho, reduzindo erros em comparação à Árvore de Decisão, principalmente na classe de Alta Radiação, mostrando-se mais robusto.Sendo assim é o modelo mais confiável para detectar períodos de alta e baixa radiação, por equilibrar bem precisão e robustez frente às variações dos dados.

## - Regressão (Eólica)
O Random Forest Regressor se mostrou ligeiramente superior à regressão linear, combinando alta capacidade explicativa e menor erro de previsão, sendo o modelo mais indicado para estimar a potência gerada pelas turbinas eólicas.

## – Regressão (Appliances Energy Prediction)
O modelo Random Forest apresentou o melhor desempenho, explicando mais da metade da variabilidade dos dados e obtendo os menores erros (RMSE e MAE). Dessa forma, pode ser considerado o modelo mais adequado para a tarefa de previsão do consumo de energia dos eletrodomésticos a partir das variáveis ambientais.

## – Classificação (Smart Grid Stability)
O modelo de Árvore de Decisão é o mais adequado para este problema, pois conseguiu classificar corretamente todos os exemplos. No entanto, vale ressaltar que resultados perfeitos podem indicar possível overfitting, sendo importante validar em outros conjuntos de dados. Ainda assim, dentro dos experimentos realizados, a Árvore de Decisão se mostrou a melhor escolha para a detecção de instabilidade da rede elétrica.