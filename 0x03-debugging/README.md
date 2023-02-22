# #0x03. C - Debugging

<a href="https://twitter.com/aceyink">aceyinc 2023</a>

Debugging
Rubber Duck
 Debugging

## learning objectives
Debugging is the process of finding and fixing errors in software that prevents it from running correctly. As you become a more advanced programmer and an industry engineer, you will learn how to use debugging tools such as gdb or built-in tools that IDEs have. However, it’s important to understand the concepts and processes of debugging manually.
gcc flags -Wall -Werror -pedantic -Wextra -std=gnu89 What are header files and how to to use them with #include
```
gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
;
betty-style.pl and betty-doc.pl
```

```
#include <stdio.h>                                                                                  

/**                                                                                                 
 * main - debugging example                                                                         
 * Return: 0                                                                                        
 */                                                                                                 
int main(void)                                                                                      
{                                                                                                   
        char *hello = "Hello, World!";                                                              

        for (i = 0; hello[i] != '\0'; i++)                                                          
        {                                                                                           
                printf("%c", hello[i]);                                                             
        }                                                                                           

        printf("\n");                                                                               

        return (0);                                                                                 
}                                                                                                   
```
