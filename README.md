package exercicio;

public class pedidoVendas {

	public static void main(String[] args) { 
		Pedido pedido = new Pedido();
		
		pedido.codigo = 15;
		pedido.setDesconto(10.0);
		pedido.setSubtotal(1000.0);
		//pedido.setTotal(150.0);
		
		
	System.out.println(pedido.obterDadosDoPedido());
		
}
}
