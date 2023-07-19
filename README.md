# MPI Ping-Pong

This code sends a message from node A to node B and back (a so called ping-pong) using the blocking send and receive constructs.

## Compile

```shell
 mpic++ ping-pong.cpp -o ping-pong
```

## Run
```shell
 mpirun -np 2 ping-pong
```
