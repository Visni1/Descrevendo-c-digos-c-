TRABALHO ADS
TURMA: ADS 
Alunos: Lucas Vasques, José Roberto, Vinicius Gabriel

EX8
#include <stdio.h> // Inclui uma biblioteca.
#include <conio.h> // Inclui uma biblioteca.
#include <math.h> // Inclui uma biblioteca.
#include <iostream> // Inclui uma biblioteca.

main() // Função principal do programa.
{
    float cotacao, us; // Declara duas variáveis.

    printf("============== Money Like a Boss ==============\n"); // Mensagem para indicar o início do programa.
    printf("Informe Cotacao DOLAR: "); // Solicita que o usuário insira a cotação do dólar.
    scanf("%f", &cotacao); // armazena na variável cotacao.
    printf("Informe Quantidade de dolar: "); // Solicita que o usuário insira a quantidade de dólares.
    scanf("%f", &us); // Lê a quantidade de dólares fornecida pelo usuário e armazena-a na variável us.

    printf("============== <>Money<> ==============\n"); // Mensagem para indicar a exibição do resultado.
    printf("Conversao em (R$): %f\n", us / cotacao); // Calcula e exibe o valor em reais.
    printf("============== <>Money<> ==============\n"); // Mensagem para indicar o fim do resultado.

    system("PAUSE"); // Pausa a execução do programa antes de terminar.
}

EX9
#include <stdio.h> // Inclui uma biblioteca.
#include <conio.h> // Inclui uma biblioteca.
#include <math.h> // Inclui uma biblioteca.
#include <iostream> // Inclui uma biblioteca.

main() // Função principal do programa.
{ 

float dep,us; // Declaração das variáveis.
float juros=0.7; // Declaração e inicialização da variável 'juros' com o valor 0.7.
printf("============== Juros from HELL ==============\n"); // Aparece a mensagem pra o usuário.
printf("Digite o valor depositado: "); // Solicita ao usuário que digite o valor do depósito.

scanf("%f",&dep); // Lê o valor digitado pelo usuário e o armazena na variável dep.

printf("============== <>Juros<> ==============\n"); //Mensagem visível ao usuário.
printf("Rendimento:%f\n",juros*dep); // Calcula o rendimento do valor do depósito e da taxa de juros.

printf("============== <>Juros<> ==============\n"); // Aparece a mensagem pra o usuário.
system("PAUSE > null"); // Pausa a execução do programa .
} 
____________________________________________________________________________
EX10
#include <stdio.h> // Inclui uma biblioteca.
#include <conio.h> // Inclui uma biblioteca.
#include <math.h> // Inclui uma biblioteca.
#include <iostream> // Inclui uma biblioteca.

