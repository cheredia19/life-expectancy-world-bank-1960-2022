---
datapackage:
title: Life expectancy at birth
description: World Bank, 1960-2022
---

<FlatUiTable
  data={{
    url: 'life_expectancy.csv'
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
