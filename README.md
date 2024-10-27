---
title: Ookla Speedtest Global Index (2017-2024)
description: 
---

> **DISCLAIMER:** This report is intended just for exploring the DataHub platform functionalities, **not** for any commercial use. All the data used in this note is property of Ookla, LLC.

In this rapidly evolving digital world, the Internet has become an essential part of our lives, powering everything from work and education to healthcare, entertainment, and social interactions. 

As we approach [International Internet Day](https://knowledgeflow.org/event/international-internet-day-2024/) on October 29, this is an ideal moment to reflect on how this transformative technology has reshaped society and continues to be a driving force behind innovation, connectivity, and access to information. 

From streamlining communication across continents to enabling real-time access to vast knowledge resources, the Internet is a cornerstone of modern life, impacting individuals and industries. 

Under that premise, at **DataHub** we analyzed the evolution of countries in terms of their connection speed, based on data from almost 200 countries that Ookla has collected since 2017 with its **Speedtest Global Index**.

Of 183 countries, **the Internet speed of 164 nations in 2024 is better than in 2017**, some with **remarkable upgrades**. In other words, 90% improved their download velocity during that span.

The table below shows a snapshot of the countries' Internet speeds from 2017 to 2024, taken every August. Users can filter data by major areas (continents), regions (based on the [United Nations definition of regions](https://population.un.org/wpp/DefinitionOfRegions/)), and the mentioned speeds in Mbps since 2017. 

<FlatUiTable
  data={{
    url: 'fb_historical.csv'
  }}
/>

## Percentage change between the most recent and the oldest reported Mbps speed by country

According to the numbers, the country that has progressed the most is **Venezuela**. The South American outlet was the world's worst-ranked by September 2017 (3.42 Mbps). However, its Internet download speed has improved 1,648.8 %. In August 2024, Venezuela ranked 90th  (61.95 Mbps), thanks to the recent investment from optical fiber private ISPs. 

Apart from Venezuela, eight States (four from Latin America and the Caribbean) improved their download velocity by more than 1,000 percent: **Egypt**, neighbors **Colombia**, **Kuwait**, **Paraguay**, **Costa Rica**, **Uzbekistan**, **United Arab Emirates**, and **Peru**.

Nineteen countries have lower Internet speeds than in 2017 or 2018, the majority from Asia and Africa.

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

But something happened, arguably thanks to the impact of the [COVID-19](https://www.mayoclinic.org/diseases-conditions/coronavirus/symptoms-causes/syc-20479963) pandemic. One hundred and forty-seven out of 179 countries (82.12%) **decreased their download Internet speed in 2022 compared to 2021**. 

It's remarkably evident when looking at each country's timeline.

The download Internet velocity progress of only 32 countries (fifteen from Latin America and the Caribbean, nine from Africa, and eight from Asia) was not interrupted.

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

## Links

- [Ookla SGI fixed broadband 2017-24 (general insights)](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-2024)

- [Australia and New Zealand](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-aus-nz)

- [Caribbean](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-cb)

- [Central America](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-cent-am)

- [Central Asia](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-cent-as)

- [Eastern Africa](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-east-af)

- [Eastern Asia](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-east-as)

- [Eastern Europe](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-east-eu)

- [Micronesia](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-mcn)

- [Middle Africa](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-mid-af)

- [Melanesia](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-mln)

- [Northern Africa](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-nor-af)

- [Northern America](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-nor-am)

- [Northern Europe](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-nor-eu)

- [South-Eastern Asia](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-se-as)

- [Southern Africa](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-sou-af)

- [South America](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-sou-am)

- [Southern Asia](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-sou-as)

- [Southern Europe](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-sou-eu)

- [Western Asia](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-west-as)

- [Western Africa](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-west-af)

- [Western Europe](https://datahub.io/@cheredia19/ookla-sgi-broadband-2017-24-west-eu)

- [Ookla Speedtest Global Index Insights](https://datahub.io/@cheredia19/ookla-speedtest-global-index-insights)
