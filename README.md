mmseg
=====

MMSEG simple word segmenter in C++ 11 

  * Based on http://yongsun.me/2013/06/simple-implementation-of-mmseg-with-python/
  * Data files from mmseg4j https://code.google.com/p/mmseg4j/
  * Compile with:
  * In main.cpp
  * If use src/Mmseg.hpp,
  * g++ -Ofast -march=native -funroll-loops -o mmseg -std=c++11 main.cpp 
  * If use src/Mmseg.h
  * g++ -Ofast -march=native -funroll-loops -o mmseg -std=c++11  main.cpp src/Mmseg.cpp 
Usage
===
	see main.cpp

