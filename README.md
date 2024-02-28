# SISTEMAS DIGITAIS E MICROPROCESSADORES

Curso de graduação da enhaguera em egenharia elétrica


## TEMA 03

### AULA 01 - Introdução

Arquitetura de sistema de microprocessadores e microcontroladores.

Historicamente falando quando falamos de "processadores" e "microprocessados"
Projeto ENIAC foi a primeiro computador a realizar calculos balisticos. tinha dimensões enormes e foi o inicio da computação.
Em 1947 foi criado os "transitores" que foram ebarcados em CI ( circuitos integrados ) 

### AULA 02 - microcontrolador vs Microprocessador

* __Microcontrolador__

É um pequeno computador que recebe instruções programadas, computando informações é composto de processador e periféricos. usado em controles de processos. usados para processos mais simples.

>[!note]
>Arduíno não é um microcontrolador, ele é uma "plataforma de prototipagem" que possui microcontrolador integrado ao sistema.

<br>

![image](https://github.com/xing-wang-kai/ENGENHARIA_SISTEMAS_DIG_E_MICROPROCESSADORES/assets/94153912/f68146bc-ae85-4a53-a564-f3d1bec96844)
<br>

* __Microprocessador__

é apenas um chip que necessita de periféricos externos que não é capaz de armazenar dados, pode realizar processos mais complexos e precisa de outros periféricos para funcionar não possui uma memória e tem um custo mais alto.

<br>

![image](https://github.com/xing-wang-kai/ENGENHARIA_SISTEMAS_DIG_E_MICROPROCESSADORES/assets/94153912/e4b24469-0cb3-4974-a0af-66bd4624174e)

### AULA 03 - Conjuntos de instruções RISC e SISC


Instruções e técnicas para que operações seja excutada. São como os dados são enviados e processados por equipamentos.

para um microcontrolador executar instruções ele precisam ser programados e eles só entedem linguagem de baixo nivel bits.

Para hardwarear precisa de uma CPU - unidade central de processamento e ULA - unidade de lógica aritimica, memória e registroia.

<br>

![image](https://github.com/xing-wang-kai/ENGENHARIA_SISTEMAS_DIG_E_MICROPROCESSADORES/assets/94153912/30fd01fb-f7ae-4b1f-8699-8890f9297262)

__von Neumann__ é uma arquitetura Sincrona que processa dados um a um antes de registrar proximas instruções.

<br>

![image](https://github.com/xing-wang-kai/ENGENHARIA_SISTEMAS_DIG_E_MICROPROCESSADORES/assets/94153912/1c964142-ec72-4cbd-beb4-1f8cd4a285e5)

__arquitetura de harvard__ instruções de dados são paralelos


Arquitetura do microprocessador ATmega 328P;
<br>

![image](https://github.com/xing-wang-kai/ENGENHARIA_SISTEMAS_DIG_E_MICROPROCESSADORES/assets/94153912/bbb30e59-0351-482e-b5fb-8abf1564a893)

<br>

![image](https://github.com/xing-wang-kai/ENGENHARIA_SISTEMAS_DIG_E_MICROPROCESSADORES/assets/94153912/a0a64d62-2c69-4042-b12c-c82d9bfc1ef9)

RISC precisa somente um ciclo de maquina - mas não resolver instruções complexas
CISC precisa de mais ciclos para instruções - excuta operações complexas

<br>

![image](https://github.com/xing-wang-kai/ENGENHARIA_SISTEMAS_DIG_E_MICROPROCESSADORES/assets/94153912/cba41530-4de2-4900-96b3-bea2a97f659f)


### AULA 04 - Arquitetura ATmega328P

<br>

![image](https://github.com/xing-wang-kai/ENGENHARIA_SISTEMAS_DIG_E_MICROPROCESSADORES/assets/94153912/5de893c9-1e05-4fa7-ae40-de3e870de3ca)


### AULA 05 - Periféricos complexos e básicos

POrtas digitais com os pinos de entrar básica em bits positivo ou negativos. Periféricos complexos são entradas para grandezas analógicas.
<br>

![image](https://github.com/xing-wang-kai/ENGENHARIA_SISTEMAS_DIG_E_MICROPROCESSADORES/assets/94153912/c969b0d5-3f40-46a6-960b-38f5f370b078)

![image](https://github.com/xing-wang-kai/ENGENHARIA_SISTEMAS_DIG_E_MICROPROCESSADORES/assets/94153912/e069475b-46e7-4666-a2e1-44c3c0af7608)

Portas digitais podem ser entradas ou saídas.
PC PD PB são portas birecionais que recebem e enviam sinais de entrada e saída de 0 e 5v sendo hight ou low 
PullUP sempre manda 5v para porta e fecha o VCC
pulldow sempre manda 0 para porta e abre o VCC


* _GPR_ -> Registrado de propósito Gral 
* _SFR_ - > proposito de funções especiais - regristram direcionamentos especificos.




