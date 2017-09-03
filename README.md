# AQM0802-CLOCK

Display the current time using AQM0802 and Raspberry Pi.

## Description

AQM0802 is a character LCD module. This script displays current time using Raspberry Pi.

## Requirement

- i2c-tools

## Usage

- Run
    ```
    $ sudo bash main
    ```

- Run in the background
    ```
    $ nohup sudo bash main > /dev/null &
    ```

## Installation

1. git clone
    ```
    $ git clone https://github.com/kazumatsudo/aqm0802-clock.git
    ```
    
1. open main and rewrite I2C address
    ```
    $ cd aqm0802-clock
    $ sudo vi main
      # Check and rewrite I2C address
      readonly DEVICE="0x3e"
    ```

## Author

[kazumatsudo](https://kazumatsudo.jp)

## License

[MIT](https://github.com/kazumatsudo/aqm0802-clock/LICENSE)