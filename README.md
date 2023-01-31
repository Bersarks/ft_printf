## PRINTF 1.0.0

- This is a simple implementation of the printf function in C. It is not a complete implementation, but it does support the following format specifiers:
	- > %d - %i-> integer
		- Simple: ft_printf("%d", 42); or ft_printf("%i", 42);
		- Output: 42
	- > %u -> unsigned integer
		- Simple: ft_printf("%u", 42);
		- Output: 42
	- > %x -> hexadecimal
		- Simple: ft_printf("%x", 42);
		- Output: 2a
	- > %X -> hexadecimal
		- Simple: ft_printf("%X", 42);
		- Output: 2A
	- > %c -> character
		- Simple: ft_printf("%c", 'a');
		- Output: a
	- > %s -> string
		- Simple: ft_printf("%s", "Hello World");
		- Output: Hello World
	- > %p -> pointer (hexadecimal)
		- Simple: ft_printf("%p", &str);
		- Output: 0x and the hexadecimal value of the pointer

> NOTE: This project has some features of printf-specific working potentials as mentioned, please test with the format markers mentioned above.
