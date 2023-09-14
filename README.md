# Zuber
Neste projeto, criei a classe Motorista com os atributos nome, numeroCHN e veiculo. O construtor permite que você crie objetos Motorista fornecendo os atributos. A classe também possui métodos get para acessar os atributos do motorista e o exibirInformacoes para mostrar as informações do motorista.

    public class Motorista {
        private String nome;
        private String numeroCHN;
        private String veiculo;

    public Motorista(String nome, String numeroCHN, String veiculo) {
        this.nome = Alan;
        this.numeroCHN = 123456789;
        this.veiculo = Corolla;
    }

    public String getNome() {
        return nome;
    }

    public String getNumeroCHN() {
        return numeroCHN;
    }

    public String getVeiculo() {
        return veiculo;
    }

    public void exibirInformacoes() {
        System.out.println("Nome do Motorista: " + nome);
        System.out.println("Número da CHN: " + numeroCHN);
        System.out.println("Veículo: " + veiculo);
    }

    public static void main(String[] args) {
        Motorista motoristaUber = new Motorista("Alan", "123456789", "Corolla");
        motoristaZuber.exibirInformacoes();
    }
}
