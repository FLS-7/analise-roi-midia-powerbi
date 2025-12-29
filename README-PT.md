# Análise ROI de Mídia com Power BI

![Status](https://img.shields.io/badge/status-concluído-brightgreen)

> Projeto de portfólio que demonstra a criação de um dashboard executivo para análise de Retorno Sobre o Investimento (ROI) em diferentes canais de marketing.

![Dashboard de Análise de ROI](https://i.imgur.com/hKIlbl3.png)

---

## 🎯 Problema de Negócio

A diretoria de uma empresa precisava de clareza sobre a eficácia de seus investimentos em publicidade, que eram historicamente alocados com base na tradição, e não em dados. O objetivo deste projeto foi responder às seguintes perguntas de negócio:

*   Qual é a relação entre o investimento em cada canal de mídia (TV, Rádio, Jornal) e as vendas?
*   Qual canal é o mais eficiente em gerar retorno e qual é o menos eficiente?
*   Como o orçamento de marketing deve ser realocado para maximizar as vendas futuras?

---

## 📊 Fonte de Dados

Os dados utilizados neste projeto são um conjunto de dados públicos clássicos sobre publicidade, contendo os investimentos em três canais de mídia distintos e as vendas resultantes. O dataset está disponível no Kaggle.

*   **Link para os dados:** [Advertising Kaggle Dataset](https://www.kaggle.com/datasets/ashydv/advertising-dataset)

---

## 🛠️ Ferramentas Utilizadas

*   **Microsoft Power BI:** Ferramenta principal para ETL, modelagem, criação de medidas e visualização de dados.
*   **DAX (Data Analysis Expressions):** Utilizada para a criação das métricas e KPIs principais, como:
    *   `Investimento Total`
    *   `Total Vendas`
    *   `Custo por Venda`
*   **Power Query:** Utilizado para a ingestão e verificação da qualidade dos dados.

---

## 💡 Análise, Insights e Recomendações

A análise do dashboard permitiu a extração de insights acionáveis que podem guiar a estratégia de marketing da empresa de forma muito mais eficiente.

### 1. TV: O Motor Principal de Vendas
*   **Insight:** O gráfico de dispersão revela uma **forte e clara correlação positiva** entre o investimento em TV e as vendas. A linha de tendência ascendente mostra que, de forma consistente, quanto mais se investe em TV, mais as vendas aumentam.
*   **Recomendação:** Manter a TV como o pilar da estratégia de mídia e o principal canal para investimentos robustos, dado seu retorno previsível e de grande escala.

### 2. Jornal: O Canal Ineficaz
*   **Insight:** A análise mostra uma **correlação muito fraca ou nula** entre os gastos com publicidade em jornais e as vendas. A nuvem de pontos é extremamente dispersa e a linha de tendência é quase plana, indicando que aumentar o orçamento neste canal não gera um aumento significativo ou confiável nas vendas.
*   **Recomendação Estratégica:** **Reavaliar completamente o orçamento de Jornal.** Sugere-se a realocação de 90% a 100% desta verba para canais com performance comprovadamente superior (TV e Rádio), a fim de evitar o desperdício de recursos e maximizar o ROI total.

### 3. Rádio: A Oportunidade Oculta
*   **Insight:** Apesar de receber a menor fatia do investimento total (aproximadamente 11%), o Rádio apresenta uma **correlação positiva e mais forte que a do Jornal**. Isso indica que, embora em menor escala que a TV, o Rádio é um canal eficiente.
*   **Recomendação:** O Rádio representa a maior **oportunidade de crescimento otimizado**. Recomenda-se aumentar experimentalmente o investimento neste canal, utilizando parte da verba realocada do Jornal. É provável que o Rádio gere um retorno sobre o investimento superior ao que é observado atualmente.

---

## 🖱️ Interatividade do Dashboard

O dashboard conta com **filtros interativos (sliders)** para cada um dos três canais de mídia. Esta funcionalidade permite que a diretoria e os gestores de marketing explorem diferentes cenários de investimento em tempo real, observando o impacto direto no total de vendas e no custo por venda para diferentes faixas de orçamento.

---

## 👨‍💻 Autor

*   **[Flávio Sales]**
*   **LinkedIn:** [https://www.linkedin.com/in/flávio-sales-a67663266/](https://www.linkedin.com/in/flávio-sales-a67663266/)
*   **GitHub:** [https://github.com/FLS-7](https://github.com/FLS-7)
