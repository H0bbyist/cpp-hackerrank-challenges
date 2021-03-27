#include <stdio.h>

void update(int *a,int *b) {
    int sum = *a + *b;
    int diff;

    if (*a > *b){
        diff = *a - *b;
    } else if (*b > *a){
        diff = *b - *a;
    } else {
        diff = 0;
    }

    *a = sum;
    *b = diff;
}

int main() {
    int a, b;
    int *pa = &a, *pb = &b;
    
    scanf("%d %d", &a, &b);
    update(pa, pb);
    printf("%d\n%d", a, b);

    return 0;
}