main() // Função principal do programa.
{
    float compra; // Declara uma variável.
    printf("==============Mamao JHOW==============\n"); // Mensagem visível.
    printf("Digite valor da compra: "); // Solicita ao usuário que digite o valor da compra.
    scanf("%f", &compra); // armazena na variável compra.
    printf("============== <>Parcelamento<> ==============\n"); // Mensagem visível.
    printf("Em 5X: %f\n", compra / 5); // Calcula e exibe o valor de cada parcela para um parcelamento em 5 vezes.
    printf("============== <>Parcelamento<> ==============\n"); // Visivel ao usuário.

    system("PAUSE > null"); // Pausa a execução do programa antes de terminar.

¬¬____________________________________________________________________
EX11
#include <stdio.h> // Inclui uma biblioteca.
#include <conio.h> // Inclui uma biblioteca.
#include <math.h> // Inclui uma biblioteca.
#include <iostream> // Inclui uma biblioteca.

main() // função principal do programa.
{
    float custo, percent, venda; // Declara três variáveis.
    printf("==============Produtos Like a Boss==============\n"); // mensagem de título visível ao usuário.
    printf("Digite o custo do produto: "); // Solicita ao usuário que digite o custo do produto.
    scanf("%f", &custo); // armazena na variável custo.
    printf("Digite o percentual para venda: "); // Solicita ao usuário que digite o percentual para venda.
    scanf("%f", &percent); // armazena na variável percent.

    percent = ((percent / 100) * custo); // Calcula o valor percentual do custo.
    venda = percent + custo; // Calcula o valor de venda somando o custo com o valor percentual.
    printf("============== <>Acrescimo<> ==============\n"); // Mensagem visível ao usuário.
    printf("O valor de venda é: %f\n", venda); // Exibe o valor de venda calculado.
    printf("============== <>Acrescimo<> ==============\n"); // Mensagem visível ao usuário.

    system("PAUSE > null"); // Pausa a execução do programa.
}

EX12
#include <stdio.h> // Inclui uma biblioteca.
#include <conio.h> // Inclui uma biblioteca..
#include <math.h> // Inclui uma biblioteca.
#include <iostream> // Inclui uma biblioteca.

main() // Função principal do programa.
{
    float custof, custocon, percd, impostos; // Declara quatro variáveis.
    printf("==============CARRO NOVO==============\n"); // Mensagem visível ao usuário.
    printf("Digite Custo de Fabrica: "); // Solicita ao usuário que digite o custo de fábrica do carro.
    scanf("%f", &custof); // armazena na variável custof.

    impostos = (0.45 * (custof)); // Calcula o valor dos impostos.
    percd = ((custof) + (impostos)) * 0.28; // Calcula o valor do percentual de distribuidor.
    custocon = ((custof) + (impostos) + (percd)); // Calcula o custo para o consumidor.

    printf("Custo Consumidor:%1.2f", custocon); // Mostra o custo para o consumidor.
    system("Pause>null"); // Pausa a execução do programa antes de terminar.
}
EX13
#include <stdio.h> // Inclui uma biblioteca.
#include <conio.h> // Inclui uma biblioteca.
#include <math.h> // Inclui uma biblioteca.
#include <iostream> // Inclui uma biblioteca.

main() // Função principal do programa.
{
    int numero; // Declara uma variável inteira chamada numero.

    printf("==============Maior==============\n"); // Mensagem visível ao usuário.
    printf("Digite um numero: "); // Solicita ao usuário que digite um número.
    scanf("%d", &numero); // armazena na variável numero.

    if (numero > 10) // Verifica se o número digitado é maior que 10.
        printf("Numero Positivo"); // Se for maior que 10, imprime "Numero Positivo".
    else
        return 0; // encerra o programa com sucesso.

    system("Pause>null"); // Pausa a execução do programa antes de terminar.
}

EX14
#include <stdio.h> // Inclui uma biblioteca.
#include <conio.h> // Inclui uma biblioteca.
#include <math.h> // Inclui uma biblioteca.
#include <iostream> // Inclui uma biblioteca.

main() // Função principal do programa.
{
    int v1, v2; // Declara duas variáveis inteiras.

    
    printf("==============Dois Valores MAIOR==============\n"); // Mensagem visível ao usuário.
    printf("Digite Primeiro Valor: "); // Solicita ao usuário que digite o primeiro valor.
    scanf("%d", &v1); // armazena na variável v1.
    printf("Digite Segundo Valor: "); // Solicita ao usuário que digite o segundo valor.
    scanf("%d", &v2); // armazena na variável v2.

    { 
        if (v1 > v2) // Verifica se v1 é maior que v2.
            printf("Primeiro Valor e MAIOR\n"); // Se v1 for maior que v2, imprime "Primeiro Valor e MAIOR".
        else // Se não
            if (v2 > v1) // Verifica se v2 é maior que v1.
                printf("Segundo Valor e MAIOR\n"); // Se v2 for maior que v1, imprime "Segundo Valor e MAIOR".
            else // Se não
                printf("Valores IGUAIS\n"); //  "Valores IGUAIS".
        system("Pause>null"); // Pausa a execução do programa antes de terminar.
    } // Fim do bloco de código.
}

EX15
#include <stdio.h> // Inclui uma biblioteca.
#include <conio.h> // Inclui uma biblioteca.
#include <math.h> // Inclui uma biblioteca.
#include <iostream> // Inclui uma biblioteca.

main() // Função principal do programa.
{
    int v1; // Declara uma variável inteira.

    printf("==============Intervalos==============\n"); // Mensagem visível ao usuário.
    printf("Digite Um Valor: "); // Solicita ao usuário que digite um número.
    scanf("%d", &v1); // armazena na variável v1.

    {
        if (v1 >= 100 && v1 <= 200) // Verifica se o valor está entre 100 e 200.
            printf("Esta no Intervalo 100 a 200\n"); // Se sim, exibe que está no intervalo.
        else
            printf("Fora do Intervalo 100 a 200\n"); // Se não, exibe que está fora do intervalo.
        system("Pause>null"); // Pausa a execução do programa antes de terminar.
    }
}
EX17
#include <stdio.h> // Inclui uma biblioteca.
#include <conio.h> // Inclui uma biblioteca.
#include <math.h> // Inclui uma biblioteca.
#include <iostream> // Inclui uma biblioteca.

main() // Função principal do programa.
{
    int i, n1, intervalo; // Declara três variáveis inteiras.
    {
        for (i = 1; i <= 3; i++) // Inicia com i variando de 1 a 3.
        {
            printf("Digite um numero"); // Solicita ao usuário que digite um número.
            scanf("%d", &n1); // armazena na variável n1.
        }

        if (n1 >= 10 && n1 <= 150) // Verifica se o valor de n1 está entre 10 e 150.
        {
            intervalo = intervalo + 1; // soma +1.
        }
        
        printf("%d", intervalo); // exibe o valor de intervalo.
        
        system("PAUSE > null"); // Pausa a execução do programa antes de terminar.
    }

EX18
#include <stdio.h> // Inclui uma biblioteca.
#include <conio.h> // Inclui uma biblioteca.
#include <math.h> // Inclui uma biblioteca.
#include <iostream> // Inclui uma biblioteca.

main() // Função principal do programa.
{
    int idade, x; // Declara duas variáveis inteiras.
    char nome[30]; // 30 de armazenamento para nome.

    for (x = 1; x <= 3; x++) // Inicia um loop com x variando de 1 a 3.
    {
        printf("Informe Nome: "); // Solicita ao usuário que informe o nome.
        scanf("%s", nome); // armazena na variável nome.
        printf("Digite idade: "); // Solicita ao usuário que digite a idade.
        scanf("%d", &idade); // armazena na variável idade.

        if (idade >= 18) // Verifica se a idade é maior ou igual a 18.
        {
            
            printf("<><><><><><><><><><>STATS<><><><><><><><><><><>\n");
            printf("[%s] e maior de IDADE\n", nome);
            printf("<><><><><><><><><><>STATS<><><><><><><><><><><>\n");
\\ Se tiver 18 ou mais, imprime na tela.
        }
        else
        {
            // Se não imprime que é menor de idade.
            printf("<><><><><><><><><><>STATS<><><><><><><><><><><>\n");
            printf("[%s] e menor de IDADE\n", nome);
            printf("<><><><><><><><><><>STATS<><><><><><><><><><><>\n");
        }
    }
    system("PAUSE > null"); // Pausa a execução do programa antes de terminar.
}

EX23
#include <iostream> // Inclui uma biblioteca.
#include <conio.h> // Inclui uma biblioteca.
#include <stdio.h> // Inclui uma biblioteca.
#include <math.h> // Inclui uma biblioteca.
#include <stdlib.h> // Inclui uma biblioteca.

main() // Função principal do programa.
{
    int numero; // Declara uma variável inteira..
    printf("Informe um Numero: "); // Solicita ao usuário que informe um número.
    scanf("%d", &numero); // armazena na variável numero.

    if (numero == 40) // Verifica se o número digitado é igual a 40.
    {
        printf("Numero digitado 40"); // Se for igual a 40, mostra "Numero digitado 40".
    }
    if (numero > 80) // Verifica se o número digitado é maior que 80.
    {
        printf("Numero maior que 80"); // Se for maior que 80, mostra "Numero maior que 80".
    }
    else // Se não..........
    {
        if (numero < 25) // Verifica se o número digitado é menor que 25.
        {
            printf("Numero Menor que 25"); // Se for menor que 25,  mostra "Numero Menor que 25".
        }
    }

    system("PAUSE > null"); // Pausa a execução do programa antes de terminar.
}

EX25 
#include <iostream> // Inclui uma biblioteca.
#include <conio.h> // Inclui uma biblioteca.
#include <stdio.h> // Inclui uma biblioteca.
#include <math.h> // Inclui uma biblioteca.
#include <stdlib.h> // Inclui uma biblioteca.

main() // Função principal do programa.
{
    int n1, n2; // Declara duas variáveis inteiras .

    printf("Informe Primeiro numero: "); // Solicita ao usuário que informe o primeiro número.
    scanf("%d", &n1); // armazena na variável n1.
    printf("Informe Segundo Numero: "); // Solicita ao usuário que informe o segundo número.
    scanf("%d", &n2); // armazena na variável n2.

    if (n1 == n2) // Verifica se os números são iguais.
    {
        printf("===========[NUMEROS IGUAIS]===========\n"); // Se forem iguais, imprime "NUMEROS IGUAIS".
    }
    else // SE NÃÃAÃAÃAÃOO...
    {
        if (n1 != n2 && n1 > n2) // Verifica se os números são diferentes e se n1 é maior que n2.
        {
            printf("-----------[NUMEROS DIFERENTES]-----------\n"); // Se sim, imprime "NUMEROS DIFERENTES".
            printf("[MAIOR NUMERO:%d]", n1); //  informa que n1 é o maior número.
        }
        else // Se n1 não for maior que n2, então n2 é o maior.
        {
            printf("-----------[NUMEROS DIFERENTES]-----------\n"); // mostra "NUMEROS DIFERENTES".
            printf("[MAIOR NUMERO:%d]", n2); // E informa que n2 é o maior número.
        }
    }

    system("PAUSE > null"); // Pausa a execução do programa antes de terminar.
}

#include <stdio.h>
#include <iostream>
int main()

{
	int mat;/* declaração da variável inteira mat */
	char nome[25],classificacao; /* declaração das variáveis caractere "nome" e "classificação"*/
	float nota1, nota2, nota3;/*declaração das variáveis "nota1, nota2 e nota3"*/
	float p1, p2, p3; /* declaração das variáveis flutuantes "p1,p2 e p3" */
	float mp; /* decalaração da variável flutuante mp */
	p1=2; /* atribuição de valor*/
	p2=3; /* atribuição de valor*/
	p3=5; /* atribuição de valor*/
	printf("Informe o nome do Aluno: \n"); /* mostra em tela o texto e pula a linha*/
	scanf("%s",&nome); /* recebe a informação solicitada na linha anterior e armazena em nome*/
	printf("Informe o numero da matricula: \n"); /* mostra em tela o texto e pula a linha*/
	scanf("%d",&mat);/* recebe a informação solicitada na linha anterior e armazena em mat*/
	printf("Informe a nota do trabalho de laboratorio: \n"); /* mostra em tela o texto e pula a linha*/
	scanf("%f",&nota1);/* recebe a informação solicitada na linha anterior e armazena em nota1*/
	printf("Informe a nota da avaliacao semestral: \n"); /* mostra em tela o texto e pula a linha*/
	scanf("%f",&nota2);/* recebe a informação solicitada na linha anterior e armazena em nota2*/
	printf("Informe a nota do exame final: \n"); /* mostra em tela o texto e pula a linha*/
	scanf("%f",&nota3);/* recebe a informação solicitada na linha anterior e armazena em nota3*/
	mp=((nota1*p1)+(nota2*p2)+(nota3*p3))/(p1+p2+p3); /* realiza operações matemáticas com os dados armazenados nas variáveis*/
		if (mp>8) { /* inicio da estrutura de condições */
			classificacao='A';
		}else {
			if(mp>=7&&((mp<8))){
				classificacao='B';
			}else{
				if((mp>=6) && (mp<7)){
					classificacao='C';
				}else {
					if((mp>=5)&&(mp<6)){
						classificacao='D';
						}else{
							classificacao='R'; /* fim da estrutura de condições*/
						}					
					}
					
				}
			}
		
	printf("Aluno:%s\a\n",nome); /* exibe em tela o nome e gera um beep*/
	printf("Matricula: %d\n",mat); /* exibe em tela a matricula*/
	printf("Media:\%1.2f\n",mp); /* exibem em tela a media calculada*/
	printf("Classificacao: %c\n",classificacao); /* exibe em tela a classificação condicionada na estrutura 'if'*/
	system("Pause>NULL");
}
	_______________________________________________________________________

#include <stdio.h>   
#include <iostream> 

int main()
{
	float notalab, notasem, notafin; /* declaração das variaveis flutuantes nota */
	float peso1, peso2, peso3; /* declaração das variáveis flutuantes peso */
	float media; /* declaração da variavel flutuante media*/
	peso1=2; /*atribuição de valor à variável*/
	peso2=3; /*atribuição de valor à variável*/
	peso3=5; /*atribuição de valor à variável*/
	printf("Informe a nota do trabaho de laboratorio:\n"); /*exibe a mensagem em tela e solicita a entrada de dados*/
	scanf("%f",&notalab); /*recebe a entrada de dados*/
	printf("Informe a nota da avaliacao semestral:\n"); /*exibe a mensagem em tela e solicita a entrada de dados*/
	scanf("%f",&notasem);/*recebe a entrada de dados*/
	printf("Informe a nota do exame final:\n");/*exibe a mensagem em tela e solicita a entrada de dados*/
	scanf("%f",&notafin);/*recebe a entrada de dados*/
	media=((notalab*peso1)+(notasem*peso2)+(notafin*peso3))/(peso1+peso2+peso3);/* executa a operação matemática com os dados inseridos salvos na memória*/
	printf("A media ponderada e: %1.2f\n",media); /* exibe em tela o resultado da operação matematica*/
	system("Pause>NULL");
#include <stdio.h> // inclui biblioteca
#include <iostream> // inclui biblioteca
int main()
{
	float consumo; //declaração da variável flutuante 'consumo'
	int tipo; //declaração da variável inteira 'tipo'
	printf("Informe o consumo em kw/h\n"); //exibe em tela a mensagem e solicita dado
	scanf("%f",&consumo); //recebe e armazena na variável'consumo'
	printf("Informe o tipo de cliente\n"); //exibe em tela a mensagem
	printf("1-Residencia, 2-Comercio, 3-Industria\n"); //exibe em tela a mensagem e solicita dado
	scanf("%d",&tipo); // recebe e armazena dado na variável 'tipo'
   		switch(tipo){ //comando de seleção ou comando de condição
                case 1: // para escolha de 1
                printf("O valor da conta eh %1.2f\n",(consumo)*(0.6)); //exibe em tela a mensagem e calculo do valor da conta
                break;  // comando que salta  o código para o final do switch, se o case acima for atendido
                case 2: // para escolha de 2
                printf("O valor da conta eh %1.2f\n",(consumo)*(0.48));//exibe em tela a mensagem e calculo do valor da conta
                break;// comando que salta  o código para o final do switch, se o case acima for atendido  
                case 3:a// para escolha de 3
                printf("O valor da conta eh %1.2f\n",(consumo)*(1.29));//exibe em tela a mensagem e calculo do valor da conta
                break; // comando que salta  o código para o final do switch, se o case acima for atendido 
                default: // se nenhum caso acima for atendido, vai para a proxima linha
                printf("Tipo de cliente invalido\n"); // exibe em tela a mensagem se nenhum caso acima for atendido
                break; // comando que salta  o código para o final do switch             
   }
	system("Pause >NULL"); // pausa a execução do programa antes de fechar.
}
#include <stdio.h> // inclui biblioteca   
#include <iostream> // inclui biblioteca
int main()
{
int idade; // declara variável inteira 'idade'
printf("Informe a idade do nadador\n"); // exibe em tela a mensagem e pede entrada de dado
scanf("%d",&idade); // recebe e armazena na variável 'idade'
           if ((idade >=5) && (idade<=7)) { // condição se
                printf("Infantil A"); // se verdadeiro, apresenta em tela a mensagem
           }else{ //senão
                if ((idade>7) && (idade<=10)) { // condição se
                     printf("Infantil B"); // se verdadeiro, apresenta em tela a mensagem
                }else{ // senão
                     if ((idade>10) && (idade<=13)) { //condição
                          printf("Juvenil A"); //se verdadeiro, apresenta em tela a mensagem
                     }else{ // senão
                          if ((idade>13) && (idade <=17)) { // condição
                               printf("Juvenil B"); //se verdadeiro, apresenta em tela a mensagem
                          }else{ // senão
                               if ((idade>17) && (idade<=25)) { // condição
                                    printf("Senior");//se verdadeiro, apresenta em tela a mensagem
                               }else{//senão
                                    printf("Idade fora da faixa etaria"); // apresenta em tela a mensagem caso nenhuma condição acima tenha sido atendida
                               }
                          }
                     }
                }
           }
system("Pause >NULL"); //pausa o programa antes de fechar
}
#include <stdio.h> //adiciona biblioteca  
#include <iostream> // adiciona biblioteca
int main()
{
	float ha; // declaração da variável flutuante 'ha'
	int nivel; // decalração da variável inteira 'nivel'
	char nome[25]; //declaração da variavel caractere 'nome' com até 25 caracteres admitidos.
	printf("Informe o nome do professor\n"); //apresenta em tela a mensagem
	scanf("%s",&nome);// recebe o dado e armazena na variável 'nome'
	printf("informe o total de horas/aula\n"); //apresenta a mensagem em tela
	scanf("%f",&ha); // recebe o dado e armazena na variável 'ha'
	printf("Informe o nivel do professor\n");// apresenta a mensagem em tela
	scanf("%d",&nivel);// recebe dado e armazena na variável 'nivel'
	switch(nivel){  // comando de seleção 
   		printf("O salario de %s eh R$ %1.2f",nome,((ha)*12));//exibe em tela a mensagem e calculo do valor da hora aula dada
   		break;que salta  o código para o final do switch, se o case acima for atendido 
   		case 2:
   		printf("O salario de %s eh R$ %1.2f",nome,((ha)*17));//exibe em tela a mensagem e calculo do valor da hora aula dada
   		break;que salta  o código para o final do switch, se o case acima for atendido 
   		case 3:
   		printf("O salario de %s eh R$ %1.2f",nome,((ha)*25));//exibe em tela a mensagem e calculo do valor da hora aula dada
   		break;que salta  o código para o final do switch, se o case acima for atendido 
  		default: // se nenhum caso acima for atendido, vai para a proxima linha
   		printf("Nivel invalido"); // exibe em tela a mensagem para nenhum caso acima atendido.
   break; // vai para o fim da switch
}
system("Pause >NULL"); //pausa o programa antes de fechar
}
#include <stdio.h> // inclui biblioteca  
#include <iostream> // incui biblioteca

int main()
{
	int a,b,c; // declaração das variáveis inteiras 'a', 'b', 'c'
	printf("informe ovalor de a\n"); // exibe em tela a mensagem solcitando dado
	scanf("%d",&a); //recebe dado e armazena na variavel 'a'
	printf("Informe o valor de b\n");// exibe em tela a mensagem solcitando dado
	scanf("%d",&b);//recebe dado e armazena na variavel 'b'
	printf("Informe o valor de c\n");// exibe em tela a mensagem solcitando dado
	scanf("%d",&c);//recebe dado e armazena na variavel 'c'
       if (a<(b+c) && b<(c+a) && c<(b+a)){ //estrutura de condição SE, realiza calculo
          if (a==b && b==c){ //realiza calculo 
               printf("Os valores informados correspondem a um triangulo Equilatero e Isoscele");//exibe em tela o resultado do calculo
          }else{ //senão
               if (a!=b && b!=c && c!=a){ // realiza calculo para estrutura de condição
                    printf("Os valores informados correspondem a um triangulo Escaleno"); //exibe em tela o resultado do calculo
               }else{
                    printf("Os valores informados correspondem a um triangulo Isoscele");//exibe em tela o resultado do calculo
               }
          }      
       }else{
       printf("Os valores informados nao correspondem a um triangulo"); // caso nenunha das condições sejam atendidas exibe a mensagem na tela
       }
system("Pause >NULL"); // pausa o programa para encerrar
}
#include <stdio.h> //inclui biblioteca
#include <iostream> //inclui biblioteca
int main() 
{ 
	float a,b; //declara as variaveis float 'a' e 'b'
	char c; // declara as variaveis char 'c'
	printf("informe um valor para A\n"); // exibe a mensagem em tela solicitando entrada de dado
	scanf("%f",&a); //recebe e armazena dado na variavel 'a'
	printf("Informe um valor para B\n");  // exibe a mensagem em tela solicitando entrada de dado
	scanf("%f",&b); // recebe e armazena dado na variavel 'b'
	printf("Informe um operador para a operacao\n");  // exibe a mensagem em tela solicitando entrada de dado
	printf("Adicao: +\n"); // exibe em tela o operador matemático
	printf("Subtracao: -\n"); // exibe em tela o operador matemático
	printf("Divisao: /\n"); // exibe em tela o operador matemático
	printf("Multiplicacao: *\n"); // exibe em tela o operador matemático
	scanf("%s",&c); //recebe operador matematico e armazena na variável 'c'
	switch(c){ //comando de seleção ou comando de condição
		case '/': // para o caso de /
		if (b!=0) { //verifica se 'b' não é zero
			printf("o resultado da divisao eh %1.2f\n",(a/b)); // exibe em tela a mensagem e o resultado do calculo
}		else{ 
			printf("Operacao nao realizada: Divisao por zero\n"); // exibe em tela a mensagem caso a operação seja divisão por 0
} 
		case '*': 
			printf("o resultado da multiplicacao eh %1.2f\n",(a*b)); // exibe em tela a mensagem e o resultado do calculo
		break; //salta para o final da switch se o case for atendido
		case '-': 
			printf("o resultado da subtracao eh %1.2f\n",(a-b)); // exibe em tela a mensagem e o resultado do calculo
		break; //salta para o final da switch se o case for atendido
		case '+': 
			printf("o resultado da adicao eh %1.2f\n",(a+b)); // exibe em tela a mensagem e o resultado do calculo
		break; //salta para o final da switch se o case for atendido
		default: 
		printf("Operador invalido\n"); //exibe em tela mensagem se caracter inserido não for um operador matemático válido
	break; //salta para o final da switch se o case for atendido
system("Pause >NULL"); //pausa o programa antes de fechar
}
#include <stdio.h> // adiciona biblioteca
#include <iostream> // adiciona biblioteca

int main() 
{ 
	int idade; //declaraçã da variavel inteira 'idade' 
	char nome[35]; // declaração da variavel char nome com até 35 caracteres
	char sexo; // declaração da variavel 'sexo'
	float sf,sl; // declaração da variável float 'sf' e 's1'
	printf("Informe o nome do funcionario:\n"); // mostra mensagem em tela e solicita dado
	scanf("%s",&nome); // recebe dado e armazena na variavel 'nome'
	printf("Informe o salario fixo em R$:\n"); // mostra mensagem em tela e solicita dado
	scanf("%f",&sf); // recebe dado e armazena na variavel 'sf'
	printf("Informe a idade: \n"); // mostra mensagem em tela e solicita dado
	scanf("%d",&idade); // recebe dado e armazena na variavel 'idade'
	sexo='I'; // atribui à variavel 'sexo' o valor I
		do { 
		printf("Informe o sexo: F ou M \n");// mostra mensagem em tela e solicita dado 
		scanf("%s",&sexo); // recebe dado e armazena na variavel'sexo'
		} 
		while ((sexo!='M') && (sexo!='F')); // loop para que se digite M ou F
		switch(sexo){ //condição de seleção
			case 'F': // caso de escolha F
			if (idade >=30){ //se idade for maior ou igual 30
			sl=sf+200; //calcula sl=sf+200
			}else{ // senão
			sl=sf+80; //calcula sl=sf+80
			} 
			break; // atendida algum case acima, salta para o final do switch
			case 'M': //para no caso de escolha M
				if (idade >=30){ // se a idade for maior ou igual 30 anos
				sl=sf+100; // calcula sl=sf+100
			}else{ //senão
				sl=sf+50; //calcula sl=sf+50
			} 
			break; //salta para o final do switch
		}  
	printf("O salario liquido de %s e R$ %1.2f",nome,sl); // exibe em tela a mensagem, o nome e o resultado do calculo
system("Pause >NULL"); // pausa o programa antes de fechar
}

#include <stdio.h> // inclui biblioteca
#include <iostream> // incui biblioteca
int main() 
{ 
	int mes; // declaração da variavel inteira 'mes'
	printf("Entre com o numero do mes:\n"); //exibe mensagem em tela e solicita dado
	scanf("%d",&mes); // recebe dado e armazena na variavel'mes'
	switch(mes){ 
		case 1: 
		printf("Janeiro\n"); // exibe em tela o mês relativo a 1
		break; // salta para o final do switch, sendo atendido o case acima
		case 2: 
		printf("Fevereiro\n"); // exibe em tela o mês relativo a 2
		break;// salta para o final do switch, sendo atendido o case acima
		case 3: 
		printf("Marco\n"); // exibe em tela o mês relativo a 3
		break;// salta para o final do switch, sendo atendido o case acima 
		case 4: 
		printf("Abril\n"); // exibe em tela o mês relativo a 4
		break; // salta para o final do switch, sendo atendido o case acima
		case 5: 
		printf("Maio\n"); // exibe em tela o mês relativo a 5
		break;// salta para o final do switch, sendo atendido o case acima 
		case 6: 
		printf("Junho\n"); // exibe em tela o mês relativo a 6
		break; // salta para o final do switch, sendo atendido o case acima
		case 7: 
		printf("Julho\n"); // exibe em tela o mês relativo a 7
		break; // salta para o final do switch, sendo atendido o case acima
		case 8: 
		printf("Agosto\n"); // exibe em tela o mês relativo a 8
		break; // salta para o final do switch, sendo atendido o case acima
		case 9: 
		printf("Setembro\n"); // exibe em tela o mês relativo a 9
		break; // salta para o final do switch, sendo atendido o case acima
		case 10: 
		printf("Outubro\n"); // exibe em tela o mês relativo a 10
		break;// salta para o final do switch, sendo atendido o case acima
		case 11: 
		printf("Novembro\n"); // exibe em tela o mês relativo a 11
		break; // salta para o final do switch, sendo atendido o case acima
		case 12: 
		printf("dezembro\n"); // exibe em tela o mês relativo a 12
		break; // salta para o final do switch, sendo atendido o case acima
		default: 
		printf("Mes invalido\n"); // exibe em tela mensagem de erro caso diferente em numero de 1 a 12
		break; // salta para o final do switch, sendo atendido o case acima
	} 
system("Pause >NULL"); // pausa o sistema antes de fechar

#include <stdio.h> 
#include <iostream> 
int main() 
{ 
float vf,des,vv,td,tp; // declaração das variaveis flutuantes
//vf = Valor, final des=desconto, vv=valor veiculo, td=total desconto, tp=total pago
char combustivel; //declaração da variavel char
td=0; //atribui à variavel 'td valor 0
tp=0; // atribui à variavel 'tp' valor 0
printf("informe o valor do veiculo: \n"); // exibe em tela
scanf("%f",&vv); //recebe valor e armazena na variavel vv
while (vv > 0){ //estrutura enquanto
combustivel='N'; //atribui N a combustivel (constante octal)
	{ 
	printf("Informe o tipo de combustivel\n\n");// exibem em tela a mensagem e solicita dado 
	printf("A - Alcool\n"); // exibe em tela a mensagem
	printf("G - Gasolina\n"); // exibe em tela a mensagem
	printf("D - Diesel\n"); // exibe em tela a mensagem
	scanf("%s",&combustivel); //recebe o dado e armazena na variavel combustivel
	} 
	while ((combustivel !='A') && (combustivel !='G') && (combustivel !='D')); //estrutura enquanto
	switch(combustivel) // estrutura de escolha
	{ 
	case 'A': 
	des=(0.25)*vv; // se o dado for A executa o calculo
	break; // salta para o fim do switch
	case 'G': 
	des=(0.21)*vv; // se o dado for B executa o calculo
	break; // salta para o fim do switch
	case 'D': 
	des=(0.14)*vv; //se o dado for D executa o calculo
	break;// salta para o fim do switch 
	} 
		vf=vv-des; // calcula vf
		td=td+des; // calcula td
		tp=tp+vf; //calcula tp
		printf("o valor do Veiculo com desconto de R$ %1.2f e de R$ %1.2f\n",des,vf); //exibe em tela a mensagem e resultado dos calculos de des e vf
		printf("informe o valor do veículo. (Valor 0 encerra o programa)\n"); // exibe msg em tela solicitando novo valor de Veículo
		scanf("%f",&vv); // recebe e armazena dado
		} 
		printf("Valor total de descontos: R$ %1.2f\n", td); // exibe em tela valor total de descontos
		printf("Valor total pago pelos clientes: R$ %1.2f\n", tp); // exibe em tela valor total pago 
		system("Pause >NULL"); //pausa e fecha
}

#include <iostream>
#include <conio.h>
#include <stdio.h>
#include <math.h>
#include <stdlib.h>

main()
     {
         int numero;
         {
            //seção de comandos
            printf("Informe um Numero: ");
            scanf("%d",&numero);
                 if(numero>=1 && numero<=5)
                   {
                     printf("====== [NUMERO NO INTERVALO 1-5] ======\n \n");
                   }
                   else
                   {
                    printf("()()()()()[NUMERO INVALIDO]()()()()()\n \n");  
                   }
                   switch (numero){
                   	case 1:
                   		printf("um\n");
                   		break;
                   	case 2:
					   printf("dois\n");
					   break;
					case 3:
                   		printf("tres\n");
                   		break;
                   	case 4:
					   printf("quatro");
					   break;  
					 defalt:
					 	printf("cinco\n");
					 	break;
					
				   }
          }
          system("PAUSE > null");
     }                 

#include <iostream>//iclui biblioteca
#include <conio.h>// inclui biblioteca
#include <stdio.h>// inclui biblioteca
#include <math.h>// inclui biblioteca
#include <stdlib.h>// inclui biblioteca

main()
     {
         int n1,n2; // declaração de variaveis inteiras 'n1' 'n2' 'n3'
         
         printf("Informe Primeiro numero: "); // exibe na tela mensagem e solicita dado
         scanf("%d",&n1);//recebe dado e armazena na variavel n1
         printf("Informe Segundo Numero: ");//exibe na tela mensagem e solicita dado
         scanf("%d",&n2); // recebe dado e armazena na variavel n2
              if(n1==n2) // condição se n1 é igual n2
              {
                 printf("===========[NUMEROS IGUAIS]===========\n"); //exibe mensagem na tela
                } 
                else //senão
                {
                  if(n1!=n2 && n1>n2)// condição se n1 não é igual n2 e n1 menor que n2
                    {
                     printf("-----------[NUMEROS DIFERENTES]-----------\n"); //exibe mensagem na tela
                     printf("[MAIOR NUMERO:%d]",n1);// exibe mensagem na tela e apresenta valor de n1
                    }       
                    else//senão
                    {
                    printf("-----------[NUMEROS DIFERENTES]-----------\n"); // apresenta mensagem na tela
                     printf("[MAIOR NUMERO:%d]",n2); // apresenta mensagem na tela e valor de n2 
                     }
               }  
               system("PAUSE > null"); //pausa antes de encerrar programa
       }             

#include <iostream>// inclui biblioteca
#include <conio.h>// inclui biblioteca
#include <stdio.h> // inclui biblioteca
#include <math.h>// inclui biblioteca
#include <stdlib.h>// inclui biblioteca

main()
     {
         int numero;//declaração de variavel
         
            printf("Informe um Numero: ");// exibe mensagem na tela e solicita dado
            scanf("%d",&numero);// recebe dado armazena na variavel numero
               if(numero==40)// condição Se variavel numero for igual a 40
                 {
                   printf("Numero digitado 40");// exibe na tela mensagem
                 }            
                   if(numero>80)//se numero for menor que 80
                     {
                       printf("Numero maior que 80");// exibe mensagem na tela
                     }
                    else//senão
                     {
                       if(numero<25)// condição se variavel numero for menor que 25
                          { 
                            printf("Numero Menor que 25"); // exibe na tela mensagem
                          }     
                     }
        system("PAUSE > null"); // pausa para encerrar.
# Descrevendo-c-digos-c-
