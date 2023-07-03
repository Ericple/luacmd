cmake_minimum_required(VERSION 3.25)
project(luacmd C)

set(CMAKE_C_STANDARD 17)

add_executable(luacmd lua.c lua.h luaconf.h lprefix.h lauxlib.h lualib.h lauxlib.c lapi.c lapi.h ldebug.c ldebug.h lstate.c lstate.h ldo.c ldo.h lfunc.c lfunc.h lgc.c lgc.h lmem.c lmem.h lobject.c lobject.h lctype.c lctype.h llimits.h lstring.c lstring.h lvm.c lvm.h lopcodes.c lopcodes.h ltable.c ltable.h ltm.c ltm.h ljumptab.h lundump.c lundump.h lzio.c lzio.h lcode.c lcode.h llex.c llex.h lparser.c lparser.h lopnames.h loslib.c lbaselib.c lcorolib.c ldunp.c linit.c liolib.c lmathlib.c loadlib.c lstrlib.c ltablib.c luac.c lutf8lib.c ldblib.c)
