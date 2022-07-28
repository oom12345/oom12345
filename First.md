#include <stdio.h>
int main() {
    int n, i;
    i=0;
    printf("Enter Your Number : ");
    scanf("%d" , &n);
    do{
        printf("%d" , i);
        i=i+1;
    }while(i<=n);
    

    return 0;
}

