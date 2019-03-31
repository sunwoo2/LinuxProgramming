
all:
	gcc -D_REENTRANT -o thread1 thread1.c -lpthread
	gcc -o thread2           thread2.c           -lpthread
	gcc -o thread3_sem       thread3_sem.c       -lpthread
	gcc -o thread3a_sem      thread3a_sem.c      -lpthread
	gcc -o thread4_mutex     thread4_mutex.c     -lpthread
	gcc -o thread5_detach    thread5_detach.c    -lpthread
	gcc -o thread6_sched     thread6_sched.c     -lpthread
	gcc -o thread7_cancel    thread7_cancel.c    -lpthread
	gcc -o thread8           thread8.c           -lpthread
	gcc -o thread8a          thread8a.c          -lpthread

clean:
	rm -rf thread1 thread2 thread3_sem thread3a_sem thread4_mutex thread5_detach \
        thread6_sched thread7_cancel thread8 thread8a
