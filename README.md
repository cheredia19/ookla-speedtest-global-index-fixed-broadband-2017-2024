---
title: Ookla Speedtest Global Index (2017-2024)
description: 
---

<FlatUiTable
  data={{
    url: 'fb_historical.csv'
  }}
/>

## Percentage change between the most recent and the oldest reported mbps speed by country

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
