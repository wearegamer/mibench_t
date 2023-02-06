OBJ = main.o fftmisc.o  fourierf.o
FILE = main.c fftmisc.c  fourierf.c

include ../../Makefile_compile
fft: ${OBJ} Makefile
	${CROSS_CC}  ${STATIC_FLAGS}  ${OBJ} -o fft -lm
fftmisc.o: fftmisc.c
	${CROSS_CC}  ${STATIC_FLAGS}  -c fftmisc.c
fourierf.o: fourierf.c
	${CROSS_CC}  ${STATIC_FLAGS}  -c fourierf.c
main.o: main.c
	${CROSS_CC}  ${STATIC_FLAGS}  -c main.c

clean:
	rm -rf *.o fft output*
