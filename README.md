# Libft
>The aim of this project is to compile static library called _libft_ that have 
recoded _libc_ functions. It is then been used in another projects.

## functions:

- memset
- bzero
- memcpy
- memccpy
- memmove
- memchr
- memcmp
- strlen
- strlcpy
- strlcat
- strchr
- strrchr
- strnstr
- strncmp
- atoi
- isalpha
- isdigit
- isalnum
- isascii
- isprint
- toupper
- tolower

## Additional functions:

name|prototype|description
---|---|---
ft_substr|char *ft_substr(char const *s, unsigned int start, size_t len);|Allocates (with malloc(3)) and returns a substring from the string ’s’. The substring begins at index ’start’ and is of maximum size ’len’.
ft_strjoin|char *ft_strjoin(char const *s1, char const *s2);|Allocates (with malloc(3)) and returns a new string, which is the result of the concatenation of ’s1’ and ’s2’.
ft_strtrim|char *ft_strtrim(char const *s1, char const *set);|Allocates (with malloc(3)) and returns a copy of ’s1’ with the characters specified in ’set’ removed from the beginning and the end of the string.
ft_split|char **ft_split(char const *s, char c);|Allocates (with malloc(3)) and returns an array of strings obtained by splitting ’s’ using the character ’c’ as a delimiter. The array must be ended by a NULL pointer.
ft_itoa|char *ft_itoa(int n);|Allocates (with malloc(3)) and returns a string representing the integer received as an argument. Negative numbers must be handled.
ft_strmapi|char *ft_strmapi(char const *s, char (*f)(unsigned int, char));|Applies the function ’f’ to each character of the string ’s’ to create a new string (with malloc(3)) resulting from successive applications of ’f’.
ft_putchar_fd|void ft_putchar_fd(char c, int fd);|Outputs the character ’c’ to the given file descriptor.
ft_putstr_fd|void ft_putstr_fd(char *s, int fd);|Outputs the string ’s’ to the given file descriptor.
ft_putendl_fd|void ft_putendl_fd(char *s, int fd);|Outputs the string ’s’ to the given file descriptor, followed by a newline.
ft_putnbr_fd|void ft_putnbr_fd(int n, int fd);|Outputs the integer ’n’ to the given file descriptor.


