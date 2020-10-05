# micropython firmwares

## Compilando MicroPython com exemplo principal

- [Compilando micropython/ports/stm32 (para placas Pyboard, etc)](https://gitlab.com/rcolistete/computacaofisica-privado/-/blob/master/Compilando_MicroPython/Compilando_MicroPython_STM32.md)

- [Compilando micropython/ports/nrf (incluindo BBC Micro:bit)](https://gitlab.com/rcolistete/computacaofisica-privado/-/blob/master/Compilando_MicroPython/Compilando_MicroPython_nRF.md)

Firmwares em placas Pyboard-D SF2 e Micro:bit

```pybv11_dp_v1.12-665-g60f5b941e_2020-08-27.dfu```: firmware com precisão dupla nativa;

```pybv11_sp_96mhz_v1.12-665-g60f5b941e_2020-08-27.dfu``` firmware com precisão simples e clock default de 96 MHz;

```pybv11_sp_thread_v1.12-657-g37e1b5c89_2020-08-27.dfu``` firmware que permite multithreading (é usado sempre que um programa tem que executar a mesma função (tarefa) muitas vezes) com precisão simples;

```pybd-sf2_sp_v1.12-665-g60f5b941e_2020-08-22.dfu``` firmware com precisão simples nativa.

```microbit_v1.12-665-g60f5b941e_2020-08-27.hex```  firmware com micropython atualizado para Micro:bit.
