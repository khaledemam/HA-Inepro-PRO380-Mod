# HA-Inepro-PRO380-Mod
Inepro PRO380-Mod integration into Home Assistant

Settings:
1. On the consumption meter:
parity: N
address: 2

2. The modbus.yaml file must be copied to the /config directory

3. In Configuration.yaml:
modbus: !include modbus.yaml

4. reboot
