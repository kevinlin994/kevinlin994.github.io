---
layout: post
title: WomenTechWomenYes Project!
---
The Benson Project was the first assignemnt I completed at Metis! We worked in groups of four to help Women Tech Women Yes, a new and inclusive orginzation, spread word of their upcoming gala. Their mission was to spread awareness of their cause and to also garner interest of individuals already familiar with the tech industry. Since they are located in New York City we used the publicly available mta subway data to narrow down specific subway stations their volunteers could effectively collect email addresses from people interested in their orginization and gala.  <br/><br/>
To help them throw a successful gala, we downloaded four months of turnstile data and started our analysis. This data contains the cumulative entry and exit numbers of each unique turnstile from every subway station in New York. The entry and exit numbers are updated every four hours. We processed the data by first finding the difference in entry and exit numbers for every four hour interval of each unique turnstile. This gave us the total number of entries and exits each turnstile had every four hours. We then summed these totals in order to determine total overall traffic and also average traffic for each station. With this data we could recommend that WTWY send volunteers to the stations with highest traffic to quickly spread awareness for their event. Additionally, we researched the locations of large tech companies that were close to the busiest stations. This would increase the chance that people working in technology would be reached. <br/><br/>
I used python and python libraries to complete this project. These include: NumPy, matplotlib, seaborn, and pandas.<br/><br/>
Future work that I could add to improve my final recommendation would be to gather the demographic data of the neighborhoods where the stations are located. Combining this data with my existing data would allow me to have a better criteria to choose which stations to gather emails from.



