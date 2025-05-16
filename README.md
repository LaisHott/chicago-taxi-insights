# 🚕 Explorando Corridas de Táxi em Chicago  
### Um estudo para a Zuber: preferências dos passageiros e o impacto do clima nas corridas

Este projeto foi desenvolvido para a **Zuber**, uma nova empresa de caronas que busca entender o comportamento dos passageiros em Chicago. A análise visa identificar padrões nas corridas e como fatores externos — especialmente o clima — influenciam a duração e a frequência das viagens.

## 🧭 Objetivo

Investigar as **preferências dos passageiros** e o **impacto de fatores externos** (como clima e dia da semana) nas corridas de táxi em Chicago, a fim de gerar **insights estratégicos** para otimizar os serviços da Zuber.

## 📦 Fontes de Dados

O banco de dados utilizado inclui:

- 🏙️ Nome e código dos bairros
- 🚕 Identificação de táxis e empresas proprietárias
- ⏱️ Detalhes das corridas (data/hora, duração, distância, local de retirada/entrega)
- 🌦️ Registros meteorológicos (temperatura, data/hora, descrição do clima)

Clima de novembro de 2017 foi obtido diretamente de:  
[Chicago Weather Data - Practicum](https://practicum-content.s3.us-west-1.amazonaws.com/data-analyst-eng/moved_chicago_weather_2017.html)

---

## 🔍 Etapas do Projeto

### 🧩 Passo 1: Extração e análise do clima 🌧️

- Coleta de dados meteorológicos de novembro de 2017 em Chicago
- Conversão dos dados em formato utilizável via SQL

### 📊 Passo 2: Análise Exploratória de Dados

- Número de corridas por empresa de táxi  
- Comparação entre empresas com "Amarelo" ou "Azul" no nome  
- Foco em empresas **Flash Cab** e **Taxi Affiliation Services**  

### 🧪 Passo 3: Teste de Hipóteses

> 📌 **Hipótese:** A duração das corridas do Loop até o Aeroporto O’Hare muda em sábados chuvosos.

- Realização de testes estatísticos para validar ou rejeitar essa hipótese

---

## 💡 Conclusões Esperadas

- Quais empresas dominam o mercado de táxi em Chicago  
- Como o clima afeta a operação das corridas  
- Padrões comportamentais dos passageiros  
- Insights para campanhas e estratégias da Zuber

---

## 🛠️ Tecnologias Utilizadas

- 🐘 PostgreSQL  
- 🐍 Python (Pandas, Matplotlib, Seaborn)  
- 📓 Jupyter Notebook  
- 📊 Testes estatísticos

---
### 📁 Estrutura de Diretórios e Arquivos de Dados

📦 chicago-taxi-insights/
├── 📁 data/
│ ├── 📄 project_sql_result_01.csv
│ ├── 📄 project_sql_result_04.csv
│ └── 📄 project_sql_result_07.csv


### 📊 Descrição dos Arquivos de Dados

- `project_sql_result_01.csv`  
  🔸 Contém:
  - `trips_amount`: número de corridas para cada empresa de táxi entre os dias **15 e 16 de novembro de 2017**.

- `project_sql_result_04.csv`  
  🔸 Contém:
  - `dropoff_location_name`: bairros de Chicago onde as corridas terminaram.  
  - `average_trips`: número médio de corridas que terminaram em cada bairro durante **novembro de 2017**.

- `project_sql_result_07.csv`  
  🔸 Contém:
  - Dados sobre corridas que tiveram **início no Loop** e **destino no Aeroporto Internacional O'Hare**, utilizadas para teste de hipótese sobre duração em sábados chuvosos.

> 💡 Todos os arquivos foram obtidos via consultas SQL durante o projeto e são essenciais para a análise das preferências dos passageiros e o impacto de fatores externos nas corridas de táxi em Chicago.

---

*Projeto desenvolvido como parte da formação em Data Analytics 🎓*
