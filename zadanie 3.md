#Rozwiązania 
zadanie - wypisac elementy tablicy w odwrotnej kolejności

```c
#include<stdio.h>
int main() {
  int tabela[]={1,2,4,6,12};
  int i=0;
  for(i=4;i>=0;i--){
  
    printf("\n%d\n",tabela[i] );
  }

  return 0;
}  
 
