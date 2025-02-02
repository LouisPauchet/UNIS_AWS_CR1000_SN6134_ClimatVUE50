# Logger programme and AWS information

## Station Location and description

The mast is located behind the longyearbyen school at 78.21281°N 15.61222°E.
The station use as support the weather mast from Met Norway SN99857.

---
## History

| Time (UTC)       | Operator     | Information                       | Data | Pictures |
|------------------|--------------|-----------------------------------|------|----------|
|2024-04-05 12:10  | Louis UNIS   | Arriving on the station site      ||
|2024-04-05 13:05  | Louis UNIS   | :white_check_mark: Station up and running            ||:link:[20240405](/pictures/20240405)|
|2024-04-05 13:10  | Louis UNIS   | Leaving area                      ||
|2024-04-18 12:15  | Louis UNIS   | Arriving on the station site      ||
|2024-04-18 12:25  | Louis UNIS   | :chart: Data collection                   |:link:[20240418 Data Access](/data/20240418)|
|2024-04-18 12:40  | Louis UNIS   | Leaving area                      ||
|2024-05-03 13:33  | Louis UNIS   | Arriving in the area              ||
|2024-05-03 13:34  | Louis UNIS   | :chart: Data collection                   |:link:[20240503 Data Access](/data/20240503)|
|2024-05-03 13:40  | Louis UNIS   | :red_circle: Data logger off                   ||:link:[20240405](/pictures/20240503)
|2024-05-03 13:46  | Louis UNIS   | Leaving area                      ||
|2024-05-15 10:30  | Louis UNIS   | Arriving on the station site and deploying the new logger box                       ||
|2024-05-15 11:03  | Louis UNIS   | :white_check_mark: Station running                       ||
|2024-05-15 11:11  | Louis UNIS   | Leaving the area                       ||
|2024-07-04 14:00  | Louis UNIS   | Arriving on the station site and trying to connect to the data logger without succes                       ||
|2024-07-04 14:30  | Louis UNIS   | Leaving the area                       ||
|2024-07-16 15:20  | Louis UNIS   | Arriving on the station site                      ||
|  |   | Replacing the power supply to connect on the 12V of the main mast                      ||
|  |   | Trying to connect to the data logger unsuccesfully                      ||
|  |   | Replacing the battery of the 2  Netatno sensors                      ||
|2024-07-16 17:00  | Louis UNIS   | Leaving the area                       ||

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
