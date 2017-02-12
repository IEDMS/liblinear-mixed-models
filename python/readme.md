```C
#include <stdio.h>
unsigned int fact_r(unsigned int n) {
    if (n == 0) {
        return 1;
    } else {
        return n * fact_r(n - 1);
    }
}
int main () {
	unsigned int f = 10;
	unsigned int val_r = fact_r(f);
	printf("Factorial (recursive) of %u is %u.\n",f,val_r);
}
```
