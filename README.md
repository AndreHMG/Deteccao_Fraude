# Deteccao_Fraude

Análise de Detecção de Fraude em Cartões de Crédito

Este projeto tem como foco a detecção de transações fraudulentas em cartões de crédito, utilizando um dataset de transações de titulares europeus de setembro de 2013. O dataset contém 284.807 transações, com apenas 492 casos de fraude (0,172%), tornando-o altamente desbalanceado. Para abordar essa questão, a análise utiliza regressão logística para prever transações fraudulentas. As principais bibliotecas utilizadas incluem pandas, numpy e scikit-learn. O desempenho do modelo é avaliado com base em métricas de acurácia e precisão, com ênfase na Área Sob a Curva de Precisão-Recall (AUPRC), devido ao desbalanceamento do conjunto de dados.
