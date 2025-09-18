# T1-TRM-FSC
Trabalho de Fundamentos de Sistemas Computacionais
- Programação em Assembly no processador TRM.
- Grupo: Gustavo Silveira, Pedro Peccolo e Pedro Veit

O trabalho basea-se em resolver problemas utilizando a linguagem Assembly no processador TRM (Tiny RISC Machine).
O arquivo README contém a explicação simplificada de cada problema do trabalho.

Explicação do funcionamento dos códigos:
- Problema_1: Guarda na memória os primeiros números ímpares, iniciando no endereço 0x20. Lê o valor de N, começando no 1 e soma de 2 em 2. O número gerado será colocado no espaço de memória ao lado do número anterior e, o processo segue até que todos os valores N sejam colocados na memória. 
<img width="1366" height="725" alt="image" src="https://github.com/user-attachments/assets/97274d79-240f-409b-ab50-062b7972ae5f" />
 
- Problema_2: Gera os primeiros números da sequência de Fibonacci e escreve cada número na memória a partir do endereço 0x30.
O programa inicia com os dois primeiros números de Fibonacci, 1 e 1. O programa calcula o próximo número somando os dois números anteriores a cada volta feita e, cada resultado é colocado em sequência na memória, um do lado do outro (pulando de 2 em 2, pois cada número ocupa uma palavra).
<img width="1366" height="726" alt="image" src="https://github.com/user-attachments/assets/58ba484a-0525-4fe4-b0c4-ed6bb02dca02" />

- Problema_3: Percorre os números que foram guardados entre os endereços 0x40 e 0x80 para encontrar o maior inteiro positivo. O programa lê o inteiro atual e, ignora se ele não for positivo e compara com o inteiro maior que foi encontrado.
Caso seja maior, o número é atualizado e, no fim do programa, o inteiro mais alto encontrado é colocado no endereço 0x90.
<img width="1366" height="726" alt="image" src="https://github.com/user-attachments/assets/5c0a2a98-f3df-4f4d-904e-564e52576e4e" />

- Problema_4: Solicita ao usuário para digitar 5 números inteiros e, guarda esses valores na memória a partir do endereço 0x40, "copia" os inteiros para ondereço de 0x90.
Se o número é par, soma 1 para transformá-lo em um número ímpar.
Se for ímpar, mantém como está.
No print do programa abaixo utilizamos os valores: 2, 4, 6, 8 e 10.
<img width="1366" height="725" alt="image" src="https://github.com/user-attachments/assets/e60364b0-8f71-431c-965a-bbc336f025fc" />

- Problema_5: Procura entre os endereços 0x60 e 0x70 por dois números cuja soma seja igual a 10. O programa percorre as posições em pares e, quando encontra um par que soma 10, ele salva os endereços das duas posições no endereço 0x80 e 0x90.
Se não existir nenhum par válido, apenas encerra a execução. 
No programa utilizamos como entrada os valores: 2, 4, 6, 8 e 10 novamente.
<img width="1366" height="726" alt="image" src="https://github.com/user-attachments/assets/bca3a762-ad8b-4c0d-bb86-b04fa908aeae" />

- Problema_6: Inverte os dados salvos entre os endereços 0x40 e 0x60 no mesmo lugar, apontando para o primeiro e o último byte, troca os dois de posição, avança um passo do início e volta um passo do fim, repetindo o processo até chegar ao meio.
O programa foi criado dentro do endereço 0x40 e 0x60, invertendo os valores.
<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/c38c89fc-1787-4f0a-9039-fb699423dd77" />

- Problema_8: O programa faz a leitura da String armazenada na memória, passa por cada caracter até chegar ao final e por fim manda o texto sugerido para a saída.
![0a67f22c-6c80-4bb3-a9ac-508492c8a9af](https://github.com/user-attachments/assets/5f759806-aff3-4069-8799-ecde17b2c6f7)


- Problema_9: O código verifica se uma palavra é um palíndromo, lendo em 0x60 o tamanho da palavra sugerida, depois seleciona os caracteres a partir do 0x70. Compara a letra da esquerda com a da direita, avançando até o centro. Se tudo der certo o simulador apresenta a letra "T" de True, caso contrário apresenta a letra "F" de False.
<img width="1366" height="726" alt="image" src="https://github.com/user-attachments/assets/e9c1baf5-e97f-43cb-a4f7-0b2d59c03f42" />

- Prblema_10: Processa os primeiros N caracteres de um texto, localizado na memória a partir do endereço 0x60. Conta a ocorrência de cada vogal ('a', 'e', 'i', 'o', 'u') independentemente de serem maiúsculas ou minúsculas.
Para cada vogal encontrada, um contador específico é incrementado.
<img width="1366" height="722" alt="image" src="https://github.com/user-attachments/assets/33548f5c-5f86-48e5-98f0-b02416c940d7" />
