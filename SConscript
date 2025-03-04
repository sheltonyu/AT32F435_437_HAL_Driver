from building import *
import os

cwd = GetCurrentDir()
path = [os.path.join(cwd, 'inc')]
src_path = os.path.join(cwd, 'src')

CPPDEFINES = ['USE_STDPERIPH_DRIVER']

src = [
os.path.join(src_path, 'at32f435_437_acc.c'),
os.path.join(src_path, 'at32f435_437_adc.c'),
os.path.join(src_path, 'at32f435_437_can.c'),
os.path.join(src_path, 'at32f435_437_crc.c'),
os.path.join(src_path, 'at32f435_437_crm.c'),
os.path.join(src_path, 'at32f435_437_dac.c'),
os.path.join(src_path, 'at32f435_437_debug.c'),
os.path.join(src_path, 'at32f435_437_dma.c'),
os.path.join(src_path, 'at32f435_437_dvp.c'),
os.path.join(src_path, 'at32f435_437_edma.c'),
os.path.join(src_path, 'at32f435_437_emac.c'),
os.path.join(src_path, 'at32f435_437_ertc.c'),
os.path.join(src_path, 'at32f435_437_exint.c'),
os.path.join(src_path, 'at32f435_437_flash.c'),
os.path.join(src_path, 'at32f435_437_gpio.c'),
os.path.join(src_path, 'at32f435_437_i2c.c'),
os.path.join(src_path, 'at32f435_437_misc.c'),
os.path.join(src_path, 'at32f435_437_pwc.c'),
os.path.join(src_path, 'at32f435_437_qspi.c'),
os.path.join(src_path, 'at32f435_437_scfg.c'),
os.path.join(src_path, 'at32f435_437_sdio.c'),
os.path.join(src_path, 'at32f435_437_spi.c'),
os.path.join(src_path, 'at32f435_437_tmr.c'),
os.path.join(src_path, 'at32f435_437_usart.c'),
os.path.join(src_path, 'at32f435_437_usb.c'),
os.path.join(src_path, 'at32f435_437_wdt.c'),
os.path.join(src_path, 'at32f435_437_wwdt.c'),
os.path.join(src_path, 'at32f435_437_xmc.c'),
]

group = DefineGroup('libraries', src, depend = ['PKG_USING_AT32F435_437_HAL_DRIVER'], CPPPATH = path, CPPDEFINES = CPPDEFINES)

Return('group')
