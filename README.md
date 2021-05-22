# Cache Lab
**Course Information**: CS359 Computer Architecture, for SJTU CS
This is the second project:  Understanding Cache Memories

## complie
```makefile
make clean
make
```

## run small test
./csim -s 2 -E 2 -b 2 -t traces/yi2.trace

## run csim-ref for test
./csim-ref -s 2 -E 2 -b 2 -t traces/yi2.trace
## run evaluation
 ./test-csim