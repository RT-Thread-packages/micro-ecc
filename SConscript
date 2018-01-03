# RT-Thread building script for component

from building import *

cwd = GetCurrentDir()
src = Split('''
micro-ecc/uECC.c
''')
CPPPATH = [cwd + '/micro-ecc']

group = DefineGroup('micro-ecc', src, depend = ['PKG_USING_MICROECC'], CPPPATH = CPPPATH)

Return('group')
