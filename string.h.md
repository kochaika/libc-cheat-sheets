# <string.h>

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

### function_name
`prototype`
#### Description
Function description
#### Return
Return value description
#### Example
```
// using function code example
```
