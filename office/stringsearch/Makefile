FILE1 = bmhasrch.c  bmhisrch.c  bmhsrch.c  pbmsrch_small.c 
FILE2 = bmhasrch.c  bmhisrch.c  bmhsrch.c  pbmsrch_large.c 
include ../../Makefile_compile
all: search_small search_large

search_small: ${FILE1} Makefile
	${CROSS_CC}  ${STATIC_FLAGS} ${FILE1}  -o search_small

search_large: ${FILE2} Makefile
	${CROSS_CC}  ${STATIC_FLAGS} ${FILE2}  -o search_large

clean:
	rm -rf search_small search_large output*
