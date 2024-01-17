# `Vamos conversar sobre a: LIBFT` 💬

[<img src="https://raw.githubusercontent.com/Chrystian-Natanael/Aleatorios/master/Mycovers/CoverLIBFT.png" alt="libft_banner" width="1000">](https://github.com/Chrystian-Natanael/Aleatorios/blob/master/Mycovers/CoverLIBFT.png)

### `Selecione a linguagem:`

<p align="center">
  <a href="https://github.com/Chrystian-Natanael/Libft/blob/main/README_BR.md">
  <img src="https://github.com/Chrystian-Natanael/Aleatorios/raw/master/Flags/Round_Brazil_Flag.png" alt="libft" width="50">
  </a>
  &nbsp &nbsp &nbsp &nbsp
  <a href="https://github.com/Chrystian-Natanael/Libft">
  <img src="https://github.com/Chrystian-Natanael/Aleatorios/raw/master/Flags/Round_EUA_Flag.png" alt="libft" width="50">
  </a>
</p>

## Sobre o projeto

<p align="center">
  <a href="https://github.com/Chrystian-Natanael/Libft">
  <img src="https://github.com/Chrystian-Natanael/Aleatorios/raw/master/badges/libftm.png" alt="libft" width="125">
  </a>
</p>

A Libft é o primeiro projeto significativo da escola 42, no qual o objetivo é construir nossa primeira biblioteca estática de funções, na linguagem C.
<br>
Ao longo do projeto, enfrentamos diversos desafios, como compreender o conceito de memória e seus endereços, além de muita lógica de programação.

# 📂 `Arquivos` da biblioteca
Aqui vou listar as funções da libft, explicando um pouco sobre cada uma e o que deve ser considerado ao iniciar o seu projeto.
<br>
Clicando na função, você será direcionado para minha libft no código da respectiva função.
<br>
<h3> 🦮 Sumário: 🦮 <br>
<br>
<a href="https://github.com/Chrystian-Natanael/Libft/blob/main/README_BR.md#mandat%C3%B3rio-parte-1" style="color: inherit; text-decoration: none;">🔗 Mandatório parte 1 </a> <br> <br>
<a href="https://github.com/Chrystian-Natanael/Libft/blob/main/README_BR.md#mandat%C3%B3rio-parte-2" style="color: inherit; text-decoration: none;">🔗 Mandatório parte 2 </a> <br> <br>
<a href="https://github.com/Chrystian-Natanael/Libft/blob/main/README_BR.md#-parte-b%C3%B4nus" style="color: inherit; text-decoration: none;">🔗 Parte bônus </a>
<br>
</h3>
<br>

### `Mandatório parte 1`:

## [📄 Isalpha](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_isalpha.c)

A função `Isalpha` recebe um caractere (no código ASCII) e verifica se é um caractere `alfabético`, retornando 0 se for, e diferente de 0 se não for.

## [📄 Isdigit](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_isdigit.c)

A função `Isdigit` recebe um caractere (no código ASCII) e verifica se é um caractere `numérico` (`0 - 9`), retornando 0 se for, e diferente de 0 se não for.

## [📄 Isalnum](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_isalnum.c)

Assim como as duas funções anteriores, esta também recebe um caractere em código ASCII e verifica se é um caractere `alfabético` `ou` um `dígito`, retornando 0 se for, e diferente de 0 se não for.

## [📄 Isascii](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_isascii.c)

Como você pode ter percebido pelo padrão, esta função verifica se o caractere está dentro do `intervalo` de caracteres `ASCII` (`0 - 127`), retornando também 0 se estiver e diferente de 0 se não estiver.

## [📄 Isprint](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_isprint.c)

A função `Isprint` recebe um caractere (no código ASCII) e verifica se é um `caractere imprimível`, incluindo espaços. Retorna 0 se for um caractere imprimível, e diferente de 0 se não for.

## [📄 Strrchr](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strrchr.c)

Esta função busca a `última` ocorrência de um caractere em uma `string`. Retorna um ponteiro para a última ocorrência do caractere, ou NULL se o caractere não for encontrado na string.

## [📄 Strlen](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strlen.c)

`Strlen` mede o `comprimento` de uma `string`. Retorna o número de caracteres `antes` do byte nulo de terminação `NULL` ('\0').

## [📄 Strncmp](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strncmp.c)

`Strncmp` compara até `n` caracteres de `duas strings`. Retorna um inteiro menor que, igual a, ou maior que zero se os primeiros n caracteres de s1 forem, respectivamente, menores que, iguais a, ou maiores que os primeiros n caracteres de s2.

## [📄 Memset](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_memset.c)

`Memset` preenche os primeiros n bytes da área de memória apontada por s com o byte constante c. Retorna um ponteiro para a área de memória s.

## [📄 Bzero](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_bzero.c)

`Bzero` define os primeiros n bytes da área iniciando em s como zero.

## [📄 Memchr](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_memchr.c)

Esta função varre os primeiros n bytes da área de memória apontada por s em busca da `primeira instância de c`. Retorna um ponteiro para o byte correspondente ou NULL se o caractere não ocorrer na área de memória fornecida.

## [📄 Memcpy](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_memcpy.c)

`Memcpy copies` n `bytes from memory` area src `to memory area dest`. The memory areas must `not overlap`. It returns a pointer to dest.

## [📄 Memcmp](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_memcmp.c)

`Memcmp` compara os primeiros n bytes das áreas de memória s1 e s2. Retorna um inteiro menor que, igual a, ou maior que zero se s1 for, respectivamente, menor que, igual a, ou maior que s2.

## [📄 Memmove](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_memmove.c)

`Memmove` copia n bytes de src para dest. As áreas de memória podem se sobrepor; ele lida `corretamente` com áreas `sobrepostas`.

## [📄 Strnstr](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strnstr.c)

Esta função `localiza` a `primeira ocorrência` da string needle (terminada por null) na string haystack, onde não mais do que len caracteres são `pesquisados`. Caracteres que aparecem após um caractere '\0' não são pesquisados.

## [📄 Strlcpy](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strlcpy.c)

`Strlcpy` copia até size `-1` caracteres da string src terminada por NULL para dst, terminando o resultado com `NULL`.

## [📄 Strlcat](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strlcat.c)

`Strlcat` `anexa` a string src terminada por NUL ao `final` de dst. Ele anexará no máximo size - strlen(dst) - 1 bytes, terminando o resultado com NUL.

## [📄 Toupper](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_toupper.c)

A função `Toupper` converte uma letra minúscula `para` a letra maiúscula correspondente.

## [📄 Tolower](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_tolower.c)

Por outro lado, a função `Tolower` converte uma letra maiúscula `para` a letra minúscula correspondente.

## [📄 Strchr](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strchr.c)

A função `Strchr` localiza a primeira ocorrência de c (convertido para um char) na string apontada por s. O byte nulo de terminação é considerado parte da string; portanto, se c for '\0', a função localiza o '\0' de terminação.

## [📄 Calloc](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_calloc.c)

Para `ft_calloc`(), é permitido usar a função `MALLOC`(). Essa função aloca memória, assim como o malloc, mas com a `diferença` de `iniciar` os espaços da memória alocada com `'\0'`.

### `Mandatório parte 2`:

## [📄 Substr](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_substr.c)

`Cria` uma `nova substring` a partir de uma string `s` fornecida. Ela começa no índice start e tem um tamanho máximo de len. Retorna a substring ou NULL se a alocação de memória falhar.

## [📄 Strjoin](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strjoin.c)

`Junta` duas strings `s1` e `s2` em uma `nova string`. Retorna a nova string ou NULL se a alocação de memória falhar.

## [📄 Strtrim](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strtrim.c)

`Remove os caracteres` especificados em set do `início` e `fim` de s1. Retorna a string resultante após o corte ou NULL se a alocação falhar.

## [📄 Split](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_split.c)

`Divide uma string` s usando c como o `delimitador`. Retorna um array de strings resultante da divisão ou NULL se a alocação falhar.

## [📄 Itoa](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_itoa.c)

`Converte` um número `inteiro` n em uma `string`. Lida com números negativos. Retorna a string resultante ou NULL se a alocação falhar.

## [📄 Strmapi](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_strmapi.c)

Aplica a `função f` a cada caractere da string s. A função f recebe o índice do caractere e o caractere como argumentos. Retorna uma `nova string criada` a partir de aplicações sucessivas de f ou NULL se a alocação falhar.

## [📄 Striteri](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_striteri.c)

Aplica a `função f` a cada caractere da string s, com o índice do caractere como primeiro argumento. `Modifica cada caractere` se necessário.

## [📄 Putchar_fd](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_putchar_fd.c)

Envia o caractere c para o descritor de arquivo `fd`.

## [📄 Putstr_fd](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_putstr_fd.c)

Envia a string s para o descritor de arquivo - `fd`.

## [📄 Putendl_fd](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_putendl_fd.c)

Envia a string s para o `descritor de arquivo` - `fd`, seguida por uma quebra de linha.

## [📄 Putnbr_fd](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_putnbr_fd.c)

Envia o número inteiro n para o descritor de arquivo fd.

### ⭐ `Parte bônus`:

## [📄 ft_lstnew](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstnew.c)

Cria um novo nó de lista com `conteúdo`. Retorna o novo nó ou NULL se a alocação falhar.

## [📄 ft_lstadd_front](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstadd_front.c)

Adiciona o nó `new` no início da lista `lst`.

## [📄 ft_lstsize](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstsize.c)

Conta o número de nós em uma lista `lst`. Retorna o comprimento da lista.

## [📄 ft_lstlast](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstlast.c)

Retorna o último nó da lista `lst`.

## [📄 ft_lstadd_back](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstadd_back.c)

Adiciona o nó `new` no final da lista `lst`.

## [📄 ft_lstdelone](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstdelone.c)

Libera a memória do conteúdo do nó `lst` usando a função `del`, e em seguida, libera o próprio nó. A memória de `next` não é liberada.

## [📄 ft_lstclear](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstclear.c)

Exclui e libera o nó fornecido `lst` e todos os seus sucessores, usando a função `del`. Define o ponteiro da lista como NULL posteriormente.

## [📄 ft_lstiter](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstiter.c)

Itera sobre a lista `lst` e aplica a função `f` no conteúdo de cada nó.

## [📄 ft_lstmap](https://github.com/Chrystian-Natanael/Libft/blob/main/source/ft_lstmap.c)

Itera sobre a lista `lst`, aplica a função `f` no conteúdo de cada nó e cria uma nova lista a partir dos resultados. Usa `del` para excluir o conteúdo de um nó, se necessário.