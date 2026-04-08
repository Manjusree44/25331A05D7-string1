#include<stdio.h>
#include<string.h>

int main(){
char str1[100], str2[100];
char copystr[100];

printf(“25331a05d7\n”);
printf("enter the first string");
scanf(" %s ",  str1);
printf("enter the second string");
scanf(" %s ", str2);

printf("enter the length of the first string: %lu", strlen(str1));
printf("enter the length of the second string: %lu", strlen(str2));

strcpy(copystr, str1);
printf("the string that is copied is: %s", copystr);
strcat(str1, str2);
printf("\n the concatenated string : %s", str1);

if(strcmp(copystr, str1) == 0){
printf("the strings are equal");
}
else{
printf("the strings are not equal");
}
return 0;
}


