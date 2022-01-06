# RTR-105
Datormācība(pamatkurss)elektroniskā klade 
## Dungeons and Dragons 5E
**Welcome to Dungeons and Dragons,adventurer**
>Hope,power and wishes will help you in Dungeons And Dragons 5E 
>
![Welcome to DnD](https://comiczone.ru/wp-content/uploads/2019/10/c433543859742e9843f3269d7c5e89863bb2e13e.png)
### Let's play,if you have time and imagination
### 40 000 000 souls
![image](https://user-images.githubusercontent.com/56522929/139584018-497e629d-45b6-4619-ade4-7a36d1c53514.png)
### dec2bin
#include <stdio.h>
long size_of_array = 8;
const char * restrict main()
{
char x, index, c;
char bin[size_of_array];
printf("Please enter any natural number(ex: 5) \n");
scanf("%c", &x);
index = (size_of_array - 1);
while(index >= 0)
{
bin[index] = x & 1;
index--;
x >>= 1;
}
printf("Your Converted number: ");
for(c=0; c<size_of_array; c++)
{
printf("%d", bin[c]);
}
{
printf("\n");
}
{
return 0;
}
}
