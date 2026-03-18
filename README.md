# 📊 Análise de Vendas — Diagnóstico Inteligente por KPIs

![Análise de Dados](https://img.shields.io/badge/Análise%20de%20Dados-2962FF?style=for-the-badge&logo=databricks&logoColor=white)
![Ciência de Dados](https://img.shields.io/badge/Ciência%20de%20Dados-4CAF50?style=for-the-badge&logo=python&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Estatística](https://img.shields.io/badge/Estatística-9C27B0?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=for-the-badge)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

---

## 📌 Objetivo do Projeto

Este repositório tem como finalidade desenvolver uma **análise científica de vendas**, identificando **gatilhos de crescimento** por meio de uma **cesta múltipla de KPIs**.  
A proposta é construir um diagnóstico robusto da saúde dos indicadores, utilizando técnicas estatísticas, modelagem e visualização de dados.

A análise será conduzida em **Python**, com notebooks desenvolvidos no **Google Colab**, utilizando bibliotecas de ciência de dados e estatística.

---

> **Nota de Confidencialidade:** Devido a políticas de LGPD, dados sensíveis e nomes de colunas reais foram omitidos ou mascarados. Para análises horizontais, o nome dos agentes foi codificado no formato (Codinome&ID). O foco deste repositório é demonstrar a arquitetura da solução e os diagnósticos obtidos em contribuição ao negócio.

## 🧠 Pergunta Central

**Quais KPIs influenciam diretamente o aumento de vendas e como podemos diagnosticar sua saúde para gerar ações estratégicas?**

---

## 🧪 Técnicas e Métodos Utilizados

### **📈 Estatística Descritiva e Exploratória**
- 📝 Análise da dispersão em Gauss  
- 📝 Dispersão de grupo  
- 📝 Histograma  
- 💬 Coeficiente de variação  
- 💬 Fator Bond  
- 📝 Boxplots por KPI  
- 📝 Matriz de correlação  
- 📝 Heatmap  
- 📝 PCA (Análise de Componentes Principais)

### **📉 Modelagem e Regressão**
- 📝 Regressão múltipla  
- 📝 Regressão cruzada  
- 📝 Componentes chave  
- 📝 Exemplos comuns de regressão aplicada  

### **🧪 Planejamento de Experimentos**
- 📝 Quadrado Latino (DQL)  
- 📝 Delineamento Fatorial  
- 📝 Carta de controle  

### **📊 Séries Temporais**
- 📝 Modelo ARIMA  
- 📝 Modelo autoregressivo  

### **🧬 Inteligência Artificial**
- 📝 Neurônio artificial  
- 📝 Arquitetura multicamadas (MLP)  
- 📝 Treinamento & Backpropagation  

---

## 🧰 Ferramentas e Tecnologias

- **Python** para análise científica  
- **Pandas** para manipulação de dados  
- **NumPy** para cálculos numéricos  
- **SciPy** para estatística avançada  
- **Scikit-Learn** para modelagem e machine learning  
- **Matplotlib & Seaborn** para visualização  
- **Google Colab** para desenvolvimento dos notebooks  
- **GitHub** para versionamento e colaboração  

---

## 📂 Estrutura do Repositório
📁 analise-de-vendas
├── 📁 data/                # Bases de dados brutas e tratadas
├── 📁 notebooks/           # Notebooks de análise
├── 📁 src/                 # Scripts auxiliares
├── 📁 reports/             # Relatórios e gráficos gerados
├── README.md               # Documentação principal
└── requirements.txt        # Dependências do projeto


---

## 🎯 Resultado Esperado

- Identificação dos KPIs mais sensíveis ao aumento de vendas  
- Diagnóstico da saúde dos indicadores  
- Modelos estatísticos e preditivos para suporte à decisão  
- Visualizações claras e acionáveis  
- Insights estratégicos para crescimento sustentável  

---

## 🔄 Plano de execução das analises

- Importar e tratar a base de vendas  
- Criar análises exploratórias iniciais  
- Aplicar técnicas estatísticas listadas  
- Construir modelos preditivos  
- Gerar relatório final com recomendações  

---

## 📌 Conclusões da Análise Científica de Vendas

A análise estatística e multivariada dos KPIs revelou um comportamento operacional dividido em **dois motores distintos**, indicando que a operação não funciona como um sistema homogêneo. Esse achado é central para qualquer decisão estratégica futura.

### 🔍 Diagnóstico Estrutural dos KPIs
- Os indicadores apresentam **duas dinâmicas independentes**, sugerindo que parte da operação responde a estímulos comerciais enquanto outra parte responde a critérios de qualidade.
- Caso a estratégia deseje **aumentar a correlação entre os KPIs**, será necessária uma **revisão profunda dos critérios de Qualidade** aplicados no processo de vendas.
- Se a estratégia for manter a **Qualidade como guardião do processo**, a estrutura atual está coerente com esse objetivo.

### 🚨 Risco Operacional: ABS e Instabilidade
Os ensaios estatísticos (dispersão, fator Bond, coeficiente de variação, cartas de controle e DQL) apontaram:

- **Instabilidade significativa** nos indicadores de ABS.
- **Descontrole estatístico**, sugerindo risco operacional em médio e longo prazo.
- Impactos diretos em:
  - Turnover  
  - Processos de Recrutamento & Seleção prolongados  
  - Formação inicial acima do esperado para o segmento  
- A recomendação inicial é a operação trabalhar com:
  - **ABS ≈ 7%**
  - **Turnover variando entre 5% e 8%**

Diante disso, é **altamente recomendado abrir um DMAIC específico para ABS**, com foco em estabilização e controle.

### 📈 Regressão Múltipla e Cruzada
A análise inicial sugere:

- **Strike_Rate** deve ser tratado como variável resposta principal.
- **Hit_Rate**, apesar da colinearidade, deve ser testado:
  - junto com Strike_Rate  
  - e isoladamente  

Isso porque a percepção operacional indica que **um não necessariamente chama o outro**, apesar da correlação estatística.  
O objetivo é validar ou refutar essa hipótese, evitando viés de confirmação.

### 🧪 DQL, MLP e RNA — Hipóteses Estratégicas
- O **DQL** mostrou que o planejamento estratégico de divisão de carteira está correto: não há perda de timing do lead.
- Entretanto, **MLP e RNA** levantaram uma hipótese crítica:
  - possível **ineficiência de penetração de carteira** no trade-off **Qualidade × Comercial**.
- Essa hipótese **não foi testada neste ensaio**, mas deve ser tratada como **próximo passo prioritário**.

---

## 🔮 Próximos Passos Científicos

### 📅 1. Ampliar a série histórica
- Mínimo de **24 meses** para:
  - viabilizar **SARIMA** com sazonalidade real  
  - aumentar robustez dos modelos preditivos  
- A série atual opera no limite da significância estatística.

### 👥 2. Clusterização de agentes por perfil de carteira
- Segmentar agentes por:
  - volume  
  - ticket  
  - categoria de cliente  
- Objetivo: identificar se o trade-off **Qualidade × Comercial** é:
  - comportamental (perfil do agente)  
  - ou estrutural (planejamento da carteira)

### 🧪 3. Validar hipótese de penetração de carteira
- Testar se agentes com maior diversidade de PDVs apresentam queda sistemática de qualidade.
- Controlar por tipo de carteira.
- Se confirmado: o problema é **planejamento**, não **performance individual**.

### 📉 4. Regressão múltipla em dois cenários
Rodar modelos com:
- **Strike_Rate isolado**
- **Hit_Rate isolado**

Comparar:
- coeficientes  
- resíduos  
- significância  

Se convergirem → colinearidade operacional confirmada.  
Se divergirem → existem drivers distintos que a correlação simples não capturou.

### 🤖 5. Validação real dos modelos de ML
- Separar **20% da série como holdout temporal** antes de treinar MLP e RNA.
- Objetivo: garantir que o R² reflita **capacidade preditiva real**, não ajuste ao treino.

---

Essas conclusões consolidam o diagnóstico atual e apontam um caminho claro para aprofundar a análise científica, reduzir riscos operacionais e orientar decisões estratégicas baseadas em evidências.

