# SHA256CUDA

Modified for [SHAllenge](https://shallenge.quirino.net/)

`$ nvcc -o hash_program -O2 main.cu`

Example run:

```
$ ./hash_program
Prefix message : Hello/
Suffix message : +worlds
Nonce : 0
Difficulty : 6

Shared memory is 16KB
209572 hash(es)/s
Nonce : 8388608
Hello/27329144+worlds
000000ff9bf3100d718e9c4ae46d72aba42fa5fa703e484b5e761d970319c8fd
```
