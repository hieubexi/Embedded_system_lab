# Embedded_system_lab
Creator/lastUpdateDate: HieuNguyenHuu/Nov.18.2023
github: https://github.com/hieubexi/Embedded_system_lab

# About this repository
Creator/UpdateDate: HieuNguyenHuu/Dec.04.2023 <br>
This repo contains  6 lab exercises of Embedded Systems (CO3054), Ho Chi Minh City University of Technology (HCMUT)<br>
Note: In lab06, we only implement ESP32 as a station role.
| Supported Targets | ESP32 | ESP32-C2 | ESP32-C3 | ESP32-C6 | ESP32-H2 | ESP32-S2 | ESP32-S3 |
| ----------------- | ----- | -------- | -------- | -------- | -------- | -------- | -------- |


For more information on the structure and contents of ESP-IDF projects, please refer to Section [Build System](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-guides/build-system.html) of the ESP-IDF Programming Guide.
# Required environment
## Install
1. Download and install [Visual Studio Code](https://code.visualstudio.com/).
2. Open the **Extensions** view by clicking on the Extension icon in the Activity Bar on the side of Visual Studio Code or the **View: Extensions** command (shortcut: <kbd>⇧</kbd> <kbd>⌘</kbd> <kbd>X</kbd> or <kbd>Ctrl+Shift+X</kbd>.
3. Search the extension with any related keyword like `espressif`, `esp-idf`, `esp32`, `esp32s2`, etc.
4. Install the extension. You can follow the instructions [HERE](https://github.com/espressif/vscode-esp-idf-extension/blob/master/docs/tutorial/install.md).
# How to run the project
We have two methods to run the project
1. Run using buttons provided by the application<br>
All of buttons are placed in the bottom of Visual Studio interface.
```
    * Build the project. Push the button ESP-IDF Build project
    * Flash to the device. Push the button ESP-IDF Flash device
    * Open monitor of device. Push the button ESP-IDF Monitor device
```
2. Run with commands
```
    * Build the project. `idf.py build`
    * Flash to the device. `idf.py flash`
    * Open monitor of device. `idf.py monitor`
```
or you can just run multiple commands `idf.py build flash monitor`.

* Program upload failure
    * Hardware connection is not correct: run `idf.py -p PORT monitor`, and reboot your board to see if there are any output logs.
    * The baud rate for downloading is too high: lower your baud rate in the `menuconfig` menu, and try again.
We will get back to you as soon as possible.

