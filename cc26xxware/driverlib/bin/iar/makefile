# Get directory of this makefile
MAKEFILE_DIR := $(dir $(lastword $(MAKEFILE_LIST)))

# Specify the default makedefs file, which can be overridden at the command line
MAKEDEFS = $(MAKEFILE_DIR)makedefs
include $(MAKEDEFS)

# Always builds phony rules
.PHONY: all clean

# Builds driverlib.lib
all :
		@ rm -f $(MAKEFILE_DIR)driverlib.lib
		@ rm -f $(MAKEFILE_DIR)*.o
		@ echo IAR: Compile adi.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/adi.c -D nDEBUG -o $(MAKEFILE_DIR)adi.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile aon_batmon.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/aon_batmon.c -D nDEBUG -o $(MAKEFILE_DIR)aon_batmon.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile aon_event.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/aon_event.c -D nDEBUG -o $(MAKEFILE_DIR)aon_event.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile aon_ioc.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/aon_ioc.c -D nDEBUG -o $(MAKEFILE_DIR)aon_ioc.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile aon_rtc.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/aon_rtc.c -D nDEBUG -o $(MAKEFILE_DIR)aon_rtc.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile aon_wuc.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/aon_wuc.c -D nDEBUG -o $(MAKEFILE_DIR)aon_wuc.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile aux_adc.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/aux_adc.c -D nDEBUG -o $(MAKEFILE_DIR)aux_adc.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile aux_smph.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/aux_smph.c -D nDEBUG -o $(MAKEFILE_DIR)aux_smph.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile aux_tdc.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/aux_tdc.c -D nDEBUG -o $(MAKEFILE_DIR)aux_tdc.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile aux_timer.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/aux_timer.c -D nDEBUG -o $(MAKEFILE_DIR)aux_timer.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile aux_wuc.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/aux_wuc.c -D nDEBUG -o $(MAKEFILE_DIR)aux_wuc.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile chipinfo.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/chipinfo.c -D nDEBUG -o $(MAKEFILE_DIR)chipinfo.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile cpu.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/cpu.c -D nDEBUG -o $(MAKEFILE_DIR)cpu.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile crypto.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/crypto.c -D nDEBUG -o $(MAKEFILE_DIR)crypto.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile ddi.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/ddi.c -D nDEBUG -o $(MAKEFILE_DIR)ddi.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile debug.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/debug.c -D nDEBUG -o $(MAKEFILE_DIR)debug.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile driverlib_ver.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/driverlib_ver.c -D nDEBUG -o $(MAKEFILE_DIR)driverlib_ver.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile event.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/event.c -D nDEBUG -o $(MAKEFILE_DIR)event.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile flash.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/flash.c -D nDEBUG -o $(MAKEFILE_DIR)flash.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile flashsafe.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/flashsafe.c -D nDEBUG -o $(MAKEFILE_DIR)flashsafe.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile gpio.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/gpio.c -D nDEBUG -o $(MAKEFILE_DIR)gpio.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile i2c.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/i2c.c -D nDEBUG -o $(MAKEFILE_DIR)i2c.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile i2s.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/i2s.c -D nDEBUG -o $(MAKEFILE_DIR)i2s.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile interrupt.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/interrupt.c -D nDEBUG -o $(MAKEFILE_DIR)interrupt.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile ioc.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/ioc.c -D nDEBUG -o $(MAKEFILE_DIR)ioc.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile osc.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/osc.c -D nDEBUG -o $(MAKEFILE_DIR)osc.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile prcm.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/prcm.c -D nDEBUG -o $(MAKEFILE_DIR)prcm.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile pwr_ctrl.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/pwr_ctrl.c -D nDEBUG -o $(MAKEFILE_DIR)pwr_ctrl.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile rfc.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/rfc.c -D nDEBUG -o $(MAKEFILE_DIR)rfc.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile setup.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/setup.c -D nDEBUG -o $(MAKEFILE_DIR)setup.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile smph.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/smph.c -D nDEBUG -o $(MAKEFILE_DIR)smph.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile spis.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/spis.c -D nDEBUG -o $(MAKEFILE_DIR)spis.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile ssi.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/ssi.c -D nDEBUG -o $(MAKEFILE_DIR)ssi.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile systick.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/systick.c -D nDEBUG -o $(MAKEFILE_DIR)systick.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile sys_ctrl.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/sys_ctrl.c -D nDEBUG -o $(MAKEFILE_DIR)sys_ctrl.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile timer.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/timer.c -D nDEBUG -o $(MAKEFILE_DIR)timer.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile trng.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/trng.c -D nDEBUG -o $(MAKEFILE_DIR)trng.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile uart.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/uart.c -D nDEBUG -o $(MAKEFILE_DIR)uart.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile udma.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/udma.c -D nDEBUG -o $(MAKEFILE_DIR)udma.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile vims.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/vims.c -D nDEBUG -o $(MAKEFILE_DIR)vims.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Compile watchdog.c
		@ $(COMPILER_TOOL) $(MAKEFILE_DIR)../../../driverlib/watchdog.c -D nDEBUG -o $(MAKEFILE_DIR)watchdog.o --no_clustering --debug --endian=little --cpu=Cortex-M3 -e --fpu=None -I $(MAKEFILE_DIR)../../.. -Oh --require_prototypes --silent
		@ echo IAR: Archive driverlib.lib
		@ $(ARCHIVER_TOOL) $(MAKEFILE_DIR)adi.o $(MAKEFILE_DIR)aon_batmon.o $(MAKEFILE_DIR)aon_event.o $(MAKEFILE_DIR)aon_ioc.o $(MAKEFILE_DIR)aon_rtc.o $(MAKEFILE_DIR)aon_wuc.o $(MAKEFILE_DIR)aux_adc.o $(MAKEFILE_DIR)aux_smph.o $(MAKEFILE_DIR)aux_tdc.o $(MAKEFILE_DIR)aux_timer.o $(MAKEFILE_DIR)aux_wuc.o $(MAKEFILE_DIR)chipinfo.o $(MAKEFILE_DIR)cpu.o $(MAKEFILE_DIR)crypto.o $(MAKEFILE_DIR)ddi.o $(MAKEFILE_DIR)debug.o $(MAKEFILE_DIR)driverlib_ver.o $(MAKEFILE_DIR)event.o $(MAKEFILE_DIR)flash.o $(MAKEFILE_DIR)flashsafe.o $(MAKEFILE_DIR)gpio.o $(MAKEFILE_DIR)i2c.o $(MAKEFILE_DIR)i2s.o $(MAKEFILE_DIR)interrupt.o $(MAKEFILE_DIR)ioc.o $(MAKEFILE_DIR)osc.o $(MAKEFILE_DIR)prcm.o $(MAKEFILE_DIR)pwr_ctrl.o $(MAKEFILE_DIR)rfc.o $(MAKEFILE_DIR)setup.o $(MAKEFILE_DIR)smph.o $(MAKEFILE_DIR)spis.o $(MAKEFILE_DIR)ssi.o $(MAKEFILE_DIR)systick.o $(MAKEFILE_DIR)sys_ctrl.o $(MAKEFILE_DIR)timer.o $(MAKEFILE_DIR)trng.o $(MAKEFILE_DIR)uart.o $(MAKEFILE_DIR)udma.o $(MAKEFILE_DIR)vims.o $(MAKEFILE_DIR)watchdog.o --create -o $(MAKEFILE_DIR)driverlib.lib
		@ rm -f $(MAKEFILE_DIR)*.o

# Deletes previous output and temporary files
clean :
		@ rm -fR $(MAKEFILE_DIR)*.o
		@ rm -fR $(MAKEFILE_DIR)*.lib
