QMK?=~/lib/qmk_firmware
KEYBOARD?=kyria/rev1
KEYMAP?=malcocer
BOOTLOADER?=dfu

.PHONY:
generic:
	cd ${QMK} && ./util/docker_build.sh ${KEYBOARD}:${KEYMAP}:${BOOTLOADER}

.PHONY:
left:
	cd ${QMK} && ./util/docker_build.sh ${KEYBOARD}:${KEYMAP}:${BOOTLOADER}-split-left

.PHONY:
right:
	cd ${QMK} && ./util/docker_build.sh ${KEYBOARD}:${KEYMAP}:${BOOTLOADER}-split-right
