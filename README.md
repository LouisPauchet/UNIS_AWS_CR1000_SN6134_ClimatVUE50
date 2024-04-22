# Logger programme and AWS information

## Station Location and description

The mast is located behind the longyearbyen school at 78.21281°N 15.61222°E.
The station use at support the weather mast from Met Norway SN99857.

---
## History

| Time (UTC)       | Operator     | Information                       | Data | Pictures |
|------------------|--------------|-----------------------------------|------|----------|
|2024-04-05 12:10  | Louis UNIS   | Arriving on the station site      ||
|2024-04-05 13:05  | Louis UNIS   | Station up and running            ||[AWS01](/pictures/AWS01.jpg) [AWS02](/pictures/AWS02.jpg) [AWS03](/pictures/AWS03.jpg) [AWS04](/pictures/AWS04.jpg) [AWS05](/pictures/AWS05.jpg)|
|2024-04-05 13:10  | Louis UNIS   | Leaving area                      ||
|2024-04-18 12:15  | Louis UNIS   | Arriving on the station site      ||
|2024-04-18 12:25  | Louis UNIS   | Data collection                   |[20240418 Data Access](/data/20240418)|
|2024-04-18 12:40  | Louis UNIS   | Leaving area                      ||



---
### Logging informations

The data logger sample interval is **10s** which is then use in the logging tables as presented bellow.

---
## Data description

| Field         | Unit          | Table logging |
|---------------|---------------|---------------|
|TIMESTAMP      |Timestamp (UTC)| 1min & 1h interval|
|RECORD         |Number||
|SlrFD_W_Avg    |W/m^2|Average|
|Rain_mm_Tot    |mm|Total|
|WS_ms_S_WVT    |m/s|Wind Vector|
|WindDir_D1_WVT |Deg|Wind Vector|
|WindDir_SD1_WVT|Deg|Wind Vector|
|MaxWS_ms_Max   |m/s|Maximum|
|AirT_C_Avg     |°C|Average|
|VP_mbar_Avg    |mbar|Average|
|BP_mbar_Avg    |mbar|Average|
|RH             |%|Sample
|RHT_C_Avg      |°C|Average|
|TiltNS_deg_Avg |Deg|Average|
|TiltWE_deg_Avg |Deg|Average|
|CVMeta         ||Sample|
