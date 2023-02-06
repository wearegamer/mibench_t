include ../../Makefile_compile
all:  dijkstra_large dijkstra_small

dijkstra_large: dijkstra_large.c Makefile
	${CROSS_CC}  ${STATIC_FLAGS} dijkstra_large.c -o dijkstra_large

dijkstra_small: dijkstra_small.c Makefile
	${CROSS_CC}  ${STATIC_FLAGS} dijkstra_small.c -o dijkstra_small 

clean:
	rm -rf dijkstra_large dijkstra_small output*
