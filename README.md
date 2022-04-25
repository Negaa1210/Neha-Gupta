# Neha-Gupta
# Saqid loves super heroes he used to imagine himself to be a hero. One day his teachers was taking a class about shapes and asked the students to find the Area of the triangle using Heron’s formula. Saqid misheard this a Hero’s formula and was curious to discover the Hero’s formula for finding the area of the triangle. Help Saqid to solve his math problem by using the correct logic in your code. Functional Description: Area=sqrt(s(s-a)(s--b)(s-c)), where S=(a+b+c)/2 and  a, b and c are the sides of triangle. Constraints: 1=&lt;a=&lt;15 1=&lt;b=&lt;15 1=&lt;c=&lt;15 Input Format: Only Line of input has 3 integers representing 3 sides of the triangle separated by a space. Output Format: Print the area of triangle with only two values after the decimal point.
#include <stdio.h>
#include <math.h>
int main()
{

int a,b,c;
float s,area;
scanf("%d %d %d",&a,&b,&c);
s=(a+b+c)/2;
area=sqrt(s*(s-a)*(s-b)*(s-c));
printf("%0.2f",area);
	return 0;
}
