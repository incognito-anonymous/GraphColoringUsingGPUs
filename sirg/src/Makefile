BIN=../bin/

sirg: 
	nvcc -O3 -arch=sm_60 graphColoring.cu sirgL32.cu sirg.cu -lcurand -lcusparse -o $@
	mv $@ $(BIN)

clean:
	rm sirg
