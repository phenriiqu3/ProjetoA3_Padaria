// # ProjetoA3_Padaria 
// Projeto tela de Padaria com cadastro, estoque, cadastro de produtos e funcionários e banco de dados.
// Nome dos integrantes - Paulo Henrique Oliveira dos Santos
import java.util.ArrayList;

public class Produto {
    private int id;
    private String nome;
    private double preco;
    // Outros atributos relevantes
    
}

public class Funcionario {
    private int id;
    private String nome;
    private String cargo;
    
}

public class Estoque {
    private ArrayList<Produto> produtos;    
}

public class Padaria {
    private ArrayList<Produto> produtos;
    private ArrayList<Funcionario> funcionarios;
    private Estoque estoque;    
    
    // Método principal para interagir com o usuário
    public void iniciar() {
    }
}

public class Main {
    public static void main(String[] args) {
        Padaria padaria = new Padaria();
        padaria.iniciar();
    }
}

