# Principios de funcionamento de computadores 2

- Registradores funcionam como variáveis

- Códigos compilados são especificos para arquiteturas

## passos de compilação

- Compilador: Traduz o código de alto nivel para um programa em assembly

- Assembler: traduz o código em assembly para código de máquina
    - Cria um arquivo objeto
    - Tradução um-pra-um

- Linker: Pega todos os procedimentos compilados independentemente em objetos e junta em uma única saida.
    - Uma forma de evitar de ter que compilar o programa inteiro de uma vez
    - Posiciona o s módulos de código e dados simbolicamente na memória
    - Determina o enereço dos labels de instruções e dados
    - Realiza todas as referencias internas e externas

- Loader
    - Carrega o arquivo objeto na memória principal para prepará-lo para a exeução
    - Loader no UNIX:
        - Le o cabeçalho do aquivo executavel e determina o tamanho do segmento de textos e de dados
        - aloca um espaco de enderecamento gande o suficiente para caber os segmentos
        - copia as ntrucoes e os dados do arquivo executavel para a memori
        - copia os parametros(se existirem) para o programa principal na piha
        - inicializa os registradores e posicona s ponteiros em posicoes de memoria
        - Salta para a rotina de inicio e chama a rotina principal do programa. Quando a rotina principal retorna, a rotina de iniciotermina o programa com uma chamada de sistema exit

## Microcontrolador x microprocessador

Microcontrolador - computador em um CHIP

Microprocessador - somente CPU no chip

## ASIC, ASIP, FPGA

### ASIC - application specific integrated circuit

- circuito integrado projetado especificamente para um aplicação ou propósito especial

- Vantagem:
    - Desempenho
    - Eficiência

- Desvantagem
    - Pouca flexibilidade
    - Zero extensabilidade

### ASIP - Application specific instruction set processor

- Projeto do hardware mais dedicado que um General Purpose Porcessor
- Arquitetura programada por SW projetada para executar algumas tarefas mais eficientemente
- Conjunt de instrucoes especifico a um dominio de aplicacoes
- meio termo entre GPP e ASIC

### FPGA - Field Programmable Gate Arrays

- Tambem chamados de arquiteturas reconfiguraveis
- Em uma arquitetura reconfiguravel é possivel mudar o comportamento do hardware atraves da mudanca da funcao tecnica que a arquitetura realiza
- Formado por uma matriz de elementos reconfiguraveis

- desvantagem:
    - Tempo de confguracao
    - Memoria de configuracao
    - Potencia alta para realizar a configuracao

