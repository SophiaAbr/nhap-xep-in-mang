# nhap-xep-in-mang
#include <conio.h>
#include <iostream.h>
#define max 100

void nhap(int[], int);
void sapxep(int[], int);
void xuat(int[], int);

void main()
{


void sapxep(int a[], int n)
{
	int i, j, tg;
	for (i = 0; i < n - 1; i++)
		for (j = i + 1; j < n; j++)
			if (a[i] > a[j])
			{
				tg = a[i];
				a[i] = a[j];
				a[j] = tg;
			}
}
