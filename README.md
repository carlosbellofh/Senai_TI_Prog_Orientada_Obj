# Senai-TI: Programação orientada a objetos
## Cursos: Introdução a Java & Programação Orientada a Objetos

## Introdução

Esse repositório foi criado com o objetivo de armazenar os exercícios do Curso Senai-RJ - Programação Orientada a Objetos - que eu estou estudando - e programando - no momento.
Espero que esse repositório seja útil, de alguma forma, para o aprendizado dos seus estudos e por favor façam comentários para melhoria das soluções dos exercícios apresentados.
**Bons Estudos!**

## Como executar os códigos Java (no Windows):

- Baixe o aplicativo _Eclipse IDE for Enterprise Java Developers_ através deste link [[Download Aqui]](https://www.eclipse.org/downloads/packages/release/2020-12/r/eclipse-ide-enterprise-java-developers) e instale-o normalmente no seu computador.

***
### Exemplo01 (HelloWorld)
  - O Exemplo01 mostra na tela a mensagem __Hello Word__
  - Abrir o aplicativo Eclipse IDE, dentro de FILE, Criar NEW > Java Project.
  - Escrever Project name: __01_HelloWorld__ e depois clicar em __Finish__
  - Criar o __packet controller__ abaixo de __src__
  - Criar a __classe HelloWorld__ abaixo do __packet controller__, ativar o método __Main__ e clicar em __Finish__
  - Escrever o código para exibir na tela a mensagem __Hello Word__: System.out.println("Hello World")
  - Para executar é só clicar em Run HelloWord
 ### Codigo do Exemplo01 (HelloWord)
 
 _Codigo HelloWord.Java_:
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
 ### Codigo do Exemplo02 (ExemploGUI)
 
 _Codigo Exemplo.java_: 
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
### Exemplo03 (ExemploNEW)
  - O Exemplo03 mostra o uso do padrão MVC com a utilização dos pacotes model(classe Usuario) e controller (classe Cadastro) e o operador NEW.
  - Abrir o aplicativo Eclipse IDE, dentro de FILE, Criar NEW > Java Project.
  - Escrever Project name: __03_ExemploNEW__ e depois clicar em __Finish__
  - Criar o __packet model__ abaixo de __src__
    - Criar a __classe__ `Usuario` abaixo do __packet model__, __Não é necessario ativar o método Main__
    - Criar os atributos da classe `Usuario`: `nome`_ e `endereco`
  - Criar o __packet controller__ abaixo de __src__
    - Importar a classe `Usuario`do pacote _model_
    - Criar a __classe__ `Cadastro` abaixo do __packet controller__, __ativar__ o método __Main__ e clicar em __Finish__
    - Criar um novo objeto `user` `new`
    - Definir os valores dos atributos `nome`_ e `endereco`
  - Exibir na tela os valores dos atributos `nome`_ e `endereco` do objeto `user`
  - Para executar é só clicar em Run Cadastro
 ### Codigo do Exemplo03 (ExemploNew)
 
_Codigo User.java_:
 ```
 package model;
/*
 * Este é o terceiro programa Exemplo
 */

public class Usuario {

	public String nome;
	public String endereco;
	
}

 ```
 _Codigo Cadasto.java_:
 
 ```
 package controller;
import model.Usuario;
public class Cadastro {

	public static void main(String[] args) {
		
		Usuario user = new Usuario();
		user.nome="João da Silva Sauro";
		user.endereco="Rua Sem Fim, 72";
		System.out.println(user.nome);
		System.out.println(user.endereco);
		
	}

}
```
 
