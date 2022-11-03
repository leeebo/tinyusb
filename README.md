## TinyUSB Core Code for ESP32Sx

[![Push component to https://components.espressif.com](https://github.com/leeebo/tinyusb_src/actions/workflows/sync_esp_pkgmng.yml/badge.svg?branch=master)](https://github.com/leeebo/tinyusb_src/actions/workflows/sync_esp_pkgmng.yml)

The core code of TinyUSB as the ESP-IDF component, users can use the Tinyusb native interface for project development based on ESP32SX.

For more information about TinyUSB, please refer https://docs.tinyusb.org

## Feature

1. Choose between `dcd_esp32sx` or `dcd_dwc2` through Kconfig
2. Include below device drivers by default
   1. audio
   2. bth
   3. cdc
   4. dfu
   5. hid
   6. midi
   7. msc
   8. net
   9. usbtmc
   10. vendor
   11. video