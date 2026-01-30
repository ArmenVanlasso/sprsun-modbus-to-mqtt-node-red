# sprsun-modbus-to-mqtt-node-red
Complete Node‑RED flow for integrating Sprsun CGK040‑V3L heat pump with Home Assistant via Modbus TCP and MQTT Discovery


Production‑ready Node‑RED flow for Sprsun CGK040‑V3L: Modbus register mapping, data scaling, alarm handling, MQTT publishing and full Home Assistant MQTT Discovery.

Instruction:

First, import the entire flow and click Deploy.
Next, you need to configure the MQTT broker, Modbus Flex Getter, and Modbus Flex Write. 
Then, click Discovery. MQTT will discover all entities that refresh every 60 seconds.
