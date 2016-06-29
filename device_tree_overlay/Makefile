.PHONY: all install clean uninstall

all: BB_DCAN1-00A0.dtbo

BB-DCAN1-00A0.dtbo: BB-DCAN1-00A0.dts
	dtc -O dtb -o BB-DCAN1-00A0.dtbo -b 0 -@ BB-DCAN1-00A0.dts

install:
	cp BB-DCAN1-00A0.dtbo /lib/firmware/

clean: 
	rm -f *.dtbo

uninstall: 
	rm -f /lib/firmware/BB-DCAN1-00A0.dtbo
