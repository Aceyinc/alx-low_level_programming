#  0x12-singly_linked_lists
## C , agorithm, Data structure

## Read or watch:

Linked Lists
Google
Youtube

## general
When and why using linked lists vs arrays
How to build and use linked lists

```
/**
 * struct list_s - singly linked list
 * @str: string - (malloc'ed string)
 * @len: length of the string
 * @next: points to the next node
 *
 * Description: singly linked list node structure
 */
typedef struct list_s
{
    char *str;
    unsigned int len;
    struct list_s *next;
} list_t;
```
