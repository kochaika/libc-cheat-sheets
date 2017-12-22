# <string.h>
Inclusion of the `<string.h>` header may also make visible all symbols from `<stddef.h>`.
## Defines
```
NULL
size_t
```
## Functions
```
void    *memccpy(void *, const void *, int, size_t);
void    *memchr(const void *, int, size_t);
int      memcmp(const void *, const void *, size_t);
void    *memcpy(void *, const void *, size_t);
void    *memmove(void *, const void *, size_t);
void    *memset(void *, int, size_t);
===========
char    *strcat(char *, const char *);
char    *strchr(const char *, int);
int      strcmp(const char *, const char *);
int      strcoll(const char *, const char *);
char    *strcpy(char *, const char *);
size_t   strcspn(const char *, const char *);
char    *strdup(const char *);
char    *strerror(int);
size_t   strlen(const char *);
char    *strncat(char *, const char *, size_t);
int      strncmp(const char *, const char *, size_t);
char    *strncpy(char *, const char *, size_t);
char    *strpbrk(const char *, const char *);
char    *strrchr(const char *, int);
size_t   strspn(const char *, const char *);
char    *strstr(const char *, const char *);
char    *strtok(char *, const char *);
char    *strtok_r(char *, const char *, char **);
size_t   strxfrm(char *, const char *, size_t);

```
### memccpy
`void *memccpy(void *s1, const void *s2, int c, size_t n);`
#### Description
The memccpy() function copies bytes from memory area s2 into s1, stopping after the first occurrence of byte c (converted to an unsigned char) is copied, or after n bytes are copied, whichever comes first. If copying takes place between objects that overlap, the behaviour is undefined.
#### Return
The memccpy() function returns a pointer to the byte after the copy of c in s1, or a null pointer if c was not found in the first n bytes of s2.
#### Example
```
char s1[30]={0};
char s2[]="What a nice string for memccpy function!";
char *res = memccpy(s1,s2,'s', 20);
printf("%zd\n", res-s1); // 13
PRINT_STR((char*)memccpy(s1,s2,'!', 20)); // (null)
```

### memchr
```
void *memchr(const void *s, int c, size_t n);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```

### memcmp
```
int memcmp(const void *s1, const void *s2, size_t n);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```

### memcpy
```
void *memcpy(void *s1, const void *s2, size_t n);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```

### memmove
```
void *memmove(void *s1, const void *s2, size_t n);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```

### memset
```
void *memset(void *s, int c, size_t n);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```

### strcat
```
char *strcat(char *s1, const char *s2);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```

### strchr
```
char *strchr(const char *s, int c);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```

### strcmp
```
int strcmp(const char *s1, const char *s2);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```

### strcoll
```
int strcoll(const char *s1, const char *s2);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```

### strcpy
```
char *strcpy(char *s1, const char *s2);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strcspn
```
size_t strcspn(const char *s1, const char *s2);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strdup
```
char *strdup(const char *s1);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strerror
```
char *strerror(int errnum);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strlen
```
size_t strlen(const char *s);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strncat
```
char *strncat(char *s1, const char *s2, size_t n);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strncmp
```
int strncmp(const char *s1, const char *s2, size_t n);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strncpy
```
char *strncpy(char *s1, const char *s2, size_t n);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strpbrk
```
char *strpbrk(const char *s1, const char *s2);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strrchr
```
char *strrchr(const char *s, int c);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strspn
```
size_t strspn(const char *s1, const char *s2);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strstr
```
char *strstr(const char *s1, const char *s2);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strtok
```
char *strtok(char *s1, const char *s2);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strtok_r
```
char *strtok_r(char *s, const char *sep, char **lasts);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### strxfrm
```
size_t strxfrm(char *s1, const char *s2, size_t n);
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```


### function_name
```
prototype
```
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```
