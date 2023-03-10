====="How to change UUID and Serial of Motherboard "=====
1. Run DMIEDIT as Admin
2. Change UUID: System Information->UUID (Double click and change to whatever but keep the same length 32 digits)
3. Change Serial: Base Board->Serial Number (Double click and change to whatever but keep the same length)
4. Change SKUNumber,Family,Manufacturer,Version,Asset Tag,Locationm in Chassis
5. Change on System Enclosure: Serial,Asset Tag,SKU Number
6. Change on Processor Informatio: Serial, Asset Tag,Part Number
7. OEM Strings: Change String #1
8.System Configuration: Change String #1
9. System Power Supply: Change Location,Device Name,Manufacturer,Serial,Asset Tag,Model,Revision.
10. After that just hit Update->All

If you get any errors relating to PNP your motherboard isn't compatible with this version of dmiEdit.
Note: if it crashes update everything one after the other