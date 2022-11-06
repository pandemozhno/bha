# bha hashing

![Black Hole Logo](https://github.com/pandemozhno/bha/blob/main/logo.png?raw=true)

simple ease algoritm for hashing with losses

Example
`let data = '101010010010100100111101001010101010101001'
 
 let result = hasing(data)
 
 console.log(result) // 000010001110100000000
`

data collapsed for pairs 10 || 01 = 0 in result, 11 || 00 = 1 in result, and cycle result as data for 1 bit 0 or 1

> the same one, once nothing


размышления к дальнейшему развитию
дано:
- общие количество битов
- количество циклов до 1 бита
- остаток при не чётном количество битов в цикле
- количество 1 и 0 при каждом цикле
- конечный бит
- предъидёщий бит и следующий

Недостаток:
- при изначальном одинаковым количеством бит но хотябы одной разной пары разные файлы придут к одному хешу
