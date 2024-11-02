---
title: Life expectancy at birth
description: World Bank, 1960-2022
---

<FlatUiTable
  data={{
    url: 'life_expectancy.csv'
  }}
 />

## Improvement rate by country and area

 <FlatUiTable
  data={{
    url: 'imp_rate_table.csv'
  }}
 />
 
<PlotlyBarChart
  data={{
    url: 'imp_rate.csv'
  }}
  title="Improvement rate by country and region"
  xAxis="Country Code"
  yAxis="Improvement Rate"
/>

<PlotlyLineChart
  data={{
    url: 'china.csv'
  }}
  title="China"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyLineChart
  data={{
    url: 'bhutan.csv'
  }}
  title="Bhutan"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'timor_leste.csv'
  }}
  title="Timor-Leste"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyLineChart
  data={{
    url: 'maldives.csv'
  }}
  title="Maldives"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyLineChart
  data={{
    url: 'oman.csv'
  }}
  title="Oman"
  xAxis="year"
  yAxis="life_exp"
/>
