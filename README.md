# Nodebots JS Conf 2019

## Prerequisites

-   Install [Arduino IDE](https://www.arduino.cc/en/Main/Software)
-   Install nodejs

## Installing Other Tools

```
./download_res.sh
./setup.sh
```

## Installing firmata (rest to be done on the workshop day)
We need to flash the arduino with firmata.
- Open Arduino IDE -> Example -> Firmata -> Standard firmata
- Compile -> Upload

## Getting started

-   LED Blinky [example](http://johnny-five.io/examples/led-blink/)
-   Servo [example](http://johnny-five.io/examples/servo/)
-   Joystick [example](http://johnny-five.io/examples/joystick/)
-   Led Matrix [example](http://johnny-five.io/examples/led-matrix/)


## Simple Bot

Download simplebot (done by setup.sh)
-   ``` git clone https://github.com/nodebotsau/simplebot ```

Wiring - [link](https://github.com/nodebotsau/simplebot/blob/master/examples/wiring/basic_wiring_bb.png)
Code to run - [link](https://github.com/nodebotsau/simplebot/blob/master/examples/SimpleBotShield/simplebot.js)

## Neopixel
- Flash arduino with node-pixel
    -   ``` npm install -g nodebots-interchange ``` 
    -   ``` interchange install git+https://github.com/ajfisher/node-pixel -a nano --firmata```

Example - [links](https://github.com/ajfisher/node-pixel)

Other links

- https://docs.npmjs.com/getting-started/fixing-npm-permissions
- https://www.npmjs.com/package/barcli (Terminal charting)


