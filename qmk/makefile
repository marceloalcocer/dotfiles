QMK?=~/lib/qmk_firmware
KEYBOARD?=kyria/rev1
KEYMAP?=malcocer
BOOTLOADER?=dfu

.PHONY:
generic:
	${QMK}/util/docker_build.sh ${KEYBOARD}:${KEYMAP}:${BOOTLOADER}

.PHONY:
left:
	${QMK}/util/docker_build.sh ${KEYBOARD}:${KEYMAP}:${BOOTLOADER}-split-left

.PHONY:
right:
	${QMK}/util/docker_build.sh ${KEYBOARD}:${KEYMAP}:${BOOTLOADER}-split-right
