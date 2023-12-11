## NUMERICOS

Genérico: Number

space | signed | unsigner
--|--|--
8-bit	 |  i8	    |   u8
16-bit	 |  i16	    |   u16
32-bit	 |  i32	    |   u32
64-bit	 |  i64	    |   u64
128-bit	 |  i128	|   u128
arch	 |  isize	|   usize


## TEXTO

Genérico: String

- str

    "< value >"

    Cadenas de texto

- char

    '< value >'

    Caracteres individuales


## Booleanos

Genérico: Boolean
    - true
    - false



# Lists

Genérico: List

    - Array de tipado dinámica
        [str, int, str, Object]

    - Array estricta

        (type|size, size)[values...]

        (str)["a", "b", "c"]

        (u8)[1, 2, 3, 4]



# Objetos

Genérico: Object

    - Object

        {
            key: value
        }