# Program-Penyederhanaan
    #include<stdio.h>

    int main()
    {
        int a,b,sisa,x,y;
        printf("masukan bilangan = ");
        scanf("%d",&a);
        printf("masukan pembilang = ");
        scanf("%d",&b);
        sisa=a/b;
        x=a-sisa;
        y=a/b;
        if(sisa==0)
            printf("\n%d/%d",a,b,y);
        if(sisa>0)
            printf("\n%d/%d=%d %d/%d",a,b,y,sisa,b);
        printf("\n");
    return 0;
    }
# Hasil
![img](https://raw.githubusercontent.com/AminPriadi/Program-Penyederhanaan/master/menyederhanakan.png)
