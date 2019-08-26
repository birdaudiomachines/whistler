CXX = g++
CXXFLAGS = -Wall -g

chirp: chirp.o Feather.o
	$(CXX) $(CXXFLAGS) -o chirp chirp.o Feather.o

chirp.o: chirp.cpp Feather.h
	$(CXX) $(CXXFLAGS) -c chirp.cpp

Feather.o: Feather.h
