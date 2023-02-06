include ../../Makefile_compile
rijndael: aes.c aes.h aestab.h aesxam.c Makefile
	${CROSS_CC}  ${STATIC_FLAGS} -o rijndael aes.c aesxam.c

clean:
	rm -rf rijndael output*
