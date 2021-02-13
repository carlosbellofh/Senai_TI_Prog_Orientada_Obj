# Senai_TI_Prog_Obj
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
	
	Carro c2 = new Carro();
	c2.fabricante = "Chevrolet";
	c2.modelo = "Camaro";
	c2.cor = "Amarelo";
	c2.ano = 2021;
	
	System.out.println();
	System.out.println("Carro 2:");
	System.out.println("Fabricante: "+c2.fabricante);
	System.out.println("Modelo : "+c2.modelo);
	System.out.println("Cor : "+c2.cor);
	System.out.println("Ano : "+c2.ano);
	
	Carro c3 = new Carro();
	c3.fabricante = "VW";
	c3.modelo = "Fox";
	c3.cor = "Vermelho";
	c3.ano = 2016;
	
	System.out.println();
	System.out.println("Carro 3:");
	System.out.println("Fabricante: "+c3.fabricante);
	System.out.println("Modelo : "+c3.modelo);
	System.out.println("Cor : "+c3.cor);
	System.out.println("Ano : "+c3.ano);
	

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
