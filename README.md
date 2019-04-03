# speedtest-data
Half hourly speed tests for a Telstra residential cable internet connection in Brisbane, Australia (EuroDOCSIS 3.0).

Data gathered using Ookla® [speedtest.net](speedtest.net) services.

### Data Visualized
![alt text](/doc/summary.png)

---

### Example Data Snippet (4 of 23,654)
datetimestart	| datetimestop	| provider	| server	| distance	| ping	| download	| upload
--- | --- | --- | --- | --- | --- | --- | --- |
2017-10-13 23:30:01 | 2017-10-13 23:30:29 | Telstra Internet | Internode (Brisbane) | 5.31 | 19.176 | 32.37 | 1.11
2017-10-14 00:30:01 | 2017-10-14 00:30:39 | Telstra Internet | Internode (Brisbane) | 5.31 | 16.438 | 28.53 | 1.12
2017-10-14 01:00:01 | 2017-10-14 01:00:39 | Telstra Internet | Telstra (Brisbane) | 5.31 | 14.102 | 33.92 | 1.15
2017-10-14 01:30:01 | 2017-10-14 01:30:25 | Telstra Internet | Telstra (Brisbane) | 5.31 | 16.754 | 34.32 | 1.36

---
### Units
datetimestart	/ datetimestop	| provider	| server	| distance	| ping	| download	| upload
--- | --- | --- | --- | --- | --- | --- |
YYYY-MM-DD hh:mm:ss AEST  | string | string | km | ms | Mbps | Mbps |
