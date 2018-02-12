## Homebridge Motion Switch

Can be used to trigger a motion detected event when a switch is turned on, via Siri for example, similar to https://twitter.com/viticci/status/961751917973180417 but within HomeKit only.

#### Setup

`npm install -g homebridge-motion-switch`

And add the following to the accessories list in your Homebridge config. Change names as you wish.

```
{
  "accessory": "Motion Switch",
  "motion_sensor_name": "Motion Sensor",
  "switch_name": "Motion Switch",
  "name": "Motion Switch"
}
```

Then add it to HomeKit, once added, you will need to turn on Notifications for the motion sensor you just added.
