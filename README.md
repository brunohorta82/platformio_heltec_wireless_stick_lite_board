[env:heltec_wireless_stick]
platform = espressif32
board = heltec_wireless_stick_lite
framework = arduino
board_build.f_cpu = 240000000L
upload_protocol = esptool
monitor_filers = esp32_exception_decoder
monitor_speed=115200
