# Desafio4

# Questao4
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
 * 

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
