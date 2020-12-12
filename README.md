# platformio_heltec_wireless_stick_lite_board

heltec wireless stick lite_ Board support to platformio.ini

[env:heltec_wireless_stick]

platform = espressif32

board = heltec_wireless_stick_lite

framework = arduino

board_build.f_cpu = 240000000L

upload_protocol = esptool

monitor_filers = esp32_exception_decoder

monitor_speed=115200
