# Conversor BCD-7SEG
Este é um projeto de um conversor BCD-7SEG desenvolvido em SystemVerilog. O objetivo do conversor é permitir a implementação de um relógio utilizando um display de 7 segmentos.

## Funcionamento
O conversor BCD-7SEG recebe quatro palavras BCD na entrada (𝑋3, 𝑋2, 𝑋1, 𝑋0) e aciona apenas os leds correspondentes ao número em questão no display de 7 segmentos. Por exemplo, quando 𝑋3𝑋2𝑋1𝑋0==“0001”, apenas B e C devem ser 1 (ou seja, os led B e C devem ficar acesos).
