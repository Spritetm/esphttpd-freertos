This is an example of how to use libesphttpd with the Espressif FreeRTOS SDK. The master
repo of this code is http://git.spritesserver.nl/esphttpd-freertos.git/ , but it's also
mirrored at https://github.com/Spritetm/esphttpd-freertos .


The Makefile in this example isn't perfect yet: something is going wrong with the dependency
checking, causing files that have changed not always being recompiled. To work around this,
please run a
```make clean && make -C libesphttpd && make```
before running
```make flash```

