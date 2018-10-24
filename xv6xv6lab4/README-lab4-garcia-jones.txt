Definitions of syscalls:
------------------------------------------
	defs.h
	sysproc.c
	syscall.c
	syscall.h
	user.h
	usys.S


Other files edited:
-------------------------------------------
proc.c       :The logic of each syscall
proc.h       :process table, added isthread to identify a thread vs process
types.h      :Included typedef for lock_t
threads.c    :modified to work with mutex lock for accessing critical section
Makefile     :added compile instructions for threads.c
