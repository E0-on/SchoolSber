#include <stdio.h>
#include <math.h>

int main()
{
	float x, y;
	if (scanf("%f", &x) == 1 && x != 0) {
	y = 7e-3 * pow(x, 4) + ((22.8 * pow(x, (1/3)) - 1000) * x + 3) / (pow(x, 2) / 2) - x * pow((10 + x), (2/x)) - 1.01;
	printf("%.1f", y);}
	else {
		printf("n/a");
	}
	return 0;
}
