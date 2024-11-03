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

## Countries with the greatest improvement in life expectancy

<PlotlyBarChart
  data={{
    url: 'china.csv'
  }}
  title="China"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
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

<PlotlyBarChart
  data={{
    url: 'maldives.csv'
  }}
  title="Maldives"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'oman.csv'
  }}
  title="Oman"
  xAxis="year"
  yAxis="life_exp"
/>

## Life expectancy by groups

### Global

<PlotlyBarChart
  data={{
    url: 'world.csv'
  }}
  title="World"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'oecd_members.csv'
  }}
  title="OECD Members"
  xAxis="year"
  yAxis="life_exp"
/>

### By region

<PlotlyBarChart
  data={{
    url: 'afe.csv'
  }}
  title="Africa Eastern and Southern"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'afw.csv'
  }}
  title="Africa Western and Central"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'arb.csv'
  }}
  title="Arab World"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'ceb.csv'
  }}
  title="Central Europe and the Baltics"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'eas.csv'
  }}
  title="East Asia & Pacific"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'ecs.csv'
  }}
  title="Europe & Central Asia"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'emu.csv'
  }}
  title="Euro area"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'euu.csv'
  }}
  title="European Union"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'lcn.csv'
  }}
  title="Latin America & Caribbean"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'mea.csv'
  }}
  title="Middle East & North Africa"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'nac.csv'
  }}
  title="North America"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'sas.csv'
  }}
  title="South Asia"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'ssf.csv'
  }}
  title="Sub-Saharan Africa"
  xAxis="year"
  yAxis="life_exp"
/>

### By income level

<PlotlyBarChart
  data={{
    url: 'hic.csv'
  }}
  title="High income"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'umc.csv'
  }}
  title="Upper middle income"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'mic.csv'
  }}
  title="Middle income"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'lmc.csv'
  }}
  title="Lower middle income"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'lmy.csv'
  }}
  title="Low & middle income"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'lic.csv'
  }}
  title="Low income"
  xAxis="year"
  yAxis="life_exp"
/>

### Small states

<PlotlyBarChart
  data={{
    url: 'sst.csv'
  }}
  title="Small States"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'css.csv'
  }}
  title="Caribbean Small States"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'pss.csv'
  }}
  title="Pacific Island Small States"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'oss.csv'
  }}
  title="Other Small States"
  xAxis="year"
  yAxis="life_exp"
/>

### Groups in sensitive situations

<PlotlyBarChart
  data={{
    url: 'fcs.csv'
  }}
  title="Fragile and conflict affected situations"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'hpc.csv'
  }}
  title="Heavily indebted poor countries (HIPC)"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'ldc.csv'
  }}
  title="Least developed countries: UN classification"
  xAxis="year"
  yAxis="life_exp"
/>

### Groups excluding high income

<PlotlyBarChart
  data={{
    url: 'eap.csv'
  }}
  title="East Asia & Pacific"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'eca.csv'
  }}
  title="Europe & Central Asia"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'lac.csv'
  }}
  title="Latin America & Caribbean"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'mna.csv'
  }}
  title="Middle East & North Africa"
  xAxis="year"
  yAxis="life_exp"
/>

<PlotlyBarChart
  data={{
    url: 'ssa.csv'
  }}
  title="Sub-Saharan Africa"
  xAxis="year"
  yAxis="life_exp"
/>
