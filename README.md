
# PCS Reference
PCS Alarm references for dashboard

## What are these files?

### PCSAlarmIndex
`PCSAlarmIndex.json` is for referencing alarm from the hexadecimal digits

### PCSAlarmList
`PCSAlarmList.json` is the database of PCS alarms

## How to use them?

#### Install
```bash
npm install --save-dev git@github.com:ampd-energy/pcs-reference.git
```

#### Import
```javascript
  // importing the whole as one object
  import PCSRef from 'pcs-reference'

  // of course you can also do this if you want to direcly reference individual object
  import { index, list } from 'pcs-reference'
```
