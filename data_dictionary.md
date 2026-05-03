# Data Dictionary: Integrated Illinois Climate and Severe Weather Events Dataset (2010–2025)

```
| Column Name       | Description                                              | Unit / Format             | Source                 |
|-------------------|----------------------------------------------------------|---------------------------|------------------------|
| STATION           | NOAA station identifier                                  | e.g. USW00094846          | GHCN-Daily             |
| STATION_NAME      | Station name and location                                | Text                      | GHCN-Daily             |
| REGION            | Geographic region of Illinois                            | North / Central / South   | Derived                |
| DATE              | Observation date                                         | YYYY-MM-DD                | Both                   |
| YEAR              | Year                                                     | YYYY                      | Derived                |
| MONTH             | Month                                                    | 1-12                      | Derived                |
| SEASON            | Season                                                   | Winter/Spring/Summer/Fall | Derived                |
| TMAX              | Daily maximum temperature                                | °C (tenths)               | GHCN-Daily             |
| TMIN              | Daily minimum temperature                                | °C (tenths)               | GHCN-Daily             |
| TAVG              | Daily average temperature (calculated as (TMAX+TMIN)/2)  | °C                        | Derived                |
| PRCP              | Daily precipitation                                      | mm                        | GHCN-Daily             |
| SNOW              | Daily snowfall                                           | mm                        | GHCN-Daily             |
| SNWD              | Snow depth                                               | mm                        | GHCN-Daily             |
| COUNTY            | County name                                              | Text                      | Storm Events           |
| STATE             | State name                                               | Text                      | Storm Events           |
| EVENT_TYPE        | Type of severe weather event                             | e.g. Blizzard, Flood      | Storm Events           |
| EVENT_FLAG        | Flag indicating presence of event                        | 0 or 1                    | Derived                |
| DAMAGE_PROPERTY   | Estimated property damage                                | USD                       | Storm Events           |
| DAMAGE_CROPS      | Estimated crop damage                                    | USD                       | Storm Events           |
| INJURIES          | Number of direct injuries                                | Integer                   | Storm Events           |
| DEATHS            | Number of direct deaths                                  | Integer                   | Storm Events           |
```

**Notes:**  
Temperature values are in tenths of degrees Celsius as originally provided by NOAA. Precipitation, snowfall, and snow depth are in millimeters.