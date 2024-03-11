# c-using-concatenation-function
#include <stdio.h>
#include <string.h>
#define MAX_SIZE 100
int main()
{
  char str1[MAX_SIZE], str2[MAX_SIZE];
  printf("ENTER FIRST STRING:  ");
  scanf("%s", str1);
  printf("ENTER SECOND STRING: ");
  scanf("%s", str2);
  strcat(str1, str2);
  printf("Concatenated string = %s",str1);
  return 0;
}
