#include<stdio.h>
#include<string.h>

int shortChar(char string[100]){
   char temp;
   int i, j;
   int n = strlen(string);
   for (i = 0; i < n-1; i++) {
      for (j = i+1; j < n; j++) {
         if (string[i] > string[j]) {
            temp = string[i];
            string[i] = string[j];
            string[j] = temp;
         }
      }
   }
   return string;
}

int disChar(char name[100]){
    name= shortChar(name);
   int n = strlen(name);
   int count=0,i;

   for (i = 1; i<n; i++)
    {
        if (name[i] != name[i -1] )

        {
            count++;
        }

    }
    count++;
   return count;
}

int main(){
    int b;
    char name[100];
    scanf("%s",name);
    b = disChar(name);
    if(b%2==0)
    {
        printf("CHAT WITH HER!\n");
    }
    else
    {
        printf("IGNORE HIM!\n");
    }
    return 0;
}
