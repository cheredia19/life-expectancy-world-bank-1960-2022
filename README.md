---
title: Life expectancy at birth has improved all over the world
description: According to the World Bank data, from 1960 to 2022
author: César Heredia, data journalist
---

<br />

Over the past six decades, **life expectancy at birth** has shown remarkable improvement worldwide, underscoring advancements in healthcare, living conditions, and disease prevention. 

According to data from the World Bank, this value has steadily increased globally from 1960 to 2022, **moving from 50.9 years in 1960 to 72 years in 2022**, a **41.5 percent improvement in 62 years**, reflecting enhanced quality of life and medical progress on a global scale.

<PlotlyBarChart
  data={{
    url: 'world.csv'
  }}
  title="World"
  xAxis="year"
  yAxis="life_exp"
/>

All countries, regions, and areas recorded a rise in life expectancy at birth in this period except one.

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

Five countries doubled their expectation of life at birth: two from East Asia and the Pacific, two from South Asia, and one from the MENA region (a special mention to Mali (99.7%), a Sub-Saharan African nation).

**China's life expectancy at birth** was 33.3 years in 1960. In just two years, it rose 52.5% to reach 50.8 years. Although growth has slowed since then, it has been steady year by year, reaching 78.6 years for those born in 2022. From 1960 to 2022, the expectation of life in China increased by 136.2%, the highest among the listed countries.

<PlotlyBarChart
  data={{
    url: 'china.csv'
  }}
  title="China"
  xAxis="year"
  yAxis="life_exp"
/>

The increase in life expectancy at birth in **Bhutan** has been constant since 1960. Just a minimum decrease (0.2 years) for those born in 2000 compared to 1999. It's the second country with the highest value.

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

Until 2019, life expectancy at birth in **Ukraine** grew, like every other nation. Since then, it has dropped by 3.2 years. Although it is not the subject of this article, the decline might be attributed to the COVID-19 pandemic and the ongoing armed conflict with Russia.

<PlotlyBarChart
  data={{
    url: 'ukraine.csv'
  }}
  title="Ukraine"
  xAxis="year"
  yAxis="life_exp"
/>

## Life expectancy at birth by country and area (1960-2022)

<FlatUiTable
  data={{
    url: 'life_expectancy.csv'
  }}
 />

## Life expectancy by groups

### Global

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
