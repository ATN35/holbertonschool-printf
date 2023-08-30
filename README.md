[Titre] C - project _printf() int _printf(const char *format, ...)

[Description] The functions _printf() write output to stdout, the standard output stream. This function write the outpu\
t under the control of a format string that specifies how subsequent arguments are converted for output.

[Commande de compilation]
cc -Wall -Wextra -Werror -pedantic -std=gnu89 -Wno-format *.c

[Requirements] The main _printf function can be separated into more modular shorter functions More functionality can st\
ill be added (e.g. support field width specifiers, etc)

[Exemples] #include "main.h"

_printf("Character:[%c]\n", 'A');

[Man page] A man page is a detailed documentation of standard C language functions. These pages provide essential infor\
mation on how to use standard C functions and libraries appropriately. use the "man" command followed by the function n\
ame "_printf" to display the man page for this function.

[Flowchart] ![alt text](C:\Users\Antoine\Pictures\Saved Pictures\Flowchart.png)
