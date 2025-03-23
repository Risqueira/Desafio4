# Desafio4

# Questao1
```java
package nadadores;

import java.util.Scanner;

/**
 *Categoria por Idade: Dado a idade de um nadador, classifique-o em
uma das seguintes categorias:
Infantil A: 5-7 anos
Infantil B: 8-10 anos
Juvenil A: 11-13 anos
Juvenil B: 14-17 anos
Adulto: maiores de 18 anos
 * @author Henrique
 /*

public class Nadadores {

    public static void main(String[] args) {
        
        int idade;
        Scanner ler = new Scanner(System.in);
        
        System.out.println("Qual sua idade?");
        idade = ler.nextInt();
        
        if(idade>=5 && idade<=7){
            System.out.println("Infantil A");
        }else if(idade>=8 && idade<=10){
            System.out.println("Infantil B");
        }else if(idade>=11 && idade<=13){
            System.out.println("Juvenil A");
        }else if(idade>=14 && idade<=17){
            System.out.println("Juvenil B");
        }else if(idade>=18){
            System.out.println("Adulto");
        }else{
            System.out.println("idade invalida");
        }
    }
    
}
```
# Questao 2
```java
package descontoproduto;

import java.text.DecimalFormat;
import java.util.Scanner;

/**
 * Desconto em Produto: Se um produto custa mais de 100 reais, dê um desconto de
 * 15%. Se custar menos, dê um desconto de 5%. Informe o valor final do produto.
 *
 * @author Henrique
 */
public class DescontoProduto {

    public static void main(String[] args) {

        double valorProd, custoTotal;
        Scanner ler = new Scanner(System.in);
        DecimalFormat decimal = new DecimalFormat("0.00");

        System.out.println("Informe o preço do produto:");
        valorProd = ler.nextDouble();

        if (valorProd >0 && valorProd<=100) {
            custoTotal = valorProd-(valorProd * 0.05);
            System.out.println("valor do produto com desconto de 5%:" +"R$"+ decimal.format(custoTotal));
        }else if(valorProd>100){
            custoTotal = valorProd*0.85;
            System.out.println("Valor do produto com desconto de 15%:"+"R$"+decimal.format(custoTotal));
        }else{
            System.out.println("Valor Invalido");
        }

    }
}
```
# Questao 3
```java
package saudacaohorario;

import java.util.Scanner;

/**
 * Saudação conforme o horário: Dado a hora do dia (um número de 0 a 23),
 * cumprimente o usuário com "Bom dia!", "Boa tarde!" ou "Boa noite!"; conforme
 * o horário.
 *
 * @author Henrique
 */
public class SaudacaoHorario {

    public static void main(String[] args) {

        int numero;
        Scanner ler = new Scanner(System.in);

        System.out.println("Digite um numero de 0 a 23");
        numero = ler.nextInt();

        if (numero == 0) {
            System.out.println("Bom dia!");
        } else if (numero == 1) {
            System.out.println("Bom dia!");
        } else if (numero == 2) {
            System.out.println("Bom dia!");
        } else if (numero == 3) {
            System.out.println("Bom dia!");
        } else if (numero == 4) {
            System.out.println("Bom dia!");
        } else if (numero == 5) {
            System.out.println("Bom dia!");
        } else if (numero == 6) {
            System.out.println("Bom dia!");
        } else if (numero == 7) {
            System.out.println("Bom dia!");
        } else if (numero == 8) {
            System.out.println("Bom dia!");
        } else if (numero == 9) {
            System.out.println("Bom dia!");
        } else if (numero == 10) {
            System.out.println("Bom dia!");
        } else if (numero == 11) {
            System.out.println("Bom dia!");
        } else if (numero == 12) {
            System.out.println("Boa dia!");
        } else if (numero == 13) {
            System.out.println("Boa tarde!");
        } else if (numero == 14) {
            System.out.println("Boa tarde!");
        } else if (numero == 15) {
            System.out.println("Boa tarde!");
        } else if (numero == 16) {
            System.out.println("Boa tarde!");
        } else if (numero == 17) {
            System.out.println("Boa tarde!");
        } else if (numero == 18) {
            System.out.println("Boa tarde!");
        } else if (numero == 19) {
            System.out.println("Boa noite!");
        } else if (numero == 20) {
            System.out.println("Boa noite!");
        } else if (numero == 21) {
            System.out.println("Boa noite!");
        } else if (numero == 22) {
            System.out.println("Boa noite!");
        } else if (numero == 23) {
            System.out.println("Boa noite!");
        } else {
            System.out.println("Numero Invalido");
        }
    }
}
```
# Questao 4
```java
package faixadenota;

import java.util.Scanner;

/**
 * 4. Faixa de Nota: Dado uma nota de 0 a 100, classifique-a da seguinte
forma:
 0-49: Insuficiente
 50-69: Regular
 70-89: Bom
 90-100: Excelente
 * @author Henrique
 */
public class FaixaDeNota {

    public static void main(String[] args) {
        
        int nota;
        Scanner ler = new Scanner(System.in);
        
        System.out.println("Digite uma nota de 0 a 100:");
        nota = ler.nextInt();
        
        if(nota>=0 && nota<=49){
            System.out.println("Insuficiente");
        }else if(nota>=50 && nota<=69){
            System.out.println("Regular");
        }else if(nota>=70 && nota<=89){
            System.out.println("Bom");
        }else if(nota>=90 && nota<=100){
            System.out.println("Excelente");
        }else{
            System.out.println("Numero invalido");
        }
    }
}
```
# Questao 5 
```java
package verificandotriang;

import java.text.DecimalFormat;
import java.util.Scanner;

/**
 * Verificando um Triangulo: Dados três valores, A, B, C, verificar se eles
 * podem ser valores dos lados de um triângulo e, se forem, se é um triângulo
 * escaleno, equilátero ou isóscele, considerando os seguintes conceitos: O
 * comprimento de cada lado de um triângulo é menor do que a soma dos outros
 * dois lados.  Chama-se equilátero o triângulo que tem três lados iguais.
 * Denominam-se isósceles o triângulo que tem o comprimento de dois lados
 * iguais.  Recebe o nome de escaleno o triângulo que tem os três lados
 * diferentes
 *
 * @author Henrique
 */
public class VerificandoTriang {

    public static void main(String[] args) {

        double a, b, c;
        Scanner ler = new Scanner(System.in);
        DecimalFormat decimal = new DecimalFormat("0.00");

        System.out.println("Digite o valor de A:");
        a = ler.nextDouble();
        System.out.println("Digite o valor de B:");
        b = ler.nextDouble();
        System.out.println("Digite o valor de C:");
        c = ler.nextDouble();

        if (a == b && a == c) {
            System.out.println("O Triângulo é Equiláero");
        } else if (a == b || a == c || b == c) {
            System.out.println("O Triângulo é Isóceles");
        } else if (a != b && a != c) {
            System.out.println("O Triângulo é Escaleno");
        }

    }
}
```
# Questao 6
```java
package verificandotrapezio;

import java.text.DecimalFormat;
import java.util.Scanner;

/**
 * Verificando um trapézio: Faça um programa que calcule e mostre a área de um
 * trapézio. Sabe-se que:  A = ((basemaior + basemenor) * altura) / 2 Lembre-se
 * a base maior e a base menor devem ser números maiores que zero.
 *
 * @author aluno.saolucas
 */
public class VerificandoTrapezio {

    public static void main(String[] args) {

        double baseMaior, baseMenor, altura, area;
        Scanner ler = new Scanner(System.in);
        DecimalFormat decimal = new DecimalFormat("0.00");

        System.out.println("Digite o valor da base maior:");
        baseMaior = ler.nextDouble();
        System.out.println("Digite o valor da base menor:");
        baseMenor = ler.nextDouble();
        System.out.println("Digite o valor da altura:");
        altura = ler.nextDouble();

        if (baseMaior == 0 && baseMenor == 0) {
            System.out.println("Valores das bases invalidos");
        } else {
            area = ((baseMaior + baseMenor) * altura) / 2;
            System.out.println("A area do trapézio é de:" + decimal.format(area));
        }
    }

}
```
Questao 7
```java
package bhaskara;

import java.text.DecimalFormat;
import java.util.Scanner;

/**
 * Resolvendo a Fórmula de Bhaskara: Faça um programa que calcule as raízes da
 * equação quadrática ax2+bx+c=0ax^2 + bx + c = 0ax2+bx+c=0. Sabe-se que:
 *
 * Lembre-se de que o valor de A deve ser diferente de zero e verifique o valor
 * de Delta Δ é maior que zero, para determinar se a equação tem duas raízes
 * reais, uma raiz real ou nenhuma raiz real.
 *
 * @author Henrique
 */
public class Bhaskara {

    public static void main(String[] args) {

        Double a2, b, c, delta, x1, x2, x;
        Scanner ler = new Scanner(System.in);
        DecimalFormat decimal = new DecimalFormat("0.00");

        System.out.println("Digite o valor de A:");
        a2 = ler.nextDouble();
        System.out.println("Digite o valor de B:");
        b = ler.nextDouble();
        System.out.println("Digite o valor de C:");
        c = ler.nextDouble();

        delta = Math.pow(b, 2) - 4 * a2 * c;

        if (a2 != 0 && delta > 0) {

            x1 = (-b + Math.sqrt(delta)) / (2 * a2);
            x2 = (-b - Math.sqrt(delta)) / (2 * a2);
            System.out.println("Duas raizes real x1:" + decimal.format(x1) + " " + "x2:" + decimal.format(x2));
        } else if (delta == 0) {
            x = -b / (2 * a2);
            System.out.println("Uma raiz real:" + decimal.format(x));
        } else {
            System.out.println("Valor invalido");
        }

    }

}
```
# Questao 8
```java
package diasdasemana;

import java.util.Scanner;

/**
 * Dia da Semana: Dado um número de 1 a 7, imprima o dia da semana
 * correspondente, sendo 1 para segunda-feira e 7 para domingo.
 *
 * @author henrique
 */
public class DiasDaSemana {

    public static void main(String[] args) {

        int numero;
        Scanner ler = new Scanner(System.in);

        System.out.println("Digite um numero de 1 a 7:");
        numero = ler.nextInt();

        switch (numero) {
            case 1:
                System.out.println("Segunda-feira");
                break;
            case 2:
                System.out.println("Terça-feira");
                break;
            case 3:
                System.out.println("Quarta-feira");
                break;
            case 4:
                System.out.println("Quinta-feira");
                break;
            case 5:
                System.out.println("Sexta-feira");
                break;
            case 6:
                System.out.println("Sabado");
                break;
            case 7:
                System.out.println("Domingo");
                break;    
        }
    }

}
```
# Questao 9
```java
package mesesdoano;

import java.util.Scanner;

/**
 * Meses do Ano: Escreva um programa que leia um inteiro entre 1 e 12 e imprima
 * o mês correspondente a este numero. Isto é, janeiro se 1, fevereiro se 2, e
 * assim por diante.
 *
 * @author henrique
 */
public class MesesDoAno {

    public static void main(String[] args) {

        int num;
        Scanner ler = new Scanner(System.in);

        System.out.println("Digite um numero de 1 a 12:");
        num = ler.nextInt();

        switch (num) {
            case 1:
                System.out.println("Janeiro");
                break;
            case 2:
                System.out.println("Feveiro");
                break;
            case 3:
                System.out.println("Março");
                break;
            case 4:
                System.out.println("Abril");
                break;
            case 5:
                System.out.println("Maio");
                break;
            case 6:
                System.out.println("Junho");
                break;
            case 7:
                System.out.println("Julho");
                break;
            case 8:
                System.out.println("Agosto");
                break;
            case 9:
                System.out.println("Setembro");
                break;
            case 10:
                System.out.println("Outubro");
                break;
            case 11:
                System.out.println("Novembro");
                break;
            case 12:
                System.out.println("Dezembro");
                break;
            default:
                System.out.println("INVALIDO");
                break;
        }
    }

}
```
# Questao 10
```java
package estacoesanohs;

import java.util.Scanner;

/**
 * Estação do Ano: Dado um mês representado por um número (1 para
Janeiro, 12 para Dezembro), informe a estação do ano correspondente
no hemisfério sul.
 * @author henrique
 */
public class EstacoesAnoHS {

    public static void main(String[] args) {
        int num;
        Scanner ler = new Scanner(System.in);

        System.out.println("Digite um numero de 1 a 12:");
        num = ler.nextInt();

        switch (num) {
            case 1:
                System.out.println("Verão");
                break;
            case 2:
                System.out.println("Verão");
                break;
            case 3:
                System.out.println("Outono");
                break;
            case 4:
                System.out.println("Outono");
                break;
            case 5:
                System.out.println("Outono");
                break;
            case 6:
                System.out.println("Inverno");
                break;
            case 7:
                System.out.println("Inverno");
                break;
            case 8:
                System.out.println("Inverno");
                break;
            case 9:
                System.out.println("Primavera");
                break;
            case 10:
                System.out.println("Primavera");
                break;
            case 11:
                System.out.println("Primavera");
                break;
            case 12:
                System.out.println("Verão");
                break;
            default:
                System.out.println("INVALIDO");
                break;
        }
    }
    
}
```
