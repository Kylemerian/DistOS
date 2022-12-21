all:
	export TMPDIR=/tmp
	mpic++ -o task task1.cpp
	mpirun -np 16  ./task
clean:
	rm task
