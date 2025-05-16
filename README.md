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

*Projeto desenvolvido como parte da formação em Data Analytics 🎓*
