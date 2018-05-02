# Desafio de Lógica 1

Dado o seguinte código em portugol:

```portugol
var
 x,y,z : inteiro
inicio
	se (x < y+z) e (y < z+x) e (z < x+y) então
		se (y=z) e (x=y) então
			escreva('Triângulo Equilátero')
		senão 
			se (x=y) ou (y=z) ou (x=z) então 
				escreva('Triângulo Isósceles')
			senão
				escreva('Triângulo Escaleno')
           		fim_se
      		fim_se
	senão
		escreva('Não é triangulo’)
	fim_se
fim 
```

Escreva o resultado dado através da função "escrever" para as seguintes entradas:

- x:1  y:2  z:3 
- x:4  y:4  z:4
- x:2  y:2  z:4
- x:3  y:4  z:5


# Instruções

- [x] Clone este repositório na sua máquina;
- [x] Resolva as questões acima e responda no arquivo respostas.txt; 
- [x] Faça um commit e push para uma branch com o formato "sua ID + nome do repositorio" ex.: leodegeus7DesafioLogica
