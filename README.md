# wisblock-multicore
Demonstrate multicore capability on a RAK11310 WisBlock Core module. This program simply blinks the WisBlock Base blue LED using core 1 and blinks the green LED using core 0.

## Hardware

 * RAK11310 WisBlock Core module (https://docs.rakwireless.com/Product-Categories/WisBlock/RAK11310/Datasheet/#overview)
 * RAK19001 WisBlock Dual IO Base Board (https://docs.rakwireless.com/Product-Categories/WisBlock/RAK19001/Datasheet/#wisblock-dual-io-base-board-overview)

### Default Pinout

| RAK11310 |
| ----------------- |
| GPIO 23 | LED_GREEN |
| GPIO 24 | LED_BLUE |


## Cloning

```sh
git clone --recurse-submodules https://github.com/m-nahirny/wisblock-multicore.git 
```

## Building

1. [Set up the Pico C/C++ SDK](https://datasheets.raspberrypi.org/pico/getting-started-with-pico.pdf)
2. Set `PICO_SDK_PATH`
```sh
export PICO_SDK_PATH=/path/to/pico-sdk
```
3. Create `build` dir, run `cmake` and `make`:
```
4. Copy example `.uf2` to RAK11310 when in BOOT mode.

