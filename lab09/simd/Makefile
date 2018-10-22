CC=gcc
C_FLAGS=--std=c99

clean:
	rm -f simd > /dev/null 2>&1

simd: simd.c common.h
	$(CC) $(C_FLAGS) simd.c -o simd
