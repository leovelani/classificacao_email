# Classificação de Emails com Naive Bayes

## Descrição
Este projeto implementa um pipeline completo de classificação de emails (spam × ham) em Python, usando o algoritmo Naive Bayes. Ele abrange desde a coleta e pré-processamento de dados até o treinamento, avaliação e aplicação em cenários de **cibersegurança**, auxiliando na detecção de spam, phishing e outras ameaças por email.

## Funcionalidades
- Leitura de dumps de hashes e listas de emails etiquetados  
- Pré-processamento de texto (tokenização, remoção de stopwords, stemming)  
- Extração de features com TF-IDF  
- Treinamento de modelo Naive Bayes e validação cruzada  
- Geração de métricas: precisão, recall, F1-score e matriz de confusão  
- Exportação de relatórios em CSV/JSON para auditorias de segurança  

## Tecnologias
- Python  
- Scikit-learn  
- Pandas, NumPy  

##Aplicações em Cybersegurança
- A classificação automática de emails é essencial para empresas e sistemas de segurança, pois permite:

-Filtrar mensagens maliciosas e reduzir riscos de phishing
-Monitorar tentativas de ataque via email
-Integrar-se a soluções SIEM e automações de resposta a incidentes
