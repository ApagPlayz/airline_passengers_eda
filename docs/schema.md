# Data Dictionary: Airline Activity

| Column Name                  | Description                                                                                  |
|------------------------------|----------------------------------------------------------------------------------------------|
| Activity Period              | Year and month of activity, formatted YYYYMM (e.g., 202405 for May 2024)                     |
| Activity Period Start Date   | Start date of the reporting period (usually first of the month)                              |
| Operating Airline            | Airline that operated the flight                                                             |
| Operating Airline IATA Code  | 2-letter IATA airline code                                                                  |
| Published Airline            | Airline that sold the ticket/published the flight                                            |
| Published Airline IATA Code  | IATA code for the published airline                                                          |
| GEO Summary                  | Route geographic summary (Domestic, International, etc.)                                     |
| GEO Region                   | Market/region (Asia, Europe, Canada, etc.)                                                  |
| Activity Type Code           | Type of activity (Enplaned, Deplaned, Through)                                              |
| Price Category Code          | Passenger fare type (Revenue, NonRevenue)                                                   |
| Terminal                     | Passenger terminal                                                                          |
| Boarding Area                | Boarding area/gate                                                                           |
| Passenger Count              | Number of passengers                                                                         |
| data_as_of                   | Date as of which data is valid                                                              |
| data_loaded_at               | When data was loaded into the system                                                        |
