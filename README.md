# Análise de Dados - Previsão de Churn em Academia

## 📌 Descrição do Projeto
Este projeto realiza uma análise exploratória e preditiva de dados de clientes de uma academia, com foco na identificação de fatores que influenciam o churn (cancelamento de assinatura). O objetivo é desenvolver modelos de machine learning para prever quais clientes têm maior probabilidade de cancelar seus planos.

## 🎯 Objetivos
- Realizar análise exploratória dos dados (AED)
- Identificar padrões e características de clientes que cancelam vs. clientes ativos
- Desenvolver modelos de classificação para prever churn
- Implementar técnicas de clusterização para segmentação de clientes

## 📊 Dataset
O dataset `gym_churn_us.csv` contém informações de 4.000 clientes de academia com as seguintes características:

### Variáveis do Dataset:
- **gender**: Gênero do cliente (0 = Feminino, 1 = Masculino)
- **Near_Location**: Proximidade da academia (0 = Não, 1 = Sim)
- **Partner**: É funcionário de empresa parceira (0 = Não, 1 = Sim)
- **Promo_friends**: Veio através de promoção "traga um amigo" (0 = Não, 1 = Sim)
- **Phone**: Forneceu número de telefone (0 = Não, 1 = Sim)
- **Contract_period**: Período do contrato (meses)
- **Group_visits**: Participa de sessões em grupo (0 = Não, 1 = Sim)
- **Age**: Idade do cliente
- **Avg_additional_charges_total**: Média de gastos com serviços adicionais
- **Month_to_end_contract**: Meses restantes até o fim do contrato
- **Lifetime**: Tempo como cliente (meses)
- **Avg_class_frequency_total**: Frequência média total de aulas
- **Avg_class_frequency_current_month**: Frequência média no mês atual
- **Churn**: Indicador de cancelamento (0 = Ativo, 1 = Cancelou)

## 🔍 Principais Insights da Análise Exploratória

### Estatísticas Gerais:
- **Taxa de churn**: 26.5%
- **Distribuição equilibrada** entre gêneros
- **84.5%** dos clientes moram/trabalham perto da academia
- **90%** dos clientes forneceram número de telefone
- **Média de idade**: 29 anos

### Diferenças entre Grupos (Churn vs. Ativos):

| Característica | Clientes Ativos | Clientes que Cancelaram |
|----------------|-----------------|------------------------|
| Tempo de Contrato | 5.7 meses | 1.7 meses |
| Idade Média | 30 anos | 27 anos |
| Participação em Grupos | 46% | 27% |
| Gastos Adicionais | $158.45 | $115.08 |
| Frequência Semanal | 2 dias | 1 dia |

## 🛠️ Tecnologias Utilizadas
- **Python 3.x**
- **Pandas** - Manipulação de dados
- **NumPy** - Cálculos numéricos
- **Matplotlib/Seaborn** - Visualização de dados
- **Scikit-learn** - Machine Learning
- **SciPy** - Análise estatística

## 📈 Modelos de Machine Learning
O projeto implementa os seguintes algoritmos:
- **Regressão Logística**
- **Random Forest Classifier**
- **K-Means Clustering**
- **Análise de Silhueta**

## 🚀 Como Executar
1. Clone o repositório
2. Instale as dependências: `pip install pandas numpy matplotlib seaborn scikit-learn scipy`
3. Execute o notebook Jupyter: `jupyter notebook notebook_projeto_sprint13.ipynb`

## 📁 Estrutura do Projeto
```
├── notebook_projeto_sprint13.ipynb  # Notebook principal
├── gym_churn_us.csv                 # Dataset
└── README.md                        # Documentação
```

## 📄 Licença
Este projeto é para fins educacionais.

## 🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

Este projeto foi desenvolvido como parte do meu portfólio de Análise de Dados. Feedback é sempre apreciado!
