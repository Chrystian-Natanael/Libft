# `Let's talk about: LIBFT` 💬

[<img src="https://raw.githubusercontent.com/Chrystian-Natanael/Aleatorios/master/Mycovers/CoverLIBFT.png" alt="libft_banner" width="1000">](https://github.com/Chrystian-Natanael/Aleatorios/blob/master/Mycovers/CoverLIBFT.png)

### `Select a language:`

<p align="center">
  <a href="https://github.com/Chrystian-Natanael/Libft/blob/main/README_BR.md">
  <img src="https://github.com/Chrystian-Natanael/Aleatorios/raw/master/Flags/Round_Brazil_Flag.png" alt="libft" width="50">
  </a>
  &nbsp &nbsp &nbsp &nbsp
  <a href="https://github.com/Chrystian-Natanael/Libft">
  <img src="https://github.com/Chrystian-Natanael/Aleatorios/raw/master/Flags/Round_EUA_Flag.png" alt="libft" width="50">
  </a>
</p>

## About the project

<p align="center">
  <a href="https://github.com/Chrystian-Natanael/Libft">
  <img src="https://github.com/Chrystian-Natanael/Aleatorios/raw/master/badges/libftm.png" alt="libft" width="125">
  </a>
</p>

Libft is the first major project of school 42, where the goal is to build our first static library of functions, in C language.
<br>
Throughout the project, we dealt with several challenges, such as understanding the concept of memory and its addresses, and a lot of programming logic.

# 📂 `Files` of library
Here I'm going to list the functions of libft, explaining a bit about them and what to worry about when starting your project.
<br>
Clicking on the function will take you to my libft in the code of the respective function.

<br>
<h3> 🦮 Summary: 🦮 <br>
<br>
<a href="https://github.com/Chrystian-Natanael/Libft#mandatory-part-1" style="color: inherit; text-decoration: none;">🔗 Mandatory part 1 </a> <br> <br>
<a href="https://github.com/Chrystian-Natanael/Libft#mandatory-part-2" style="color: inherit; text-decoration: none;">🔗 Mandatory part 2 </a> <br> <br>
<a href="https://github.com/Chrystian-Natanael/Libft#-bonus-part" style="color: inherit; text-decoration: none;">🔗 Bonus part </a>
<br>
</h3>
<br>

### `Mandatory part 1`:

## [📄 Isalpha](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_isalpha.c)

The `Isalpha` function takes a character (in ASCII code) and checks if it is an `alphabetic` character, and returns 0 if it is, and different from 0 if it is not.


## [📄 Isdigit](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_isdigit.c)

The `Isdigit` function takes a character (in ASCII code) and checks if it is an `digit` character (`0 - 9`), and returns 0 if it is, and different from 0 if it is not.

## [📄 Isalnum](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_isalnum.c)

Like the previous two functions, this one also takes an ASCII character and checks if it is an `alphabetic` character `or` a `digit`. returning 0 if it is, different from 0 if is not.

## [📄 Isascii](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_isascii.c)

As you may have noticed from the pattern, this function checks if the character is between the `ASCII` character `range` (`0 - 127`), the return is also 0 if it is and different from 0 if is not.

## [📄 Isprint](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_isprint.c)

The `Isprint` function takes a character (in ASCII code) and checks if it is a `printable character`, including spaces. It returns 0 if it is a printable character, and different from 0 if it is not.

## [📄 Strrchr](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strrchr.c)

This function searches for the `last` occurrence of a character in a `string`. It returns a pointer to the last occurrence of the character, or NULL if the character is not found in the string.

## [📄 Strlen](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strlen.c)

`Strlen` measures the `length` of a `string`. It returns the number of characters `before` the terminating `null` byte ('\0').

## [📄 Strncmp](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strncmp.c)

`Strncmp` compares up `to n` characters of `two strings`. It returns an integer less than, equal to, or greater than zero if the first n characters of s1 is found, respectively, to be less than, to match, or be greater than the first n characters of s2.

## [📄 Memset](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_memset.c)

`Memset` `fills` the first n bytes `of the memory` area pointed to by s `with` the constant `byte c`. It returns a pointer to the memory area s.

## [📄 Bzero](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_bzero.c)

Bzero `sets` the first `n bytes` of the area starting at s `to zero`.

## [📄 Memchr](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_memchr.c)

This function `scans` the initial `n bytes of the memory` area pointed to by s for the `first instance of c`. It returns a pointer to the matching byte or NULL if the character does not occur in the given memory area.

## [📄 Memcpy](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_memcpy.c)

`Memcpy copies` n `bytes from memory` area src `to memory area dest`. The memory areas must `not overlap`. It returns a pointer to dest.

## [📄 Memcmp](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_memcmp.c)

`Memcmp` `compares` the first n bytes of the `memory` areas `s1` and `s2`. It returns an integer less than, equal to, or greater than zero if s1 is found, respectively, to be less than, to match, or be greater than s2.

## [📄 Memmove](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_memmove.c)

`Memmove` `copies` n bytes from src to dest. The memory areas may overlap; it `correctly` handles `overlapping` areas.

## [📄 Strnstr](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strnstr.c)

This function `locates` the first `occurrence` of the `null-terminated` string needle in the string haystack, where not more than len characters are `searched`. Characters that appear after a '\0' character are not searched.

## [📄 Strlcpy](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strlcpy.c)

`Strlcpy copies` up to size `-1` characters from the NUL-terminated string src to dst, NUL-terminating the result.

## [📄 Strlcat](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strlcat.c)

`Strlcat` `appends` the NUL-terminated `string` src to the `end` of `dst`. It will append at most size -strlen(dst) -1 bytes, NUL-terminating the result.

## [📄 Toupper](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_toupper.c)

The `Toupper` function `converts` a lower-case letter `to` the corresponding `upper-case` letter.

## [📄 Tolower](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_tolower.c)

Conversely, the `Tolower` function converts an upper-case letter `to` the corresponding `lower-case` letter.

## [📄 Strchr](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strchr.c)

Strchr locates the first occurrence of c (converted to a char) in the string pointed to by s. The terminating null byte is considered part of the string; therefore if c is '\0', the functions locate the terminating '\0'.

## [📄 Calloc](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_calloc.c)

For `ft_calloc`(), we are allowed to use the `MALLOC`() function. This function allocates memory, just like malloc, but with the `difference` of `starting` the spaces of the allocated memory with `'\0'`.

### `Mandatory part 2`:

## [📄 Substr](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_substr.c)

`Creates` a `new substring` from a given string `s`. It starts at index start and has a maximum size len. Returns the substring or NULL if memory allocation fails.

## [📄 Strjoin](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strjoin.c)

`Joins` two strings `s1` and `s2` into a `new string`. Returns the new string or NULL if memory allocation fails.

## [📄 Strtrim](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strtrim.c)

`Trims the characters` specified in set from the `beginning` and `end` of s1. Returns the trimmed string or NULL if allocation fails.

## [📄 Split](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_split.c)

`splits a string` s using c as the `delimiter`. Returns an array of strings resulting from the split or NULL if allocation fails.

## [📄 Itoa](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_itoa.c)

`Converts` an `integer` n into a `string`. Handles negative numbers. Returns the string or NULL if allocation fails.

## [📄 Strmapi](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strmapi.c)

Applies `function f` to each character of string s. The function f receives the character's index and character as arguments. Returns a new `string created` from successive applications of f or NULL if allocation fails.

## [📄 Striteri](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_striteri.c)

Applies `function f` to each character of string s, with the character's index as the first argument. `Modifies each character` if necessary.

## [📄 Putchar_fd](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_putchar_fd.c)

Outputs the character c to the file `descriptor fd`.

## [📄 Putstr_fd](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_putstr_fd.c)

Outputs the string s to the file `descriptor` - `fd`.

## [📄 Putendl_fd](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_putendl_fd.c)

Outputs the string s to the `file descriptor`  - `fd`, followed by a newline.

## [📄 Putnbr_fd](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_putnbr_fd.c)

Outputs the integer n to the file descriptor fd.

### ⭐ `Bonus part`:

## [📄 ft_lstnew](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstnew.c)
Creates a new list node with `content`. Returns the new node or NULL if allocation fails.

## [📄 ft_lstadd_front](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstadd_front.c)
Adds the node `new` at the beginning of the list `lst`.

## [📄 ft_lstsize](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstsize.c)
Counts the number of nodes in a list `lst`. Returns the length of the list.

## [📄 ft_lstlast](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstlast.c)
Returns the last node of the list `lst`.

## [📄 ft_lstadd_back](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstadd_back.c)
Adds the node `new` at the end of the list `lst`.

## [📄 ft_lstdelone](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstdelone.c)
Frees the memory of the node's `lst` content using `del` function, then frees the node. The `next` memory is not freed.

## [📄 ft_lstclear](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstclear.c)
Deletes and frees the given node `lst` and every successor, using the function `del`. Sets the pointer to the list to NULL afterwards.

## [📄 ft_lstiter](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstiter.c)
Iterates over the list `lst` and applies the function `f` on the content of each node.

## [📄 ft_lstmap](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstmap.c)
Iterates over the list `lst`, applies the function `f` on each node's content, and creates a new list from the results. Uses `del` to delete the content of a node if needed.