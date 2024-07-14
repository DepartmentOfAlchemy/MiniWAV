# MiniWAV

The MiniWAV is a [FeatherWing](https://learn.adafruit.com/adafruit-feather/featherwings) designed for the [Feather](https://learn.adafruit.com/adafruit-feather) ecosystem create by [Adafruit](https://www.adafruit.com). It provides an SD card reader and I2S audio output to an 1/8" jack stereo audio line output. The board is designed to be used in a haunted attraction prop control system.

## Pinout
- I2S
  - BCK: A0
  - LRCK: A1
  - DIN: A2
- SD Card SPI
  - SCLK: SCK
  - DI: MO
  - DO: MI
  - CS: D10
  - DAT2: D9
  - DAT1: D6
  - CARDDET: D5

### SD Card
| Feather Pin | SPI     | SDIO    |
|-------------|---------|---------|
| SCK         | SCLK    | CLK     |
| MO          | SI      | CMD     |
| MI          | SO      | D0      |
| D10         | CS      | D3      |
| D9          | DAT2    | D2      |
| D6          | DAT1    | D1      |
| D5          | CARDDET | CARDDET |
