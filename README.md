# hello-world
Programming is fun!
Programming in C is fun!
#include<stdio.h>

int main(int argc, char const *argv[]) {
	int i;
	for (i=0; i<argc; i++){
		printf("%d:%s\n", i, argv[i]);
	}
	
	return 0;
} 

