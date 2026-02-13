# 📊 Análise de Cancelamento de Clientes (Customer Churn)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://python.org)
[![Whisper](https://img.shields.io/badge/Whisper-OpenAI-black?logo=openai)](https://openai.com)
[![Gemini](https://img.shields.io/badge/Gemini-API-blue?logo=google)](https://deepmind.google)
[![pyttsx3](https://img.shields.io/badge/TTS-pyttsx3-green)]()
[![Licença](https://img.shields.io/badge/license-MIT-green)](LICENSE)

**Autor:** Davi Bezerra Fraga  
**Tecnologias:** Python • Pandas • Plotly • Jupyter Notebook

---

## 📌 Visão Geral

Este projeto realiza uma análise de dados completa para identificar os principais fatores que levam ao cancelamento de clientes (*churn*) em uma empresa fictícia de serviços. O objetivo é transformar dados brutos em insights estratégicos, simulando um cenário real de negócios para apoiar decisões orientadas à retenção de clientes.

---

## 🎯 Objetivos

- Calcular e interpretar a taxa de cancelamento
- Identificar padrões comportamentais associados ao churn
- Avaliar o impacto de variáveis como tipo de contrato, atrasos e contatos com suporte
- Propor ações baseadas em dados para reduzir o churn
- Demonstrar habilidades práticas em análise de dados com Python

---

## 🗺️ Etapas da Análise

1. **Aquisição dos Dados:** Carregamento da base `customer_churn_data.csv`
2. **Limpeza e Tratamento:** Remoção de valores nulos e colunas irrelevantes (`CustomerID`)
3. **Análise Exploratória (EDA):** Investigação de variáveis como idade, sexo, tempo de cliente, frequência de uso e ligações ao call center
4. **Visualização:** Criação de gráficos interativos com Plotly para identificação de padrões de churn
5. **Geração de Insights:** Recomendações estratégicas baseadas nos dados

---

## 🔑 Principais Resultados

- **Taxa de churn inicial:** 56,7%
- **Fatores críticos identificados:** contratos mensais, altos atrasos nos pagamentos e múltiplas ligações ao call center
- **Simulação pós-análise:** aplicando filtros com base nos insights, a taxa de churn foi reavaliada para **15,78%**, demonstrando o impacto de estratégias direcionadas

---

## 🛠️ Tecnologias Utilizadas

- **Python:** Linguagem principal
- **Pandas:** Manipulação e análise de dados
- **Plotly:** Visualizações interativas
- **Jupyter Notebook:** Ambiente de desenvolvimento

---

## 📁 Estrutura do Projeto

```
📁 Churn-Analysis-with-Python/
│
├── 📁 data/
│   └── 📄 customer_churn_data.csv
│
├── 📁 ipynb/
│   └── 📄 Customer_Churn_Analysis.ipynb
│
├── 📄 README.md
├── 📄 LICENSE
└── ⚙️ .gitignore
```

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Davibzf/Churn-Analysis-with-Python.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd Churn-Analysis-with-Python
   ```
3. Execute o notebook:
   ```bash
   jupyter notebook "ipynb/Customer_Churn_Analysis.ipynb"
   ```

---

## 👨‍💻 Autor

**Davi Bezerra Fraga**  
- 🔗 [LinkedIn](https://www.linkedin.com/in/davi-bezerra-fraga-319a49363/)
- 🐙 [GitHub](https://github.com/Davibzf)
- 📧 [Email](mailto:davibezerrafraga@gmail.com)
- 🌐 [Portfólio](https://davibezerrafraga.vercel.app)

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.


---

⭐ **Se este projeto foi útil para você, considere deixar uma estrela!**

---

## ⚠️ Aviso Legal

Este projeto possui fins exclusivamente educacionais e demonstrativos. Os dados utilizados são fictícios e as análises não devem ser aplicadas diretamente em cenários reais sem a devida validação e adaptação ao contexto de negócio.
