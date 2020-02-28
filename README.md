# Datasets Journal Article MDPI Drones 2020 

Datasets for the Journal Article `Reliable Long Range Multi-Link Communication for Unmanned Search and Rescue Aircraft Systems in Beyond Visual Line of Sight Operation` submitted to MDPI Drones.

```
Index Location Mission Start Stop
1   Peenemünde        Single Link                2019-08-22 07:17:54 2019-08-22 08:19:11
2a  Peenemünde        Long Range                 2019-09-14 09:20:25 2019-09-14 10:04:34
2b  Peenemünde        SAR Mission                2019-09-14 10:15:25 2019-09-14 10:25:24
3   Peenemünde        Final Demonstrator         2019-10-17 11:58:32 2019-10-17 12:58:31
4a  Peenemünde        Manned Validation Flight 1 2019-10-17 11:58:32 2019-10-17 12:58:31
4b  Peenemünde        Manned Validation Flight 2 2019-10-17 11:58:32 2019-10-17 12:58:31
5   Ribnitz-Damgarten Long Range                 2019-08-28 14:07:58 2019-08-28 15:26:39
```

Each subdirectory contains:
- `lte_<operator_name>.csv` LTE channel measurements.
- `gps.nmea` GPS measurements in NMEA format.
- `bwm.csv` bandwidth monitor recording. 
- `ping_<operator_name>.log` round-trip time measurements