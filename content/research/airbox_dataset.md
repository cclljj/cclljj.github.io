---
title: "AirBox Dataset"
date: 2022-05-23T01:33:29+08:00
---

We provide the sample dataset of the AirBox project ([https://pm25.lass-net.org/](https://pm25.lass-net.org/)). The project was inspired by the work of the Location Aware Sensing System (LASS) community, which engages citizens to participate in the PM2.5 sensing project and enables them to make low-cost PM2.5 sensing devices on their own. It also facilitates PM2.5 monitoring at a finer spatio-temporal granularity and enriches environmental data analysis by making all measurement data freely available to everyone. Till 2017/08, there have been more than 3,500 AirBox devices deployed in 30 countries worldwide.

### Description

Each sample dataset is a CSV (or zipped CSV) file that contains measurements of timestamp, GPS coordinates, temperature, relative humidity, PM1, PM2.5, and PM10 of AirBox devices in Taiwan in the given period. The detailed hardware information is below:

-   Device: [Edimax AirBox](https://www.edimax.com/edimax/merchandise/merchandise_detail/data/edimax/global/air_quality_monitoring_semioutdoor/ai-1001w_v2/) AI-1001W V1 and V2
    -   Temperature/Humidity sensor: HTS221
    -   PM1/2.5/10 sensor: Plantower PMS5003
    -   Sample rate: every 5-6 minutes

Note that, some AirBox devices are using the old version firmware that does not provide PM1/PM10 measurement results. Moreover, due to different reasons, disconnection and reconnection are frequent in the dataset, and missing data is common for all the AirBox devices.

### Download

Note that this dataset is released for research institutes and non-profit organizations only. If you are from industry or plan to use this dataset for commercial purposes, you are **NOT** eligible to download this dataset, and please go to [this page](https://airbox.edimaxcloud.com/join) for more detailed information.

-   January 2017, Taiwan: [[.csv](https://goo.gl/2P45kA)] [[.tgz](https://goo.gl/CfYwmT)]
-   February 2017, Taiwan: [[.csv](https://goo.gl/xUf4iv)] [[.tgz](https://goo.gl/mgtq1F)]
-   March 2017, Taiwan: [[.csv](https://goo.gl/KqCTpu)] [[.tgz](https://goo.gl/noACwQ)]

If you are interested in accessing real-time AirBox data, please refer to the "API" session on the [PM2.5 Open Data Portal](https://pm25.lass-net.org/) website.

### How to cite this dataset?

-   Please explicitly acknowledge the data source, [Edimax Inc](http://www.edimax.com/)., when presenting the dataset (and any outcomes based on this dataset) in any formats.
-   When writing papers that use AirBox dataset, we would highly appreciate if you could cite the dataset by adding this citation to your papers:
    -   `Ling-Jyh Chen, Yao-Hua Ho, Hu-Cheng Lee, Hsuan-Cho Wu, Hao-Min Liu, Hsin-Hung Hsieh, Yu-Te Huang, and Shih-Chun Candice Lung. An Open Framework for Participatory PM2.5 Monitoring in Smart Cities. IEEE Access Journal, volume 5, pp. 14441-14454, July, 2017.`
    -   The paper is also available for open access and download at [http://dx.doi.org/10.1109/ACCESS.2017.2723919](http://dx.doi.org/10.1109/ACCESS.2017.2723919)
        

### Acknowledgement

We wish to thank the [Edimax Inc](http://www.edimax.com/)., the [LASS community](https://www.facebook.com/groups/LASSnet/) and [Academia Sinica](https://www.sinica.edu.tw/) for their support, technical advice and administrative assistance. This research was supported in part by the Ministry of Science and Technology of Taiwan and Academia Sinica under Grants: MOST 105-2221-E-001-016-MY3, MOST 105-3011-F-001-002, MOST 106-3114-E-001-004 and AS-104-SS-A02.
