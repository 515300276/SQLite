from building import *

cwd = GetCurrentDir()
src = ['sqlite3.c']
CPPPATH = [cwd]

group = DefineGroup('sqlite', src, depend = ['RT_USING_DFS', 'PKG_USING_SQLITE'], CPPPATH = CPPPATH)

Return('group')
