Note:
  port from android toolbox, test with ubuntu x86 and armhf system.  

Build:

 gcc getevent.c -o getevent

TEST: sudo ./getevent

add device 1: /dev/input/event1

  name:     "Lite-On Technology Corp. HP Basic USB Keyboard"

add device 2: /dev/input/event0

    name:     "gpio-keys.12"

/dev/input/event0: 0001 0074 00000002

/dev/input/event0: 0000 0000 00000001

/dev/input/event0: 0001 0074 00000002

