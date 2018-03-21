# C
/*sınıf bulma*/

#include<stdio.h>
int main() {

int snf;

printf("ögrencinin sinif bilgisini gir\n");
scanf("%d",&snf);
switch(snf)
{
	
	case 1: printf("1.sinif"); break;
	case 2: printf("2.sinif"); break;
		case 3: printf("3.sinif"); break;
		case 4: printf("4.sinif"); break;
		case 5: printf("5.sinif"); break;
		case 6: printf("6.sinif"); break;
		case 7: printf("7.sinif"); break;
		case 8: printf("8.sinif"); break;
		default: printf("böyle bir ilkoku sinifi yoktur"); break;
	
	}	

	
	return 0;
}
