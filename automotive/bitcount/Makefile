FILE = bitcnt_1.c bitcnt_2.c bitcnt_3.c bitcnt_4.c bitcnts.c bitfiles.c bitstrng.c bstr_i.c 
include ../../Makefile_compile
bitcnts: ${FILE} Makefile
	${CROSS_CC}  ${STATIC_FLAGS} ${FILE} -o bitcnts

clean:
	rm -rf bitcnts output*
