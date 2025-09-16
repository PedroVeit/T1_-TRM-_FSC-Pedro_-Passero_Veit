# T1-TRM-FSC
Trabalho de Fundamentos de Sistemas Computacionais
- Programação em Assembly no processador TRM.
- Grupo: Gustavo Silveira, Pedro Peccolo e Pedro Veit

O trabalho basea-se em resolver problemas utilizando a linguagem Assembly no processador TRM (Tiny RISC Machine).
O arquivo README contém a explicação simplificada de cada problema do trabalho.

Explicação do funcionamento dos códigos:
- Problema_1:
- Guarda na memória os primeiros números ímpares, iniciando no endereço 0x20. Lê o valor de N, começando no 1 e soma de 2 em 2. O número gerado será colocado no espaço de memória ao lado do número anterior e, o processo segue até que todos os valores N sejam colocados na memória. 
<img width="1366" height="721" alt="image" src="https://github.com/user-attachments/assets/01e26c0d-0733-4af5-ace8-9b378fee9452" />
  

- Problema_2:
- Gera os primeiros números da sequência de Fibonacci e escreve cada número na memória a partir do endereço 0x30.
O programa inicia com os dois primeiros números de Fibonacci, 1 e 1. O programa calcula o próximo número somando os dois números anteriores a cada volta feita e, cada resultado é colocado em sequência na memória, um do lado do outro (pulando de 2 em 2, pois cada número ocupa uma palavra).
<img width="1366" height="726" alt="image" src="https://github.com/user-attachments/assets/58ba484a-0525-4fe4-b0c4-ed6bb02dca02" />


- Problema_3:
- Percorre os números que foram guardados entre os endereços 0x40 e 0x80 para encontrar o maior inteiro positivo. O programa lê o inteiro atual e, ignora se ele não for positivo e compara com o inteiro maior que foi encontrado.
Caso seja maior, o número é atualizado e, no fim do programa, o inteiro mais alto encontrado é colocado no endereço 0x90.
<img width="1366" height="727" alt="image" src="https://github.com/user-attachments/assets/6177582c-1fa6-4789-922f-9a375d98fc17" />


- Problema_8:
- O programa faz a leitura da String armazenada na memória, passa por cada caracter até chegar ao fim e em seguida manda para saída o testo sugerido.
- ![0a67f22c-6c80-4bb3-a9ac-508492c8a9af](https://github.com/user-attachments/assets/5f759806-aff3-4069-8799-ecde17b2c6f7)


