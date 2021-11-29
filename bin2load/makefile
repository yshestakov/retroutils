

bin2load:	main.c loadBinary.c saveLda.c conversions.c bsd/exec.h bsd/a.out.h
	$(CROSS_COMPILE)$(CC) -O main.c loadBinary.c saveLda.c conversions.c -o bin2load

bin2load.exe:	main.c loadBinary.c saveLda.c conversions.c bsd/exec.h bsd/a.out.h
	/usr/bin/i686-w64-mingw32-gcc-9.3-win32 -o bin2load.exe -static -O main.c loadBinary.c saveLda.c conversions.c
