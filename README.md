## Homebridge Motion Switch

Can be used to trigger a motion detected event when a switch is turned on, via Siri for example, similar to https://twitter.com/viticci/status/961751917973180417 but within HomeKit only.

#### Setup

Add the following to the accessories list in your Homebridge config. Change names as you wish.

```
{
  "accessory": "Motion Switch",
  "motion_sensor_name": "Test Motion Sensor",
  "switch_name": "Test Switch",
  "name": "Motion Switch"
}
```
