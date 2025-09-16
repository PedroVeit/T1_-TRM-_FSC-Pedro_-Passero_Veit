# T1-TRM-FSC
Trabalho de Fundamentos de Sistemas Computacionais
- Programação em Assembly no processador TRM.
- Grupo: Gustavo Silveira, Pedro Peccolo e Pedro Veit

O trabalho basea-se em resolver problemas utilizando a linguagem Assembly no processador TRM (Tiny RISC Machine).
O arquivo README contém a explicação simplificada de cada problema do trabalho.

Explicação do funcionamento dos códigos:
- Problema_1:
Guarda na memória os primeiros números ímpares, iniciando no endereço 0x20. Lê o valor de N, começando no 1 e soma de 2 em 2. O número gerado será colocado no espaço de memória ao lado do número anterior e, o processo segue até que todos os valores N sejam colocados na memória. 
<img width="1366" height="721" alt="image" src="https://github.com/user-attachments/assets/01e26c0d-0733-4af5-ace8-9b378fee9452" />
  
- Problema_2:
Gera os primeiros números da sequeência de Fibonacci e escreve cada número na memória a partir do endereço 0x30.
O programa inicia com os dois primeiros números de Fibonacci, 1 e 1. O programa calcula o próximo número somando os dois números anteriores a cada volta feita e, cada resultado é colocado em sequência na memória, um do lado do outro (pulando de 2 em 2, pois cada número ocupa uma palavra).
<img width="1366" height="726" alt="image" src="https://github.com/user-attachments/assets/58ba484a-0525-4fe4-b0c4-ed6bb02dca02" />
