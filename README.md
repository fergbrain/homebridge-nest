# ![](https://raw.githubusercontent.com/hoobs-org/homebridge-nest/master/branding/logo.png)

Integrate your Nest Thermostat (including Nest Temperature Sensors) and Nest Protect devices into your Apple Home system. Currently this supports all Nest Thermostat and Nest Protect models, except the UK model of the Thermostat E with Heat Link.

## Supported Accessories

### Home

* *Switch* accessory (Home Occupied) indicating detected Home/Away state - can be manually changed

### Nest Thermostat

* *Thermostat* accessory with ambient temperature and humidity sensors, mode control (heat/cool/auto/off), and target temperature control
* *Switch* accessory (Eco Mode) for turning on and off Eco Mode
* *Fan* accessory for controlling the fan
* *TemperatureSensor* accessory indicating the ambient temperature at the thermostat (disabled by default - temperature is reported by the base *Thermostat* accessory)
* *TemperatureSensor* accessory indicating the ambient temperature where each additional Nest Temperature Sensor is located
* *HumiditySensor* accessory indicating the relative humidity at the thermostat (disabled by default - humidity is reported by the base *Thermostat* accessory)

### Nest Protect

* *SmokeSensor* accessory (Smoke) indicating smoke detected
* *CarbonMonoxideSensor* accessory (Carbon Monoxide) indicating CO detected

## Things to try with Siri

* Hey Siri, *set the temperature to 72 degrees*. (in heat-only or cool-only mode)
* Hey Siri, *set the temperature range to between 65 and 70 degrees*. (in auto mode, for systems that can heat and cool)
* Hey Siri, *set the thermostat to cool*. (try heat, cool, auto, or off)
* Hey Siri, *turn on the air conditioning*.
* Hey Siri, *turn Eco Mode on*.
* Hey Siri, *what's the temperature at home*?
* Hey Siri, *what's the temperature in the Basement*? (get the temperature from a Nest Temperature Sensor)
* Hey Siri, *what's the status of my smoke detector*?

## Credit

This the HOOBS certified version of the [homebridge-nest](https://github.com/chrisjshull/homebridge-nest) plugin. Please consider supporting the developer, Adrian Cable by [making a small donation](https://paypal.me/adriancable586).

Apple, HomeKit and the Apple Home icon are registered trademarks of Apple Inc.  
Nest, Nest Protect and the Nest logo are registered trademarks of Google LLC.
