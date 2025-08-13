Código:
<img width="973" height="647" alt="image" src="https://github.com/user-attachments/assets/cd925216-2963-49c5-851a-7393e2571dac" />
<img width="940" height="642" alt="image" src="https://github.com/user-attachments/assets/bbd08d2d-2690-48b8-b629-0e0f70c7163a" />

Funcionando:
<img width="946" height="647" alt="image" src="https://github.com/user-attachments/assets/6b32e1e5-3b6e-42dd-bf16-463e567ad490" />
<img width="943" height="651" alt="image" src="https://github.com/user-attachments/assets/8f2ad0a9-ab7b-4a84-a629-6df1a1d890c1" />
<img width="903" height="449" alt="image" src="https://github.com/user-attachments/assets/022aa5b1-d35d-4b4f-8691-0feb5393a582" />
<img width="948" height="650" alt="image" src="https://github.com/user-attachments/assets/74290224-84a7-4135-a111-ebdf3469dce7" />


Para o código foi utilizado java swing para a criação das janelas de entrada e saída dos dados.

int numeroMagico = 10.
 utilizei para definir minha variavel fixa que será o número mágico.

String entrada = JOptionPane.showInputDialog.
  Para criar a janela de entrada onde coloca seu número.

int numero = Integer.parseInt(entrada).
  mantem o número inteiro salvo para as outras funções.

String mensagem = "".
 usado para o local onde aparecera as informações 

if e else para as informações, if para se realmente for aquilo e else junto ao if caso não seja, para mostrar exemplo " não é o número mágico".

if (numero == numeroMagico)
 Para o número que for igual ao que foi programado como fixo.

 if (numero > numeroMagico) {
  mensagem += "Seu número é maior que o Número Mágico.\n";
  } else {
   mensagem += "Seu numero é igual o Número mágico ./n";
  } 
    Caso seja maior if irá informar e else caso não seja irá informar.

  if (numero < numeroMagico)
    Para o número menor que o fixo.

  if (numero != numeroMagico
    Caso seja diferente.

 if (numero >= 15) {
 mensagem += "Está muito acima do Número Mágico!\n";   
   Esse código indica se é exato ou maior que o número usado como base para chegar ao fixo.

  if (numero <= 5) {
  mensagem += "Está muito abaixo do Número Mágico!\n";  
    Indica se é exato ou menor que o número usado como base para chegar ao fixo.

 Por fim:   JOptionPane.showMessageDialog(null, mensagem).
   Mostra a janela com as informações finais acumuladas, mostrando se a pessoa chegou próxima ao número mágico ou não e fechando o código.
  
 
