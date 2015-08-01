import static org.junit.Assert.*;

import org.junit.Test;

public class SaqueDinheiroTest {
	//Quantidade máxima de notas são 5 de cada uma; por exemplo, se for sacar R$700
	//vai sair 5 notas de R$100 e 4 notas de R$50
	
	//Sacando_100_Reais_Retorna_1
	//Sacando_200_Reais_Retorna_2
	//Sacando_50_Reais_Retorna_1
	//Sacando_150_Reais_Retorna_1_de_100_e_1_de_50
	//Sacando_250_Reais_Retorna_2_de_100_e_1_de_50
	//Sacando_20_Reais_Retorna_1_de_20
	//Sacando_70_Reais_Retorna_1_de_50_e_1_de_20
	//Sacando_10_Reais_Retorna_1_de_10
	//Sacando_30_Reais_Retorna_1_de_20_e_1_de_10
	//Sacando_80_Reais_Retorna_1_de_50_e_1_de_20_e_1_de_10
	//Sacando_180_Reais_Retorna_1_de_100_e_1_de_50_e_1_de_20_e_1_de_10
	//Sacando_390_Reais_Retorna_3_de_100_e_1_de_50_e_1_de_20
	//Sacando_790_Reais_Retorna_5_de_100_e_5_de_50_e_2_de_20
	//Sacando_850_Reais_Retorna_5_de_100_e_5_de_50_e_5_de_20
	//Sacando_900_Reais_Retorna_5_de_100_e_5_de_50_e_5_de_20_e_5_de_10
	
	//Esses testes em diante, você pode colocar a quantidade de notas, lembrando q fiz com
	//uma quantidade padrão pra todas, se dizer que uma tem 10 notas, as outras também vão ter
	
	//Sacando_1000_Reais_Para_Quantidade_de_notas_Ate_7_Retorna_7_de_100_e_6_de_50
	//Sacando_1020_Reais_Para_Quantidade_de_notas_Ate_6_Retorna_6_de_100_e_6_de_50_6_de_20
	
	@Test
	public void Sacando_100_Reais_Retorna_1() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		
		saque = conta.saque(100);
		
		assertEquals("Valor do Saque:R$100 - 1 nota: 100$", saque);
	}
	
	@Test
	public void Sacando_200_Reais_Retorna_2(){
		String saque;
		ContaBancaria conta = new ContaBancaria();
		
		saque = conta.saque(200);
		
		assertEquals("Valor do Saque:R$200 - 2 nota: 100$", saque);
	}
	
	@Test
	public void Sacando_50_Reais_Retorna_1() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(50);
		assertEquals("Valor do Saque:R$50 - 1 nota: 50$", saque);
	}
	
	@Test
	public void Sacando_150_Reais_Retorna_1_de_100_e_1_de_50() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(150);
		assertEquals("Valor do Saque:R$150 - 1 nota: 100$ 1 nota: 50$", saque);
	}
	
	@Test
	public void Sacando_250_Reais_Retorna_2_de_100_e_1_de_50() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(250);
		assertEquals("Valor do Saque:R$250 - 2 nota: 100$ 1 nota: 50$", saque);
	}
	
	@Test
	public void Sacando_20_Reais_Retorna_1_de_20() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(20);
		assertEquals("Valor do Saque:R$20 - 1 nota: 20$", saque);
	}
	
	@Test
	public void Sacando_70_Reais_Retorna_1_de_50_e_1_de_20() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(70);
		assertEquals("Valor do Saque:R$70 - 1 nota: 50$ 1 nota: 20$", saque);
	}
	
	@Test
	public void Sacando_10_Reais_Retorna_1_de_10() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(10);
		assertEquals("Valor do Saque:R$10 - 1 nota: 10$", saque);
	}
	
	@Test
	public void Sacando_30_Reais_Retorna_1_de_20_e_1_de_10() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(30);
		assertEquals("Valor do Saque:R$30 - 1 nota: 20$ 1 nota: 10$", saque);
	}
	
	@Test
	public void Sacando_80_Reais_Retorna_1_de_50_e_1_de_20_e_1_de_10() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(80);
		assertEquals("Valor do Saque:R$80 - 1 nota: 50$ 1 nota: 20$ 1 nota: 10$", saque);
	}
	
	@Test
	public void Sacando_180_Reais_Retorna_1_de_100_e_1_de_50_e_1_de_20_e_1_de_10() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(180);
		assertEquals("Valor do Saque:R$180 - 1 nota: 100$ 1 nota: 50$ 1 nota: 20$ 1 nota: 10$", saque);
	}
	
	@Test
	public void Sacando_390_Reais_Retorna_3_de_100_e_1_de_50_e_2_de_20(){
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(390);
		assertEquals("Valor do Saque:R$390 - 3 nota: 100$ 1 nota: 50$ 2 nota: 20$", saque);
	}
	
	@Test
	public void Sacando_790_Reais_Retorna_5_de_100_e_5_de_50_e_2_de_20() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(790);
		assertEquals("Valor do Saque:R$790 - 5 nota: 100$ 5 nota: 50$ 2 nota: 20$", saque);
	}
	
	@Test
	public void Sacando_850_Reais_Retorna_5_de_100_e_5_de_50_e_5_de_20() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(850);
		assertEquals("Valor do Saque:R$850 - 5 nota: 100$ 5 nota: 50$ 5 nota: 20$", saque);
	}
	
	@Test
	public void Sacando_900_Reais_Retorna_5_de_100_e_5_de_50_e_5_de_20_e_5_de_10() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(900);
		assertEquals("Valor do Saque:R$900 - 5 nota: 100$ 5 nota: 50$ 5 nota: 20$ 5 nota: 10$", saque);
	}
	
	@Test
	public void Sacando_1000_Reais_Para_Quantidade_de_notas_Ate_5_Retorna_Exception() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saque(1000);
		assertEquals("Quantidade de notas insuficiente para esse valor!", saque);
	}
	
	@Test
	public void Sacando_1000_Reais_Para_Quantidade_de_notas_Ate_7_Retorna_7_de_100_e_6_de_50() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saqueComQuantidadeDeNotas(1000,7);
		assertEquals("Valor do Saque:R$1000 - 7 nota: 100$ 6 nota: 50$", saque);
	}
	
	@Test
	public void Sacando_1020_Reais_Para_Quantidade_de_notas_Ate_6_Retorna_6_de_100_e_6_de_50_6_de_20() {
		String saque;
		ContaBancaria conta = new ContaBancaria();
		saque = conta.saqueComQuantidadeDeNotas(1020,6);
		assertEquals("Valor do Saque:R$1020 - 6 nota: 100$ 6 nota: 50$ 6 nota: 20$", saque);
	}
}
