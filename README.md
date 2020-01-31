# Tip-over Detection

This repository contains scooter tip-over data published by Skip.

### Summary

The tip-over data contains local timestamp and latitude/longitude information regarding each tip-over. Tip-overs are from Skip's DC Metro area scooters. Response times listed are calculated from the time of the tip-over alert creation to the time of resolution. Note that latitude/longitude values are subject to standard GPS accuracy limitations.

### Fields

| Field Name        | Description                                                           |
|-------------------|-----------------------------------------------------------------------|
| datetimeLoc       | Timestamp in local timezone (e.g., for DC, "America/New_York")                      |
| latitude          | Latitude where tip-over occurred                                      |
| longitude         | Longitude where tip-over occurred                                     |
| response_time_sec | Time delta between tip-over alert creation and resolution, in seconds |


### Medium Article

https://medium.com/@skipscooters/announcing-tip-over-detection-8264b53c14f2
