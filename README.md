---
title: Ookla Speedtest Global Index (2017-2024)
description: 
---

<FlatUiTable
  data={{
    url: 'fb_historical.csv'
  }}
/>

## Percentage change between the most recent and the oldest reported Mbps speed by country

<FlatUiTable
  data={{
    url: 'change_2017_24.csv'
  }}
/> 

<PlotlyBarChart
  data={{
    url: 'change_2017_24.csv'
  }}
  title="Percentage change"
  xAxis="country"
  yAxis="change_2017_24"
/>

## Percentage change between the 2021-22 reported Mbps speed by country

<FlatUiTable
  data={{
    url: 'change_2021_22.csv'
  }}
/> 

<PlotlyBarChart
  data={{
    url: 'change_2021_22.csv'
  }}
  title="Percentage change"
  xAxis="country"
  yAxis="change_2021_22"
/>

