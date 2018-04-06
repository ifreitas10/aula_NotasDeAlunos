public class aulaAtividades{
    public static void main(String[] args){
        int indice = 0;
        String[] nomes = new String[5];
        int[] notasFinais = new int[5];
        int maiorNota = 0;
        String alunoMaiorNota = "";
        String alunoRecebido = "";
        //Leia uma tabela de 5 nomes de alunos e 5 notas finais;
        for (indice = 0; indice <=1; indice++) {
            nomes[indice] = JOptionPane.showInputDialog("Digite o nome do aluno");
            notasFinais[indice] = Integer.parseInt(JOptionPane.showInputDialog("Digite a nota final do aluno"));
        }
                //Imprima a tabela na tela;
        for (indice = 0; indice <=1; indice++) {
            JOptionPane.showMessageDialog(null, "TODOS ALUNOS:\nNome do aluno: " + nomes[indice] + " || Nota final do aluno: " + notasFinais[indice]);
        }
                //Imprima o nome de todos alunos que obtiveram nota final acima da média;
        for (indice = 0; indice <=1; indice++){
                if(notasFinais[indice] >= 7){
                    JOptionPane.showMessageDialog(null,"Alunos com a nota acima ou igual a média:\nNome: "+nomes[indice]+" || Nota final: "+notasFinais[indice]);
                }
        }
                //Determine e imprima o nome do aluno que obteve a maior nota;
        for (indice = 0; indice <=1; indice++) {
            if (notasFinais[indice] > maiorNota){
                maiorNota = notasFinais[indice];
                alunoMaiorNota = nomes[indice];
            } else {
              }
        }
        
        JOptionPane.showMessageDialog(null, "Aluno com maior nota: " + alunoMaiorNota + " Nota: " + maiorNota);
        //Dado um nome de aluno, imprima sua nota (o aluno pode não estar na tabela)
        alunoRecebido = JOptionPane.showInputDialog("Nome do aluno que deseja ser pesquisado: ");
        for (indice = 0; indice <=1; indice++){
            if (alunoRecebido == nomes[indice]){
                JOptionPane.showMessageDialog(null, alunoRecebido + " Nota: " + notasFinais[indice]);
            } else {
                JOptionPane.showMessageDialog(null, "Aluno não encontrado");
            }
        }
    }
    
    aaaaaaaaaaaaaa
    JOptionPane.showMessageDialog(null, "Aluno com maior nota: " + alunoMaiorNota + " Nota: " + maiorNota);
        //Dado um nome de aluno, imprima sua nota (o aluno pode não estar na tabela)
        alunoRecebido = JOptionPane.showInputDialog("Nome do aluno que deseja ser pesquisado: ");
        for (indice = 0; indice <=1; indice++){
            if (alunoRecebido == nomes[indice]){
                notaRecebida = notasFinais[indice]
            }
            else {
                alunoRecebido = "não encontrado";
            }
        }
        JOptionPane.showMessageDialog(null, alunoRecebido + " Nota: " + notasFinais[indice]);
    }
}
