#include <studio.h>
void main (void){

int plata=0;
int requerido=2500;
int entregado=0;
int pesos100=0;
int pesos50=0;
int pesos20=0;
int pesos10=0;
int pesos5=0;
int pesos1=0;
printf("ingresar el monto")
scanf("%d", & plata);
if(plata<20){
   printf("monto invalido")
   return 1;
   }
if(plata>5000){
   printf("monto invalido, retire en caja")  
   return 2;
   for(plata=0; entregado<requerido;pesos100++
