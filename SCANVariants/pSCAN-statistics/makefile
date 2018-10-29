all: pscan

pscan: .obj/main.o .obj/Graph.o .obj/Utility.o
	g++ -std=c++11 .obj/main.o .obj/Graph.o .obj/Utility.o -o pscan

.obj/main.o: main.cpp
	g++ -c -O3 -std=c++11 -o .obj/main.o main.cpp

.obj/Graph.o: Graph.cpp
	g++ -c -O3 -std=c++11 -o .obj/Graph.o Graph.cpp

.obj/Utility.o: Utility.cpp
	g++ -c -O3 -std=c++11 -o .obj/Utility.o Utility.cpp

clean:
	rm -rf *o .obj/
	mkdir .obj
