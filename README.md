# ESPhome-klefr_6934_modbus
This is a ESPhome configuration for reading modbus registers from a Klefr 6934 Energy Meter with a Lilygo ESP32 CAN RS485 board and store values in InfluxDB v2

![klefr6934](https://github.com/j36701/ESPhome-klefr_6934_modbus/blob/main/KLEFR-6934-759x800.png)

Modbus register map is found in appendix A3.2: https://www.iqhome.org/klefr-6934---three-phase-100a-energy-meter-user-manual

## Lilygo ESP32 RS485 board:
[Lilygo ESP32 CAN RS-485 IOT Engineer Control Module Development Board](https://lilygo.cc/products/t-can485?srsltid=AfmBOoqSa-o-vLbd8vIbhc3OsUZ6j8ZRqZra9HUCNUz8Hb7yXC8QIIp0)

## Influx component:
It uses the external influx component: https://github.com/kpfleming/esphome-influxdb_v2_oss
