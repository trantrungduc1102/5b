# 5b
nhom 5b
#include <stdio.h>
int main() {
	int n, p=1; float s=0;
	printf ("nhap n:");
	scanf ("%d", &n);
	for ( int i=1;i<=n;i++)
	{
		p=p*i;
		s=s+p;
	}
	printf("\n ket qua do ban tim ra la : %f", s);
	return 0;
} 

#include <stdio.h>
#include <conio.h>
int main () {
	int n, a, b, c;
	printf ("nhap so nguyen duong n(co 3 chu so)");
	scanf ("%d",&n);
	a = n/100;
	b = ((n%100/10));
	c = (n%10);
	printf ("- chu so hang tram : %d\n", a);
	printf("- chu so hang chuc: %d\n", b);
	printf("- chu so hang don vi: %d\n", c);
	getch ();
}
