# homebridge-matcha-thermostat
*For testing purpose ONLY. You should NOT install this.

Plugin for homebridge to create a fake thermostat accessory

## Installation

1. Install [homebridge](https://github.com/nfarina/homebridge#installation-details)
2. Install this plugin: `npm install -g homebridge-matcha-thermostat`
3. Edit your `config.json` file (See below).

## Configuration example

```json
"accessories": [
     {
       "accessory": "Matcha-Thermostat",
       "name": "Thermostat"
     }
]
```

### Structure

| Key | Description |
| --- | --- |
| `accessory` | Must be `Matcha-Thermostat` |
| `name` | Name to appear in the Home app |
| `temperatureDisplayUnits` _(optional)_ | Whether you want °C (`0`) or °F (`1`) as your units (`0` is default) |
| `model` _(optional)_ | Appears under "Model" for your accessory in the Home app |
| `manufacturer` _(optional)_ | Appears under "Manufacturer" for your accessory in the Home app |

