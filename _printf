#include "main.h"

/*
 * _printf - custome version of printf
 * @format: the output format to be printed
 *
 * Return: numbers of characters printed
 */

int _printf(const char *format, ...)
{
	va_list arg;
	int print;

	va_start (arg, format);
	print = vfprintf (stdout, format, arg);
	va_end (arg);

	return (print);
}
