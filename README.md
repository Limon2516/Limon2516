#include <stdio.h>
#include <stdlib.h>

int main (){
	
	system("COLOR 1D");
      float Celsius = 18;
      float Fahrenheit = 86;
      float temp;
      
      printf("\033[0;32m]");
      printf("Celsius a Fahrenheit");
      printf("= %f\n", (9/5.0)*Celsius+32);
      
      printf("\033[0;33m]");
      printf("Farenheit a Celsius");
      printf("= %f\n", (Fahrenheit-32.0)*(5.0/9.0));
      
      printf("\033[0;0m]");
      printf("\t\t\t\t\t\t\t\t\t\t\t David Limon Gonzalez\n");
      
       return 0;
}
