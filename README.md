# epoll_packaging-abridgment
epoll_packaging abridgment

# 编译
```shell
➜  epoll_packaging-abridgment git:(main) make
gcc -g -w  -c    main.c
gcc -g -w  -c    comm_epoll.c
gcc -g -w  -c    comm.c
gcc -o  epoll_demo main.o comm_epoll.o comm.o
➜  epoll_packaging-abridgment git:(main) ✗
```

# 运行
```shell
➜  epoll_packaging-abridgment git:(main) ✗ ./epoll_demo
```
