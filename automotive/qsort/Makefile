FILE1 = qsort_small.c
FILE2 = qsort_large.c
include ../../Makefile_compile
all: qsort_small qsort_large

qsort_small: qsort_small.c Makefile
	${CROSS_CC}  ${STATIC_FLAGS} qsort_small.c  -o qsort_small -lm
qsort_large: qsort_large.c Makefile
	${CROSS_CC}  ${STATIC_FLAGS} qsort_large.c  -o qsort_large -lm

clean:
	rm -rf qsort_small qsort_large output*
