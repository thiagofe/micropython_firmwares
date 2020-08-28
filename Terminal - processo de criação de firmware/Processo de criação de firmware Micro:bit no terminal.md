```
(base) thiagofe@thiagofe-ubuntu:~/micropython/ports/nrf$ make BOARD=microbit clean
Use make V=1 or set BUILD_VERBOSE in your environment to increase build verbosity.
rm -rf build-microbit 
(base) thiagofe@thiagofe-ubuntu:~/micropython/ports/nrf$ make -j8 BOARD=microbit
Use make V=1 or set BUILD_VERBOSE in your environment to increase build verbosity.
mkdir -p build-microbit/genhdr
mkdir -p build-microbit/boards/microbit/modules/
mkdir -p build-microbit/device/
mkdir -p build-microbit/drivers/
mkdir -p build-microbit/drivers/bluetooth/
mkdir -p build-microbit/extmod/
mkdir -p build-microbit/lib/embed/
mkdir -p build-microbit/lib/libc/
mkdir -p build-microbit/lib/mp-readline/
mkdir -p build-microbit/lib/nrfx/drivers/src/
mkdir -p build-microbit/lib/nrfx/drivers/src/prs/
mkdir -p build-microbit/lib/nrfx/mdk/
mkdir -p build-microbit/lib/timeutils/
mkdir -p build-microbit/lib/utils/
mkdir -p build-microbit/modules/ble/
mkdir -p build-microbit/modules/board/
mkdir -p build-microbit/modules/machine/
mkdir -p build-microbit/modules/music/
mkdir -p build-microbit/modules/ubluepy/
mkdir -p build-microbit/modules/uos/
mkdir -p build-microbit/modules/utime/
mkdir -p build-microbit/py/
Create build-microbit/pins_gen.c
GEN build-microbit/genhdr/mpversion.h
GEN build-microbit/genhdr/moduledefs.h
GEN build-microbit/genhdr/qstr.i.last
GEN build-microbit/genhdr/qstr.split
GEN build-microbit/genhdr/qstrdefs.collected.h
QSTR updated
GEN build-microbit/genhdr/qstrdefs.generated.h
CC boards/microbit/modules/microbitdisplay.c
CC boards/microbit/modules/microbitimage.c
CC boards/microbit/modules/iters.c
CC boards/microbit/modules/microbitconstimage.c
CC boards/microbit/modules/microbitconstimagetuples.c
CC boards/microbit/modules/modmicrobit.c
CC ../../py/mpstate.c
CC ../../py/nlr.c
CC ../../py/nlrx86.c
CC ../../py/nlrx64.c
CC ../../py/nlrthumb.c
CC ../../py/nlrpowerpc.c
CC ../../py/nlrxtensa.c
CC ../../py/nlrsetjmp.c
CC ../../py/malloc.c
CC ../../py/gc.c
CC ../../py/pystack.c
CC ../../py/qstr.c
CC ../../py/vstr.c
CC ../../py/mpprint.c
CC ../../py/unicode.c
CC ../../py/mpz.c
CC ../../py/reader.c
CC ../../py/lexer.c
CC ../../py/parse.c
CC ../../py/scope.c
CC ../../py/compile.c
CC ../../py/emitcommon.c
CC ../../py/emitbc.c
CC ../../py/asmbase.c
CC ../../py/asmx64.c
CC ../../py/emitnx64.c
CC ../../py/asmx86.c
CC ../../py/emitnx86.c
CC ../../py/asmthumb.c
CC ../../py/emitnthumb.c
CC ../../py/emitinlinethumb.c
CC ../../py/asmarm.c
CC ../../py/emitnarm.c
CC ../../py/asmxtensa.c
CC ../../py/emitnxtensa.c
CC ../../py/emitinlinextensa.c
CC ../../py/emitnxtensawin.c
CC ../../py/formatfloat.c
CC ../../py/parsenumbase.c
CC ../../py/parsenum.c
CC ../../py/emitglue.c
CC ../../py/persistentcode.c
CC ../../py/runtime.c
CC ../../py/runtime_utils.c
CC ../../py/scheduler.c
CC ../../py/nativeglue.c
CC ../../py/pairheap.c
CC ../../py/ringbuf.c
CC ../../py/stackctrl.c
CC ../../py/argcheck.c
CC ../../py/warning.c
CC ../../py/profile.c
CC ../../py/map.c
CC ../../py/obj.c
CC ../../py/objarray.c
CC ../../py/objattrtuple.c
CC ../../py/objbool.c
CC ../../py/objboundmeth.c
CC ../../py/objcell.c
CC ../../py/objclosure.c
CC ../../py/objcomplex.c
CC ../../py/objdeque.c
CC ../../py/objdict.c
CC ../../py/objenumerate.c
CC ../../py/objexcept.c
CC ../../py/objfilter.c
CC ../../py/objfloat.c
CC ../../py/objfun.c
CC ../../py/objgenerator.c
CC ../../py/objgetitemiter.c
CC ../../py/objint.c
CC ../../py/objint_longlong.c
CC ../../py/objint_mpz.c
CC ../../py/objlist.c
CC ../../py/objmap.c
CC ../../py/objmodule.c
CC ../../py/objobject.c
CC ../../py/objpolyiter.c
CC ../../py/objproperty.c
CC ../../py/objnone.c
CC ../../py/objnamedtuple.c
CC ../../py/objrange.c
CC ../../py/objreversed.c
CC ../../py/objset.c
CC ../../py/objsingleton.c
CC ../../py/objslice.c
CC ../../py/objstr.c
CC ../../py/objstrunicode.c
CC ../../py/objstringio.c
CC ../../py/objtuple.c
CC ../../py/objtype.c
CC ../../py/objzip.c
CC ../../py/opmethods.c
CC ../../py/sequence.c
CC ../../py/stream.c
CC ../../py/binary.c
CC ../../py/builtinimport.c
CC ../../py/builtinevex.c
CC ../../py/builtinhelp.c
CC ../../py/modarray.c
CC ../../py/modbuiltins.c
CC ../../py/modcollections.c
CC ../../py/modgc.c
CC ../../py/modio.c
CC ../../py/modmath.c
CC ../../py/modcmath.c
CC ../../py/modmicropython.c
CC ../../py/modstruct.c
CC ../../py/modsys.c
CC ../../py/moduerrno.c
CC ../../py/modthread.c
CC ../../py/vm.c
CC ../../py/bc.c
CC ../../py/showbc.c
CC ../../py/repl.c
CC ../../py/smallint.c
CC ../../py/frozenmod.c
CC ../../extmod/moduasyncio.c
CC ../../extmod/moductypes.c
CC ../../extmod/modujson.c
CC ../../extmod/modure.c
CC ../../extmod/moduzlib.c
CC ../../extmod/moduheapq.c
CC ../../extmod/modutimeq.c
CC ../../extmod/moduhashlib.c
CC ../../extmod/moducryptolib.c
CC ../../extmod/modubinascii.c
CC ../../extmod/virtpin.c
CC ../../extmod/machine_mem.c
CC ../../extmod/machine_pinbase.c
CC ../../extmod/machine_signal.c
CC ../../extmod/machine_pulse.c
CC ../../extmod/machine_i2c.c
CC ../../extmod/machine_spi.c
CC ../../extmod/modbluetooth.c
CC ../../extmod/modussl_axtls.c
CC ../../extmod/modussl_mbedtls.c
CC ../../extmod/modurandom.c
CC ../../extmod/moduselect.c
CC ../../extmod/moduwebsocket.c
CC ../../extmod/modwebrepl.c
CC ../../extmod/modframebuf.c
CC ../../extmod/vfs.c
CC ../../extmod/vfs_blockdev.c
CC ../../extmod/vfs_reader.c
CC ../../extmod/vfs_posix.c
CC ../../extmod/vfs_posix_file.c
CC ../../extmod/vfs_fat.c
CC ../../extmod/vfs_fat_diskio.c
CC ../../extmod/vfs_fat_file.c
CC ../../extmod/vfs_lfs.c
CC ../../extmod/utime_mphal.c
CC ../../extmod/uos_dupterm.c
CC ../../lib/embed/abort_.c
CC ../../lib/utils/printf.c
CC main.c
CC mphalport.c
CC help.c
CC gccollect.c
CC pin_named_pins.c
CC fatfs_port.c
CC drivers/flash.c
CC drivers/rng.c
CC drivers/softpwm.c
CC drivers/ticker.c
CC drivers/bluetooth/ble_drv.c
CC drivers/bluetooth/ble_uart.c
CC device/startup_nrf51822.c
CC ../../lib/nrfx/drivers/src/prs/nrfx_prs.c
CC ../../lib/nrfx/drivers/src/nrfx_uart.c
CC ../../lib/nrfx/drivers/src/nrfx_adc.c
CC ../../lib/nrfx/drivers/src/nrfx_saadc.c
CC ../../lib/nrfx/drivers/src/nrfx_temp.c
CC ../../lib/nrfx/drivers/src/nrfx_rng.c
CC ../../lib/nrfx/drivers/src/nrfx_twi.c
CC ../../lib/nrfx/drivers/src/nrfx_spi.c
CC ../../lib/nrfx/drivers/src/nrfx_spim.c
CC ../../lib/nrfx/drivers/src/nrfx_rtc.c
CC ../../lib/nrfx/drivers/src/nrfx_timer.c
CC ../../lib/nrfx/drivers/src/nrfx_pwm.c
CC ../../lib/nrfx/drivers/src/nrfx_gpiote.c
CC ../../lib/nrfx/drivers/src/nrfx_nvmc.c
CC ../../lib/nrfx/drivers/src/nrfx_power.c
CC ../../lib/nrfx/drivers/src/nrfx_clock.c
CC modules/machine/modmachine.c
CC modules/machine/uart.c
CC modules/machine/spi.c
CC modules/machine/i2c.c
CC modules/machine/adc.c
CC modules/machine/pin.c
CC modules/machine/timer.c
CC modules/machine/rtcounter.c
CC modules/machine/pwm.c
CC modules/machine/temp.c
CC modules/uos/moduos.c
CC modules/uos/microbitfs.c
CC modules/utime/modutime.c
CC modules/board/modboard.c
CC modules/board/led.c
CC modules/ubluepy/modubluepy.c
CC modules/ubluepy/ubluepy_peripheral.c
CC modules/ubluepy/ubluepy_service.c
CC modules/ubluepy/ubluepy_characteristic.c
CC modules/ubluepy/ubluepy_uuid.c
CC modules/ubluepy/ubluepy_delegate.c
CC modules/ubluepy/ubluepy_constants.c
CC modules/ubluepy/ubluepy_descriptor.c
CC modules/ubluepy/ubluepy_scanner.c
CC modules/ubluepy/ubluepy_scan_entry.c
CC modules/music/modmusic.c
CC modules/music/musictunes.c
CC modules/ble/modble.c
CC ../../lib/nrfx/mdk/system_nrf51.c
CC ../../lib/libc/string0.c
CC ../../lib/mp-readline/readline.c
CC ../../lib/utils/pyexec.c
CC ../../lib/utils/sys_stdio_mphal.c
CC ../../lib/utils/interrupt_char.c
CC ../../lib/timeutils/timeutils.c
CC build-microbit/pins_gen.c
LINK build-microbit/firmware.elf
   text	   data	    bss	    dec	    hex	filename
 142228	    100	   1152	 143480	  23078	build-microbit/firmware.elf
arm-none-eabi-objcopy -O binary build-microbit/firmware.elf build-microbit/firmware.bin
arm-none-eabi-objcopy -O ihex build-microbit/firmware.elf build-microbit/firmware.hex
(base) thiagofe@thiagofe-ubuntu:~/micropython/ports/nrf$ 
```
