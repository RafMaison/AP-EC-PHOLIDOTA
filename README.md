# AP-EC-PHOLIDOTA
Projeto que soma dois quadrados perfeitos
#include<stdio.h>
#include<math.h>
//soma de  dois quadrados perfeitos
int main(){
	float a1,a2,a3,a4,s1,s2,result;
	scanf("%f",&a1);
	scanf("%f",&a2);
	scanf("%f",&a3);
	scanf("%f",&a4);
	s1 = pow(a1,2) + 2*(a1*a2) + pow(a2,2);
	s2 = pow(a3,2) + 2*(a3*a4) + pow(a4,2);
	result = s1 + s2;
	printf("%2.2f",result);
}
