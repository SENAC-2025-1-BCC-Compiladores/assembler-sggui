**Guilherme Santos Guimarães**

## **ASSEMBLER**

- Compilar o código:
```sh
gcc -o assembler Tokenizer.c main.c Assembler.c -Wall
```
- Após isso, para finalizar o teste, executar:
```sh
./assembler <arquivo_de_codigo>.txt <output>.mem
```
## **OBSERVAÇÃO**
O arquivo criado  (entrada.txt) foi feito apenas para teste, não necessariamente precisa ser ele. Pode ser um outro TXT.
Caso queira alterar a operação ou os valores que serão somados, deve-se alterar o entrada.txt com o código desejado.

Ao rodar, ele criará um .dump e substituirá dentro do output.mem o binário para upload no Neander.
O .dump foi criado apenas para um debug mais fácil, não precisa ser utilizado.
O arquivo que deve ser submetido ao Neander é o output.mem.

