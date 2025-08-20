# 📊 Desafio EBAC - Análise de Dados

Este projeto foi desenvolvido durante um **webinar da EBAC sobre Análise de Dados**, com foco em explorar e responder questões a partir de um dataset de carros.  
Utilizei **Python + Pandas** para manipulação de dados, responder perguntas analíticas e extrair insights relevantes.

---

## 🚀 Desafio proposto

> A partir do dataset fornecido sobre carros, crie um notebook analisando os dados e responda às seguintes perguntas:

---

### 1️⃣ Quais são as variáveis numéricas do dataset?
- **int64**: `Unnamed: 0`, `preco`, `unidades_vendidas`  
- **float64**: `cidade_alcool`, `cidade_gasolina`, `estrada_alcool`, `estrada_gasolina`, `custo_revisao`

---

### 2️⃣ Quais são os 5 carros que mais consomem gasolina na cidade?
**Top 5 modelos com maior consumo (km/l):**
1. Renault Kwid – 15.3  
2. Peugeot 208 – 14.7  
3. Renault Logan – 14.0  
4. Chevrolet Onix Plus – 13.8  
5. Fiat Cronos – 13.8  

---

### 3️⃣ Qual a média de consumo de álcool na cidade e na estrada?
- Cidade: **8.73 km/l**  
- Estrada: **9.90 km/l**

---

### 4️⃣ Crie uma nova coluna contendo o nome da montadora
- Extraí a montadora do campo `modelo`  
- Reorganizei as colunas para melhor visualização  
- Criei uma cópia do DataFrame sem o nome da montadora no `modelo`

---

### 5️⃣ Liste as 5 montadoras com a maior média de preço
1. Nissan – R$ 114.998,50  
2. Chevrolet – R$ 101.001,00  
3. Peugeot – R$ 100.165,00  
4. Volkswagen – R$ 98.111,66  
5. Toyota – R$ 96.208,00  

---

### 6️⃣ Liste os 10 carros com menor custo de manutenção
Exemplo do ranking:
- Hyundai HB20 – R$ 2.946,10  
- Nissan Kicks – R$ 3.006,00  
- Renault Kwid – R$ 3.162,95  
*(lista completa no notebook)*

---

### 7️⃣ Informe o carro mais vendido para cada montadora
Exemplo do ranking:
- Volkswagen Polo – 16.471 unidades  
- Hyundai HB20 – 12.126 unidades  
- Fiat Strada – 10.387 unidades  
- Chevrolet Onix – 10.260 unidades  
*(lista completa no notebook)*

---

### 8️⃣ Super Desafio: Criação de coluna `custo_total`
Com base em:
- Consumo de gasolina em 2 anos (150L/mês, R$ 5,50/L)  
- IPVA de 4% ao ano sobre o preço do carro  
- Revisão 1x por ano  

**Top 5 carros com maior custo em 2 anos:**
1. VW T-Cross – R$ 63.455,20  
2. Peugeot 208 – R$ 61.061,20  
3. VW Saveiro – R$ 60.363,20  
4. Chevrolet Onix Plus – R$ 58.766,88  
5. Fiat Fastback – R$ 58.662,96  

**Top 5 carros com menor custo em 2 anos:**
1. Renault Kwid – R$ 37.865,56  
2. Hyundai HB20 – R$ 38.222,96  
3. Hyundai HB20S – R$ 38.771,92  
4. Fiat Mobi – R$ 39.820,24  
5. VW Polo – R$ 40.465,08  

---

## 🛠️ Tecnologias utilizadas
- Python 3.13  
- Jupyter Notebook  
- Pandas  
- OpenPyXL  

---

## 📚 Aprendizados e Habilidades

Durante o webinar da EBAC, desenvolvi e pratiquei as seguintes competências:

- Manipulação de planilhas Excel com **Pandas** (`read_excel`, `dtypes`, `sort_values`, `groupby`).
- Análise exploratória de dados: identificação de variáveis numéricas, médias e rankings.
- Criação de novas colunas a partir de cálculos e manipulação de strings.
- Uso de funções como `mean()`, `round()`, `idxmax()`, `head()`.
- Manipulação de strings para separar montadora e modelo.
- Estruturação de um **notebook limpo e organizado**, com código e explicações em cada etapa.
- Interpretação dos resultados em formato de **insights acionáveis** (consumo, custos e vendas).

---

## 📂 Dataset
- Fornecido pela EBAC durante o webinar.  
- Contém informações sobre preço, consumo, custo de manutenção e vendas de diferentes modelos de carros.  

---

## 🔗 Links
- 📘 [Notebook no GitHub](./notebook.ipynb)  
- 💼 [Meu LinkedIn](www.linkedin.com/in/thiago-lopes-front-end)  

---

✨ Este projeto foi um grande passo para consolidar minhas habilidades em análise de dados e me motivou a continuar explorando **Python + Pandas** para extrair insights reais de datasets.  
