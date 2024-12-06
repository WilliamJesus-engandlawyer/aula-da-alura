class Exemplo {
    public static void main(String[] args) {
        System.out.println("série"); // Uso correto
        System.out.println("Arcane");
        
        int ano = 2022;  // Alterei para um ano maior que 2024
        System.out.println("ano de lançamento: " + ano);

        boolean incluidoNoPlano = true;
        double notaDaSerie = 9.9;

        // comparação com a variável ano
        if (ano > 2024) {
            System.out.println("lançamentos recentes");
        } else {
            System.out.println("clássicos da casa");
        }

        // Cálculo da média
        double media = (9.9 + 9.8 + 6.6) / 3;
        System.out.println(media);
    }
}
