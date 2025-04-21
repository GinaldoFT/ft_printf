<p align="center">
  <img src="https://raw.githubusercontent.com/GinaldoFT/GinaldoFT/main/42covers/cover-ft_printf.png" alt="libft cover" />
</p>

# 🖨️ ft_printf

A custom implementation of the standard `printf` function in C. This project replicates the behavior of `printf`, including format parsing and handling various data types — all without using the standard C library.

---

## 🔍 Project Overview

The goal of `ft_printf` is to recreate the standard `printf` function, handling formatted output with precision and performance. It's a core project at 42 that requires deep understanding of variadic functions, memory management, and string formatting.

<p align="center">
  <img src="https://raw.githubusercontent.com/GinaldoFT/GinaldoFT/main/42Badges/ft_printfe.png" width="100" alt="ft_printf badge"/>
</p>

---

## ✅ Supported Conversions

Your `ft_printf` handles the following format specifiers:

| Specifier | Description          |
|-----------|----------------------|
| `%c`      | Character            |
| `%s`      | String               |
| `%p`      | Pointer address      |
| `%d`      | Signed decimal int   |
| `%i`      | Signed decimal int   |
| `%u`      | Unsigned decimal int |
| `%x`      | Hex (lowercase)      |
| `%X`      | Hex (uppercase)      |
| `%%`      | Literal `%`          |
