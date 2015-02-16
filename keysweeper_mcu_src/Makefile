ARDUINO_DIR=/usr/share/arduino
ARDMK_DIR=/usr/share/arduino
AVR_TOOLS_DIR=/usr

USER_LIB_PATH:=$(realpath ../../libraries)
#MONITOR_PORT=/dev/ttyUSB*
#BOARD_TAG=nano328
MONITOR_PORT=/dev/ttyACM*
BOARD_TAG=mega2560

ARDUINO_LIBS=SPI RF24 EEPROM

include $(ARDMK_DIR)/Arduino.mk

all: $(OBJDIR)/keysweeper_mcu_src.hex
