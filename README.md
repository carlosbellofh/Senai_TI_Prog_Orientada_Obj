# Senai-TI: Programação orientada a objetos
## Cursos: Introdução a Java & Programação Orientada a Objetos

## Introdução

Esse repositório foi criado com o objetivo de armazenar os exercícios do Curso Senai-RJ - Programação Orientada a Objetos - que eu estou estudando - e programando - no momento.
Espero que esse repositório seja útil, de alguma forma, para o aprendizado dos seus estudos e por favor façam comentários para melhoria das soluções dos exercícios apresentados.
**Bons Estudos!**

## Como executar os códigos Java (no Windows):

- Baixe o aplicativo Eclipse IDE for Enterprise Java Developers através deste link [[Download Aqui]](https://www.eclipse.org/downloads/packages/release/2020-12/r/eclipse-ide-enterprise-java-developers) e instale-o normalmente no seu computador.

***
### Exemplo01 (HelloWorld)
  - O Exemplo01 mostra na tela a mensagem __Hello Word__
  - Abrir o aplicativo Eclipse IDE, dentro de FILE, Criar NEW > Java Project.
  - Escrever Project name: __01_HelloWorld__ e depois clicar em __Finish__
  - Criar o __packet controller__ abaixo de __src__
  - Criar a __classe HelloWorld__ abaixo do __packet controller__, ativar o método __Main__ e clicar em __Finish__
  - Escrever o código para exibir na tela a mensagem __Hello Word__: System.out.println("Hello World")
  - Para executar é só clicar em Run HelloWord
 ### Codigo do Exemplo01 (HelloWord.java)
 
 ```
 package controller;

public class HelloWorld {

	public static void main(String[] args) {
		
System.out.println("Hello World");
	}

}
```
***
### Exemplo02 (ExemploGUI)
  - O Exemplo02 mostra a interface gráfica do usuário com uma pergunta na tela.
  - Abrir o aplicativo Eclipse IDE, dentro de FILE, Criar NEW > Java Project.
  - Escrever Project name: __02_ExemploGUI__ e depois clicar em __Finish__
  - Criar o __packet controller__ abaixo de __src__
  - Criar a __classe Exemplo__ abaixo do __packet controller__, ativar o método __Main__ e clicar em __Finish__
  - Escrever o código para exibir na tela as mensagens _SENAI - Exemplo GUI_ e _Quer aumento de salário_
  - Para executar é só clicar em Run Exemplo
 ### Codigo do Exemplo02 (Exemplo.java)
 
```
package controller;

public class Exemplo {

	public static void main(String[] args) {
	
		javax.swing.JOptionPane.showMessageDialog(null, "SENAI", "Exemplo GUI", 1);
		javax.swing.JOptionPane.showConfirmDialog(null, "Quer aumento de salário?", "Salário",
				javax.swing.JOptionPane.YES_NO_OPTION);
	}

}

```
