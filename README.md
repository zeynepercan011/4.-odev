# 4.-odev

//her bir kucuk kareye 1 kareden 4 kare �izdik toplam 5 kare oldu nxn e g�re hesaplayal�m.

#include<stdio.h>
int squ(int);
int main()
{
	int n;
	printf("n sayisini giriniz.");
	scanf("%d" , &n);
	
	printf("toplam kare sayisi: %d" , squ(n));
}

int squ(int n)
{
	if(n==1){
		return 1;
	}
	
else
{
	int sonuc;
	sonuc=(n-1)*4+1;
	
	return sonuc;
}
}
