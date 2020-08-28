```
(base) thiagofe@thiagofe-ubuntu:~/micropython/ports/stm32$ make BOARD=PYBV11 clean
Use make V=1 or set BUILD_VERBOSE in your environment to increase build verbosity.
rm -rf build-PYBV11 
(base) thiagofe@thiagofe-ubuntu:~/micropython/ports/stm32$ make -j8 BOARD=PYBV11
Use make V=1 or set BUILD_VERBOSE in your environment to increase build verbosity.
mkdir -p build-PYBV11/genhdr
mkdir -p build-PYBV11/build-PYBV11/
mkdir -p build-PYBV11/drivers/bus/
mkdir -p build-PYBV11/drivers/dht/
mkdir -p build-PYBV11/drivers/memory/
mkdir -p build-PYBV11/extmod/
mkdir -p build-PYBV11/lib/embed/
mkdir -p build-PYBV11/lib/libc/
mkdir -p build-PYBV11/lib/libm/
mkdir -p build-PYBV11/lib/littlefs/
mkdir -p build-PYBV11/lib/mp-readline/
mkdir -p build-PYBV11/lib/netutils/
mkdir -p build-PYBV11/lib/oofatfs/
mkdir -p build-PYBV11/lib/stm32lib/CMSIS/STM32F4xx/Source/Templates/
mkdir -p build-PYBV11/lib/stm32lib/CMSIS/STM32F4xx/Source/Templates/gcc/
mkdir -p build-PYBV11/lib/stm32lib/STM32F4xx_HAL_Driver/Src/
mkdir -p build-PYBV11/lib/timeutils/
mkdir -p build-PYBV11/lib/utils/
mkdir -p build-PYBV11/py/
mkdir -p build-PYBV11/usbdev/class/src/
mkdir -p build-PYBV11/usbdev/core/src/
GEN stmconst build-PYBV11/genhdr/modstm_const.h
GEN build-PYBV11/pins_PYBV11.c
GEN build-PYBV11/genhdr/pybcdc.inf
GEN build-PYBV11/genhdr/pllfreqtable.h
GEN build-PYBV11/genhdr/pybcdc_inf.h
GEN build-PYBV11/genhdr/mpversion.h
GEN build-PYBV11/genhdr/moduledefs.h
GEN build-PYBV11/genhdr/qstr.i.last
GEN build-PYBV11/genhdr/qstr.split
GEN build-PYBV11/genhdr/compressed.split
GEN build-PYBV11/genhdr/qstrdefs.collected.h
GEN build-PYBV11/genhdr/compressed.collected
Compressed data updated
QSTR updated
GEN build-PYBV11/genhdr/compressed.data.h
GEN build-PYBV11/genhdr/qstrdefs.generated.h
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
MPY uasyncio/__init__.py
CC ../../lib/libc/string0.c
MPY uasyncio/core.py
MPY uasyncio/event.py
MPY uasyncio/funcs.py
MPY uasyncio/lock.py
MPY uasyncio/stream.py
CC ../../lib/mp-readline/readline.c
MPY dht.py
MPY lcd160cr.py
MPY lcd160cr_test.py
CC ../../lib/netutils/netutils.c
MPY onewire.py
CC ../../lib/netutils/trace.c
CC ../../lib/netutils/dhcpserver.c
CC ../../lib/timeutils/timeutils.c
CC ../../lib/utils/gchelper_native.c
CC ../../lib/utils/pyexec.c
CC ../../lib/utils/interrupt_char.c
CC ../../lib/utils/sys_stdio_mphal.c
CC ../../lib/utils/mpirq.c
CC ../../lib/libm/math.c
GEN build-PYBV11/frozen_content.c
CC ../../lib/libm/acoshf.c
CC ../../lib/libm/asinfacosf.c
CC ../../lib/libm/asinhf.c
CC ../../lib/libm/atan2f.c
CC ../../lib/libm/atanf.c
CC ../../lib/libm/atanhf.c
CC ../../lib/libm/ef_rem_pio2.c
CC ../../lib/libm/erf_lgamma.c
CC ../../lib/libm/fmodf.c
CC ../../lib/libm/kf_cos.c
CC ../../lib/libm/kf_rem_pio2.c
CC ../../lib/libm/kf_sin.c
CC ../../lib/libm/kf_tan.c
CC ../../lib/libm/log1pf.c
CC ../../lib/libm/nearbyintf.c
CC ../../lib/libm/roundf.c
CC ../../lib/libm/sf_cos.c
CC ../../lib/libm/sf_erf.c
CC ../../lib/libm/sf_frexp.c
CC ../../lib/libm/sf_ldexp.c
CC ../../lib/libm/sf_modf.c
CC ../../lib/libm/sf_sin.c
CC ../../lib/libm/sf_tan.c
CC ../../lib/libm/wf_lgamma.c
CC ../../lib/libm/wf_tgamma.c
CC ../../lib/libm/thumb_vfp_sqrtf.c
CC ../../extmod/modonewire.c
CC ../../drivers/bus/softspi.c
CC ../../drivers/bus/softqspi.c
CC ../../drivers/memory/spiflash.c
CC ../../drivers/dht/dht.c
CC main.c
CC stm32_it.c
CC usbd_conf.c
CC usbd_desc.c
CC usbd_cdc_interface.c
CC usbd_hid_interface.c
CC usbd_msc_interface.c
CC mphalport.c
CC mpthreadport.c
CC irq.c
CC pendsv.c
CC systick.c
CC softtimer.c
CC powerctrl.c
CC powerctrlboot.c
CC rfcore.c
CC pybthread.c
CC factoryreset.c
CC timer.c
CC led.c
CC pin.c
CC pin_defs_stm32.c
CC pin_named_pins.c
CC bufhelper.c
CC dma.c
CC i2c.c
CC pyb_i2c.c
CC spi.c
CC pyb_spi.c
CC qspi.c
CC uart.c
CC can.c
CC fdcan.c
CC pyb_can.c
CC usb.c
CC wdt.c
CC eth.c
CC gccollect.c
CC help.c
CC machine_adc.c
CC machine_i2c.c
CC machine_spi.c
CC machine_timer.c
CC machine_uart.c
CC modmachine.c
CC modpyb.c
CC modstm.c
CC moduos.c
CC modutime.c
CC modusocket.c
CC network_lan.c
CC modnetwork.c
CC extint.c
CC usrsw.c
CC rng.c
CC rtc.c
CC flash.c
CC flashbdev.c
CC spibdev.c
CC storage.c
CC sdcard.c
CC sdram.c
CC fatfs_port.c
CC lcd.c
CC accel.c
CC servo.c
CC dac.c
CC adc.c
AS ../../lib/stm32lib/CMSIS/STM32F4xx/Source/Templates/gcc/startup_stm32f405xx.s
CC ../../lib/stm32lib/CMSIS/STM32F4xx/Source/Templates/system_stm32f4xx.c
CC system_stm32.c
AS resethandler.s
AS ../../lib/utils/gchelper_m3.s
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_adc.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_adc_ex.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_cortex.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_dma.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_flash.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_flash_ex.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_gpio.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_i2c.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_pcd.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_pcd_ex.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_pwr.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_pwr_ex.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_rcc.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_rcc_ex.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_rtc.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_rtc_ex.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_spi.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_tim.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_tim_ex.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_uart.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_ll_usb.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_sd.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_ll_sdmmc.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_ll_fmc.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_mmc.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_sdram.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_dma_ex.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_dcmi.c
CC ../../lib/stm32lib/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_can.c
CC usbdev/core/src/usbd_core.c
CC usbdev/core/src/usbd_ctlreq.c
CC usbdev/core/src/usbd_ioreq.c
CC usbdev/class/src/usbd_cdc_msc_hid.c
CC usbdev/class/src/usbd_msc_bot.c
CC usbdev/class/src/usbd_msc_scsi.c
CC ../../lib/oofatfs/ff.c
CC ../../lib/oofatfs/ffunicode.c
CC ../../lib/littlefs/lfs2.c
CC ../../lib/littlefs/lfs2_util.c
CC build-PYBV11/pins_PYBV11.c
CC build-PYBV11/frozen_content.c
LINK build-PYBV11/firmware.elf
   text	   data	    bss	    dec	    hex	filename
 358484	     28	  27256	 385768	  5e2e8	build-PYBV11/firmware.elf
GEN build-PYBV11/firmware.dfu
GEN build-PYBV11/firmware.hex
(base) thiagofe@thiagofe-ubuntu:~/micropython/ports/stm32$ ls
accel.c         flashbdev.c          make-stmconst.py        network_wiznet5k.c   resethandler.s  systick.c
accel.h         flash.c              mbedtls                 nimble.c             rfcore.c        systick.h
adc.c           flash.h              mboot                   pendsv.c             rfcore.h        timer.c
adc.h           font_petme128_8x8.h  modbluetooth_hci.c      pendsv.h             rng.c           timer.h
autoflash       gccollect.c          modmachine.c            pin.c                rng.h           uart.c
boards          gccollect.h          modmachine.h            pin_defs_stm32.c     rtc.c           uart.h
btstack.c       help.c               modnetwork.c            pin_defs_stm32.h     rtc.h           usb.c
bufhelper.c     i2c.c                modnetwork.h            pin.h                sdcard.c        usbd_cdc_interface.c
bufhelper.h     i2c.h                modnwcc3k.c             pin_named_pins.c     sdcard.h        usbd_cdc_interface.h
build-PYBD_SF2  i2cslave.c           modnwwiznet5k.c         pin_static_af.h      sdio.c          usbd_conf.c
build-PYBV11    i2cslave.h           modpyb.c                portmodules.h        sdio.h          usbd_conf.h
can.c           irq.c                modstm.c                powerctrlboot.c      sdram.c         usbd_desc.c
can.h           irq.h                moduos.c                powerctrl.c          sdram.h         usbd_desc.h
dac.c           lcd.c                modusocket.c            powerctrl.h          servo.c         usbdev
dac.h           lcd.h                modutime.c              pyb_can.c            servo.h         usbd_hid_interface.c
dma.c           led.c                mpconfigboard_common.h  pybcdc.inf_template  softtimer.c     usbd_hid_interface.h
dma.h           led.h                mpconfigport.h          pyb_i2c.c            softtimer.h     usbd_msc_interface.c
eth.c           lwip_inc             mpconfigport.mk         pyb_spi.c            spibdev.c       usbd_msc_interface.h
eth.h           machine_adc.c        mpconfigport_nanbox.h   pybthread.c          spi.c           usb.h
extint.c        machine_i2c.c        mphalport.c             pybthread.h          spi.h           usbhost
extint.h        machine_spi.c        mphalport.h             qspi.c               stm32_it.c      usrsw.c
factoryreset.c  machine_timer.c      mpthreadport.c          qspi.h               stm32_it.h      usrsw.h
factoryreset.h  machine_uart.c       mpthreadport.h          qstrdefsport.h       storage.c       wdt.c
fatfs_port.c    main.c               mpu.h                   README.md            storage.h       wdt.h
fdcan.c         Makefile             network_lan.c           resethandler_m0.s    system_stm32.c
(base) thiagofe@thiagofe-ubuntu:~/micropython/ports/stm32$ cd build-PYB
bash: cd: build-PYB: Arquivo ou diretório inexistente
(base) thiagofe@thiagofe-ubuntu:~/micropython/ports/stm32$ cd build-PYBV11
(base) thiagofe@thiagofe-ubuntu:~/micropython/ports/stm32/build-PYBV11$ ls
accel.o         fdcan.o           lcd.o            modstm.o          pins_af.py       rng.o           systick.P
accel.P         fdcan.P           lcd.P            modstm.P          pins_PYBV11.c    rng.P           timer.o
adc.o           firmware0.bin     led.o            modstm_qstr.h     pins_PYBV11.o    rtc.o           timer.P
adc.P           firmware1.bin     led.P            moduos.o          pins_PYBV11.P    rtc.P           uart.o
bufhelper.o     firmware.dfu      lib              moduos.P          pins_qstr.h      sdcard.o        uart.P
bufhelper.P     firmware.elf      machine_adc.o    modusocket.o      powerctrlboot.o  sdcard.P        usbd_cdc_interface.o
build-PYBV11    firmware.hex      machine_adc.P    modusocket.P      powerctrlboot.P  sdram.o         usbd_cdc_interface.P
can.o           firmware.map      machine_i2c.o    modutime.o        powerctrl.o      sdram.P         usbd_conf.o
can.P           flashbdev.o       machine_i2c.P    modutime.P        powerctrl.P      servo.o         usbd_conf.P
dac.o           flashbdev.P       machine_spi.o    mphalport.o       py               servo.P         usbd_desc.o
dac.P           flash.o           machine_spi.P    mphalport.P       pyb_can.o        softtimer.o     usbd_desc.P
dma.o           flash.P           machine_timer.o  mpthreadport.o    pyb_can.P        softtimer.P     usbdev
dma.P           frozen_content.c  machine_timer.P  mpthreadport.P    pyb_i2c.o        spibdev.o       usbd_hid_interface.o
drivers         frozen_mpy        machine_uart.o   network_lan.o     pyb_i2c.P        spibdev.P       usbd_hid_interface.P
eth.o           gccollect.o       machine_uart.P   network_lan.P     pyb_spi.o        spi.o           usbd_msc_interface.o
eth.P           gccollect.P       main.o           pendsv.o          pyb_spi.P        spi.P           usbd_msc_interface.P
extint.o        genhdr            main.P           pendsv.P          pybthread.o      stm32_it.o      usb.o
extint.P        help.o            modmachine.o     pin_defs_stm32.o  pybthread.P      stm32_it.P      usb.P
extmod          help.P            modmachine.P     pin_defs_stm32.P  qspi.o           storage.o       usrsw.o
factoryreset.o  i2c.o             modnetwork.o     pin_named_pins.o  qspi.P           storage.P       usrsw.P
factoryreset.P  i2c.P             modnetwork.P     pin_named_pins.P  resethandler.o   system_stm32.o  wdt.o
fatfs_port.o    irq.o             modpyb.o         pin.o             rfcore.o         system_stm32.P  wdt.P
fatfs_port.P    irq.P             modpyb.P         pin.P             rfcore.P         systick.o
(base) thiagofe@thiagofe-ubuntu:~/micropython/ports/stm32/build-PYBV11$
```

