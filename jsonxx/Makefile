CXXFLAGS=-Werror -Wall -g -std=c++11

jsonxx_test: jsonxx_test.cc jsonxx.o

jsonxx.o: jsonxx.h jsonxx.cc

test: jsonxx_test
	./jsonxx_test

.PHONY: clean
clean:
	del *.o jsonxx_test.exe  -rf
