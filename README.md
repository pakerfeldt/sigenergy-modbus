# Sigenergy Modbus Registers

Machine-readable Sigenergy Modbus register definitions converted from PDF documentation.

## Files

- `sigenergy-registers.json` - Complete register definitions with addresses, data types, units, and more. 
- `sigenergy-registers.csv` - Same register data in CSV format
- `version.json` - Documentation version and revision info
  - `version` - Sigenergy documentation version (e.g., "V2.5")
  - `date` - Documentation date (YYYY-MM-DD format)
  - `revision` - Internal revision number for tracking changes within the same version (e.g., corrections to register descriptions or data types)

## Usage

The JSON format includes:
- Register addresses and quantities
- Data types (U16, S16, U32, etc.)
- Read/write permissions  
- Units and scaling factors
- Device compatibility (hybrid inverters, PV inverters)

## Example

```json
{
    "id": "p-system-time",
    "name": "System time", 
    "address": 30000,
    "dataType": "U32",
    "unit": "s",
    "permission": "RO"
}
```
