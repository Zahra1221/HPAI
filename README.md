# Web-Based Data for Canada on Country- and Regional-Level

In this repository 4 datasets are provided:
- **Canada.csv:** Includes web-based data for Canada on country-level and daily basis. 
- **Western.csv:** Includes web-based data for Western region of Canada (i.e. British Columbia, Alberta, Saskatchewan, Manitoba) on daily basis. 
- **Central.csv:** Includes web-based data for Central region of Canada (i.e. Ontario, Quebec) on daily basis.
- **Atlantic.csv:** Includes web-based data for Western region of Canada (i.e. New Brunswick, Nova Scotia, Prince Edward Island, Newfoundland and Labrador) on daily basis.

Each column of these files are explained below:
- **Date:** The date of the datasets is from November 4th, 2021 to March 31st, 2024 on daily basis.
- **HPAI:** Provides the number of Highly Pathogenic Avian Influenza (HPAI) cases.  [Source](https://www.arcgis.com/apps/dashboards/89c779e98cdf492c899df23e1c38fdbc)
- **GT:** Provides [Google Trends (GT)](https://trends.google.com/trends/explore?date=2021-11-04%202024-03-31&geo=CA&q=%2Fm%2F0292d3&hl=en) for the avian influenza disease topic.
- **GT_1st_Order:** Provides the first derivative of GT for the avian influenza disease topic.
- **GT_2nd_Order:** Provides the second derivative of GT for the avian influenza disease topic.
- **GN:** Provides the number of English and French Google News (GN) articles related to avian influenza, released in Canada. This data was gathered using the [GoogleNews API](https://github.com/Iceloof/GoogleNews) and is only available on country-level.
- **FB:** Provides the volume of Facebook (FB) posts related to avian influenza. This data which was collected using the [FacePager](https://github.com/strohne/Facepager) tool. 
- **Reddit:** Provides the volume of Reddit posts related to avian influenza. This data was gathered using the [pullpush API](https://pullpush.io/maintenance_notice.html).
- **CO:** Provides the concentration of carbon-monoxide. This data was gathered from the [Sentinel-5P](https://developers.google.com/earth-engine/datasets/catalog/sentinel-5p) of Google Earth Engine (GEE). 
- **UV:** Provides the Ultra Vioet (UV) index. This data was gathered from the [Sentinel-5P](https://developers.google.com/earth-engine/datasets/catalog/sentinel-5p) of Google Earth Engine (GEE). 
- **Min_Temperature:** Provides the minimum temperature, and was gathered from [Open-Meteo Historical Weather API](https://open-meteo.com/en/docs/historical-weather-api).
- **GDELT:** Provides the volume of online news articles related to avian influenza. This data which was gathered by scraping the [Global Database of Events, Language, and Tone (GDELT)](https://api.gdeltproject.org/api/v2/summary/summary) platform, is available only on country-level.

