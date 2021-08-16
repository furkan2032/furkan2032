- 👋 Hi, I’m @furkan2032
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
furkan2032/furkan2032 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include "stdafx.h"
#include "math.h"
#include "conio.h"
#include "stdlib.h"
#include "float.h"
#include "ctype.h"
#include "string.h"


void main()
{
	int x, y, z;
	printf("              HESAP MAKINESI UYGULAMASINA HOS GELDINIZ :) \n  \n          ");
	printf("islem yapmak istediginiz sayinizi giriniz : ");
	scanf_s("%d", &x);
	printf("                  islem yapmak istediginiz sayinizi giriniz : ");
	scanf_s("%d", &y);
	printf("\n");
	printf("toplamak icin  ------> 1");
	printf("\n");
	printf("cikarmak icin  ------> 2");
	printf("\n");
	printf("carpmak  icin  ------> 3");
	printf("\n");
	printf("bolmek   icin  ------> 4");
	printf("\n");
	printf(" yukaridan hangi islemi yapmak istiyorsaniz seciniz  :");
	scanf_s("%d", &z);
		if (z == 1)
			printf("isleminizin sonucu =%d", x + y);
		if (z == 2)
			printf("isleminizin sonucu =%d", x - y);
		if (z == 3)
			printf("isleminizin sonucu =%d", x * y);
		if (z == 4)
			printf("isleminizin sonucu =%d", x / y);
		printf("\n");
		printf("bizi tercih ettiginiz icin tesekkur ederiz iyi gunler dileriz :)");
	getchar();
	getchar();
}

