EXECS=SphereTask
MPICC?=mpicc

all: ${EXECS}

SphereTask: SphereTask.c
	${MPICC} -o SphereTask SphereTask.c

clean:
	rm -f ${EXECS}
