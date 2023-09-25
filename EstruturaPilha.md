public class InverterTexto {
    public static void main(String[] args) {
        String texto = "Olá, este é um exemplo de uso de fila e pilha em Java!";
        
        // Quebrando o texto em palavras
        String[] palavras = texto.split(" ");
        
        // Revertendo a ordem das palavras
        String textoRevertido = "";
        for (int i = palavras.length - 1; i >= 0; i--) {
            textoRevertido += palavras[i];
            if (i > 0) {
                textoRevertido += " ";
            }
        }
        
        // Imprimindo o texto revertido
        System.out.println("Texto revertido:");
        System.out.println(textoRevertido);
    }
}


 Obtive esse codigo ao pedir para a I.A um codigo com a mesma funçaõ ao que possuia a estrutura de dados, mas utilizar da mesma.
 em uma conversa de questionamento com a I.A, me foi fornecido por ela as informações de que o código que utiliza da estrutura de dados pilha é mais viavel pois se trata de uma estrutura mais simples e com mais clareza, alem do seu desempenho voltado para eficiencia do codigo. Enquanto a estrutura que utiliza array é mais complexa, portanto você consegue o controle totoal sobre ela e tem um desempenho personalizado, mas para isso você precisa ter um conhecimento afundo da estrutura. Por possuir essa funcionalidade a estrutura com array é mais recomendada para situaçoes muito especificas.
 Por esse trabalho se referir a um sistema de "ctrl+z" não é recomendado que se utilize da estrutura com array, já que para isso precisaria gerenciar manualmente o tamanho do array, realocar memória se ele ficar cheio e controlar o índice das ações. Isso pode ser mais complexo e sujeito a erros do que usar uma estrutura de dados dinâmica. E como um sistema de "ctrl+z" você teria que liudar com um monte de variaveis, um sistema como o de pilha seria o mais recomendavél por ele já se ajustar adequadamente e automaticamente ao tamanho do histórico.
