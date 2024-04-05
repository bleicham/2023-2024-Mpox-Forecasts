# Real-time forecasting of two waves of Mpox (Summer 2023 and Spring 2024) on different spatial scales 

This repository contains forecasts for the Summer 2023 wave of the mpox epidemic in the United States, Brazil, China, Colombia, England, Japan, Mexico, Peru, South Korea, Thailand, and the World and for the Spring 2024 wave in the United States. 

# Summer 2023 Wave 
For the Summer 2023 forecasts, we primarily employ three modeling techniques: (1) Facebook's Prophet model [1], (2) spatial-wave framework [2], and (3) the ensemble n-sub-epidemic framework [3] to produce 4-week out forecasts. We calibrated each model with the most recent ten weeks of data, and the data associated with each folder is the last week of data used as part of the calibration period. We also forecasted the effective reproduction number (Rt) [4] for each area, using 10- and 20-week calibration periods and forecasting four weeks at a time. Data for the US-CDC was obtained from [5] and the remaining countries from [6]. 

# Spring 2024 Wave
For the Spring 2024 wave in the US, we utilized the same modeling techniques, calibration periods, and forecasting horizons as employed during the Summer 2023 wave but now include auto-regressive integrated moving average models (ARIMA), simple linear regression (SLR), and generalized additive models (GAM). Additional details on the model specification and application can be found in [7]. Data was obtained weekly from the Centers for Disease Control and Prevention Nationally Notifiable Infectious Diseases and Conditions Weekly Tables [8]. 

Our website [9] is also updated weekly with the most recent ARIMA and ensemble sub-epidemic forecasts for the United States. 

# Additional Resources 
[1] Taylor SJ, Letham B. Forecasting at scale. The American Statistician. 2018 Jan 2;72(1):37-45.

[2] https://github.com/gchowell/spatial_wave_subepidemic_framework

[3] Chowell G, Dahal S, Bleichrodt A, Tariq A, Hyman JM, Luo R. SubEpiPredict: A tutorial-based primer and toolbox for fitting and forecasting growth trajectories using the ensemble n-sub-epidemic modeling framework. Infect Dis Model. 2024 Feb 9;9(2):411-436. doi: 10.1016/j.idm.2024.02.001. PMID: 38385022; PMCID: PMC10879680.

[4] Chowell G, Bleichrodt A, Dahal S, Tariq A, Roosa K, Hyman JM, Luo R. GrowthPredict: A toolbox and tutorial-based primer for fitting and forecasting growth trajectories using phenomenological growth models. Sci Rep. 2024 Jan 18;14(1):1630. doi: 10.1038/s41598-024-51852-8. PMID: 38238407; PMCID: PMC10796326.

[5] https://www.cdc.gov/poxvirus/mpox/response/2022/mpx-trends.html

[6] Edouard Mathieu, Fiona Spooner, Saloni Dattani, Hannah Ritchie and Max Roser (2022) - “Mpox” Published online at OurWorldInData.org. Retrieved from: 'https://ourworldindata.org/mpox' [Online Resource]

[7] Bleichrodt A, Luo R, Kirpich A, Chowell G. Retrospective evaluation of short-term forecast performance of ensemble sub-epidemic frameworks and other time-series models: The 2022-2023 mpox outbreak across multiple geographical scales, July 14th, 2022, through February 26th, 2023. medRxiv [Preprint]. 2023 Oct 17:2023.05.15.23289989. doi: 10.1101/2023.05.15.23289989. PMID: 37905035; PMCID: PMC10615009.

[8] https://wonder.cdc.gov/nndss/nndss_weekly_tables_menu.asp

[9] https://publichealth.gsu.edu/research-outreach/monkeypox-forecasting-center/

#
Last Updated: 4/5/2024 
