# Device Parameters

## Overview

A number of parameters are available inside the plugin to customize the behaaviour of the plugin or the behaviour of the device.

By default a Certified device get default parameters already initiatialized. If you want to customize you have to go to the plugin Web Admin page,
then go to Management -> Device Management and you will find for each device a Parameters field ( right column )
You can edit this field, by adding, removing or updating attributes. Please make sure to follow the syntax:

{ 'parameter1': value, 'parameter2': value .... }

| Parameter Name | Description | Working Device |
| -------------- | ----------- | -------------- |
| Calibration    | Allow to define a calibration value in °C | Tuya eTRV, Eurotronics SPZB0001, Schneider VACT, Danfoss eTRV |
| Alarm1         | Configuration of Alarm1. you have to specify Duration Volume, Melody | Tuya Siren TS0601 |
| Alarm2         | Configuration of Alarm2. you have to specify Duration Volume, Melody | Tuya Siren TS0601 |
| Alarm3         | Configuration of Alarm3. you have to specify Duration Volume, Melody | Tuya Siren TS0601 |
| Alarm4         | Configuration of Alarm4. you have to specify Duration Volume, Melody | Tuya Siren TS0601 |
| Alarm5         | Configuration of Alarm5. you have to specify Duration Volume, Melody | Tuya Siren TS0601 |
| Duration       | Applicable only inside the Alarm definition, it will configure the duration of alarm in Sec | Tuya Siren TS0601 |
| Volume         | Applicable only inside the Alarm definition, it will configure the Volume of alarm 0,1,2 (High, Medium, Low) | Tuya Siren TS0601 |
| Melody         | Applicable only inside the Alarm definition, it will configure the Melody ( from 1 to 15 ) | Tuya Siren TS0601 |
| HumidityMinAlarm    | Minimum humidity threshold for Alarm | Tuya Siren TS0601 |
| HumidityMaxAlarm    | Maximum humidity threshold for Alarm | Tuya Siren TS0601 |
| TemperatureMinAlarm | Minimum temperature threshold for Alarm | Tuya Siren TS0601 |
| TemperatureMaxAlarm | Maximum temperature threshold for Alarm | Tuya Siren TS0601 |
| PowerOnAfterOffOn   | If managed by the device, the device will go to a desired state after an electric Off/On. 0 stands for  stay Off, 1 stands for switch On, 255 stands for previous state | Ikea, ENki, BlitzWolf plug, Legrand, Philips (could required a firmware update of the end device |)
| fadingOff     | Transition time for power device power off. Will increase by 20% and then switch off | all dimming Led |
| moveToHueSatu    | Transition time in tenth of seconds ( 10 means 1s ) to change Saturation Temp from current level to target level | all dimming Led |
| moveToColourTemp | Transition time in tenth of seconds ( 10 means 1s ) to change White color from current level to target level | all dimming Led |
| moveToColourRGB  | Transition time in tenth of seconds ( 10 means 1s ) to change Led color from current level to target level | all dimming Led |
| moveToLevel      | Transition time in tenth of seconds ( 10 means 1s ) to dim the Led from current level to target level | all dimming Led |
