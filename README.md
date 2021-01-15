# include<stdio.h>
void tek_cift(int s1)
{
     if( s1 % 2 == 0 )
        printf("Sayi cifttir");
     else
        printf("Sayi tektir");
}
int main()
{
    int s1;
    
    printf("Lutfen sayi giriniz");
    scanf("%d", &s1);
    tek_cift(s1);
    return 0;
}
