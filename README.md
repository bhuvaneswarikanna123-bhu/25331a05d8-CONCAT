# 25331a05d8-CONCAT
#include<stdio.h>
int main(){
char str1 [100],str2 [100];
int i=0,j=0;
printf("_25331a05d8_\n");
printf("enter first string:");
scanf( "%s",str1);
printf("enter second string:");
scanf( " %s ",str2);
while(str1[i]!='\0'){
i++;
}
while(str2[i]='\0'){
str1[i]=str2[i];
i++;
j++;
}
str1[i]='\0';
printf("concatenated string:%s",str1);
return 0;
}

