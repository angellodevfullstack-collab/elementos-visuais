# 📊 Análise dos Impulsionadores do Limite de Crédito  
Projeto desenvolvido como entrega para o curso de Ciência de Dados.

---

## 📘 Objetivo da Atividade

A atividade consiste em analisar um conjunto de dados contendo informações pessoais, profissionais e financeiras de um grupo de indivíduos, com o objetivo de identificar **quais fatores estão mais associados a limites de crédito elevados**.

Foi solicitado que:

- Os alunos explorassem o conjunto de dados;
- Gerassem **diversos gráficos durante a exploração**;
- Selecionassem **apenas os 3 gráficos mais assertivos** para apresentação final;
- Justificassem suas escolhas com base nos insights obtidos.

---

## 🧩 Estrutura dos Dados

O DataFrame contém as seguintes colunas:

- **Nome**
- **Idade**
- **Profissão**
- **Salário**
- **Limite de Crédito**
- **Histórico de Inadimplência**
- **Estado Civil**
- **Imóvel Próprio**

Essas variáveis permitem analisar aspectos como renda, estabilidade, risco e perfil socioeconômico — todos relevantes para determinar limites de crédito.

---

## 📊 Gráficos Escolhidos e Justificativas

Após a análise exploratória, foram escolhidos **3 gráficos principais**, por se mostrarem os mais relevantes para identificar os impulsionadores do limite de crédito. Abaixo estão os visuais e suas justificativas.

---

### ⭐ 1. Relação entre Salário e Limite de Crédito (Scatter Plot)

Este gráfico evidencia claramente a tendência natural de que indivíduos com **salários mais altos tendem a possuir limites de crédito maiores**.

#### **Por que esse gráfico foi escolhido?**

- Mostra a relação mais direta e intuitiva do dataset.
- Exibe uma correlação positiva clara.
- Identifica que o salário é o **principal impulsionador** do limite de crédito.
- É útil para instituições financeiras verificarem se a concessão está alinhada com a capacidade de renda.

---

### ⭐ 2. Limite de Crédito Médio por Profissão (Bar Plot)

Profissões estão diretamente relacionadas a estabilidade financeira, nível salarial e risco. Para analisar esse impacto, foi gerado um gráfico de barras com o limite médio por categoria.

#### **Por que esse gráfico foi escolhido?**

- Categorias profissionais exibem fortes diferenças entre si.
- Profissões como **Médico** apresentam limites significativamente maiores.
- Ajuda a entender como o mercado de crédito utiliza perfis profissionais para ajustar limites.

Esse visual reforça que **profissão é um fator importante**, pois reflete rendimento e estabilidade.

---

### ⭐ 3. Impacto do Imóvel Próprio no Limite de Crédito (Bar Plot)

Possuir imóvel próprio é um indicador de patrimônio e menor risco. Esse gráfico compara o limite médio entre quem possui e quem não possui.

#### **Por que esse gráfico foi escolhido?**

- A diferença entre as médias é bastante significativa.
- Indivíduos com imóvel próprio recebem limites muito maiores.
- Esse comportamento é consistente com o modelo tradicional de análise de risco bancário.

---

## 🧠 Conclusões da Análise

Com base nos gráficos selecionados, os fatores que mais influenciam um limite de crédito elevado são:

1. **Salário** — o fator mais diretamente relacionado ao limite.
2. **Profissão** — categorias profissionais de maior renda apresentam limites superiores.
3. **Imóvel Próprio** — indicador de estabilidade e patrimônio, reduz risco e eleva o limite.

Outros fatores, como idade, estado civil e histórico de inadimplência, tiveram impacto menor no conjunto específico analisado (possivelmente pela amostra reduzida).

---

## 🧪 Código Utilizado

O código completo para geração do DataFrame e produção dos gráficos está disponível no arquivo:

