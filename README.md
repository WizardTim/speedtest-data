# speedtest-data
2.94 years of half hourly speed tests for a Telstra residential cable internet connection in Brisbane, Australia (EuroDOCSIS 3.0).

Data has 84.6% coverage, 15.4% is missing due to server downtime, failed tests, blackouts, internet outages and collection tool failures.

Data gathered using Ookla® [speedtest.net](https://www.speedtest.net/) services.

| Date Commenced       | Collection Tool                                               |
|----------------------|---------------------------------------------------------------|
| 2017-10-14T09:30:01Z | [sivel/speedtest-cli](https://github.com/sivel/speedtest-cli) |
| 2020-01-20T08:30:01Z | Ookla® Speedtest® CLI                                         | 

| Date Commenced       | Active Service                                      |
|----------------------|-----------------------------------------------------|
| 2017-10-14T09:30:01Z | Telstra Cable Broadband (Standard Speed Tier)       |
| 2019-05-03T01:00:00Z | Telstra x NBN Co. HFC (100 Premium Speed Tier)      |

---

### Data Visualized
![Whole Dataset Times Series Plot](/doc/summary.png)
![Time of Day Download Heatmap](/doc/download_heatmap_1.png)
![Time of Day Upload Heatmap](/doc/upload_heatmap_1.png)

---

### Example Data Snippet (2 of 43,620)
| datetimestart        | datetimestop         | servername         | serverid | latency | jitter | packetloss | download | upload  | downloadbytes | uploadbytes |
|----------------------|----------------------|--------------------|----------|---------|--------|------------|----------|---------|---------------|-------------|
| 2020-03-11T03:00:01Z | 2020-03-11T03:00:16Z | Telstra - Brisbane | 2604     | 7.869   | 0.2    | 0          | 11130794 | 4696348 | 62641392      | 17891488    |
| 2020-03-11T03:30:01Z | 2020-03-11T03:30:14Z | AARNet - Brisbane  | 6119     | 8.178   | 2.081  | 0          | 11929526 | 4701399 | 75245320      | 16982144    |

---
### Units
| datetimestart / datetimestop   | servername | serverid | latency | jitter | packetloss | download | upload  | downloadbytes | uploadbytes |
|--------------------------------|------------|----------|---------|--------|------------|----------|---------|---------------|-------------|
| ISO8601 (YYYY-MM-DDThh:mm:ssZ) | string     | ID       | ms      | ms     | percent    | bytes/s  | bytes/s | bytes         | bytes       |
