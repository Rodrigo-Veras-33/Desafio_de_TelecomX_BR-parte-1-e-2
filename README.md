📊 Análise de Prevenção de Evasão de Clientes (Churn Prediction)
Este repositório contém uma solução completa de Data Science para previsão e prevenção de evasão de clientes (churn) utilizando múltiplos algoritmos de machine learning.

🚀 Visão Geral
O projeto analisa os principais fatores que levam à evasão de clientes e propõe estratégias baseadas em dados para redução do churn. Foram implementados e comparados quatro modelos diferentes:

Regressão Logística

K-Nearest Neighbors (KNN)

Random Forest

Support Vector Machine (SVM)

📂 Estrutura do Repositório
text
churn-prediction/
├── data/
│   ├── raw/                    # Dados brutos originais
│   ├── processed/              # Dados pré-processados
│   └── outputs/                # Resultados e análises
├── notebooks/
│   ├── 1_EDA.ipynb             # Análise exploratória
│   ├── 2_Feature_Engineering.ipynb
│   ├── 3_Model_Training.ipynb  # Treinamento dos modelos
│   └── 4_Results_Analysis.ipynb
├── src/
│   ├── preprocessing.py        # Funções de pré-processamento
│   ├── modeling.py             # Funções de modelagem
│   └── visualization.py        # Funções de visualização
├── reports/                    # Relatórios em PDF/PPT
├── models/                     # Modelos treinados (pickle)
└── README.md                   # Este arquivo
🔍 Principais Descobertas
Os modelos identificaram como fatores críticos para evasão:

📉 Contratos mensais (aumentam risco em +78%)

💰 Cobranças mensais elevadas (+65% risco)

🆕 Tempo curto como cliente (<6 meses)

🛡️ Falta de serviços de segurança online

💡 Estratégias de Retenção Propostas
Programa de fidelização para contratos anuais

Monitoramento proativo de clientes novos

Pacotes promocionais para serviços de segurança

Sistema de alerta para clientes de alto risco

🛠️ Como Executar
Clone o repositório:

bash
git clone https://github.com/seu-usuario/churn-prediction.git
Instale as dependências:

bash
pip install -r requirements.txt
Execute os notebooks na ordem numérica:

text
1_EDA.ipynb → 2_Feature_Engineering.ipynb → 3_Model_Training.ipynb → 4_Results_Analysis.ipynb
📊 Resultados
Modelo	Acurácia	Precisão	Recall	F1-Score
Regressão Logística	0.85	0.83	0.78	0.80
Random Forest	0.89	0.87	0.82	0.84
KNN	0.82	0.81	0.75	0.78
SVM	0.84	0.82	0.80	0.81

🤝 Como Contribuir
Faça um fork do projeto

Crie sua branch (git checkout -b feature/nova-feature)

Commit suas mudanças (git commit -m 'Adiciona nova feature')

Push para a branch (git push origin feature/nova-feature)

Abra um Pull Request

📝 Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para detalhes.
