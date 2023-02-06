include ../../Makefile_compile
patricia: patricia.c patricia_test.c
	${CROSS_CC}  ${STATIC_FLAGS} patricia.c patricia_test.c  -o patricia

clean:
	rm -rf patricia output*
