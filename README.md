# NUMBER-TRIANGLE



// Online C compiler to run C program online
#include <stdio.h>
#include <stdlib.h>
int main() {
    int i,j, k, l, n;
    printf("ENTER A NUMBER\n");
    scanf("%d", &n);
    for(i=1; i<=n; i++){
        for(j=1; j<=n-i; j++){
            printf(" ");
        }
        for(k=1; k<=i; k++){
            printf("%d", k);
            
        }
        for(l=i-1; l>=i; l--)
        {
            printf("%d", l);
        }
        printf("\n");
    }
return 0;
}
