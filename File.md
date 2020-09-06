## WAP to implement strlen (), strcat (),strcpy () using the concept of Functions.
### 1. Length of the string (strlen)
The syntax of strlen is :

strlen(string);
It calculates the length of the string and returns its length. For example:
 
```
#include<string.h>

string = "Mumbai";

printf("Length = %d",strlen(string));
```
The above code displays 5, because Mumbai consists of 5 characters. Note: it does not count null character.
### 2. Joining two strings (strcat)
The syntax of strcat is

strcat(string1,string2);
Now it removes the null character from string1 and joins the first character of string2 at that position. Now string1 consists of both string1 and string2 in joined form. Example:
 
```
#include<string.h>

char string1[] = "Anti";

char string2[] = "Particle";

strcat(string1,string2);

printf("%s",string1); //display AntiParticle
```

### 3. Copying one string to another (strcpy)
The syntax of strcpy is 
 

strcpy(destination_string, source_string);
It copies the content of source_string to destination_string. Example:
 
```
#include<string.h>

char source[] = "Hello";

char destination[10]; //uninitialized

strcpy(destination,source);

printf("%s",destination); //prints Hello
```
