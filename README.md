# Overview
Small Repository for the Zabbix Tempaltes that I build

All templates require the appropriate MIBs to be installed on your system. OIDs are ugly and impossible to read.

## Template_Palo_Alto
Built for Zabbix 3.0 and heavily utilises the new discovery methods. Should be able to handle scaling to a clustered Palo.

###MIBs Required:
- PAN-ENTITY-EXT-MIB
- PAN-COMMON-MIB
- PAN-GLOBAL-REG-MIB
- PAN-GLOBAL-TC-MIB
- PAN-LC-MIB
- PAN-PRODUCT-MIB
- PAN-TRAPS
- ENTITY-SENSOR-MIB
- ENTITY-STATE-MIB
- ENTITY-STATE-TC-MIB

### TODO
- Trap Handling
