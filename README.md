# Senai_TI_Prog_Obj
Java Programacao Orientada a Objeto
package controller;

import model.Carro;

public class Cadastro {

	public static void main(String[] args) {
		// syso + Ctrl+espaço
		//System.out.println();
	Carro c1 = new Carro();
	c1.fabricante = "Honda";
	c1.modelo = "Fit";
	c1.cor = "Prata";
	c1.ano = 2020;
	
	System.out.println("Carro 1:");
	System.out.println("Fabricante: "+c1.fabricante);
	System.out.println("Modelo : "+c1.modelo);
	System.out.println("Cor : "+c1.cor);
	System.out.println("Ano : "+c1.ano);

	}

}
//
package model;

public class Carro {

	public String fabricante;
	public String modelo;
	public String cor;
	public int ano;
}
