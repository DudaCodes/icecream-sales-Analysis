# 🍦 Análise de Vendas de Sorvete com Pandas

Projeto desenvolvido como exercício prático do curso de Ciência de Dados com Python na plataforma Udemy. A proposta é realizar uma análise exploratória de vendas de sorvete com base na temperatura ambiente, utilizando Python e Pandas, aplicando técnicas de ordenação, visualização e exportação de dados.

---

## 📌 Objetivo

Explorar e visualizar a relação entre temperatura e volume de vendas de um caminhão de sorvete. O projeto envolve:

- Conversão de temperaturas de Fahrenheit para Celsius
- Ordenação dos dados por temperatura
- Criação de gráficos para análise visual

Os resultados são salvos em arquivos `.pdf` para documentação e comparação.

---

## 🧰 Tecnologias Utilizadas

- Python 3
- Biblioteca Pandas
- Biblioteca Matplotlib
- Arquivo `IceCreamData.csv` como fonte de dados

---

## 📁 Funcionalidades do Script

O notebook `IceCream.ipynb` executa as seguintes operações:

1. 🌡️ **Conversão de temperatura**
   - Converte os valores de temperatura de Fahrenheit para Celsius usando a fórmula:
     ```
     Celsius = (Fahrenheit - 32) * 5/9
     ```

2. 📊 **Visualização com gráfico**
   - Cria um gráfico de linha relacionando temperatura (°C) com as vendas em dólares.
   - O gráfico é salvo como `icecream_sales_Celsius.pdf`.

3. 🗃️ **Organização e exportação**
   - Os dados são ordenados da temperatura mais quente para a mais fria.
   - A visualização permite identificar como a temperatura influencia nas vendas.

---

## 📂 Arquivos do Projeto

- `IceCream.ipynb` – Notebook com a análise e geração dos gráficos.
- `IceCreamData.csv` – Base de dados utilizada.
- `icecream_sales_Fahrenheit.pdf` – Gráfico original (em Fahrenheit).
- `icecream_sales_Celsius.pdf` – Gráfico final (com temperatura em Celsius).

---

## 📌 Observações

- O projeto é simples e ideal para quem está iniciando em análise de dados com Python.
- Pode ser facilmente adaptado para outras análises sazonais ou de impacto climático em vendas.

---

## 👨‍🏫 Créditos

Projeto realizado como parte de um curso de introdução à Ciência de Dados com Python.
