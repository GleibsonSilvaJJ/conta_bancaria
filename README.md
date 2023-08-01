# Aplicação de Gerenciamento de Conta Bancária
Esta documentação explica o funcionamento da aplicação de gerenciamento de conta bancária desenvolvida em Python. Essa aplicação permite realizar operações básicas como depósito, saque, verificação do extrato e encerramento do programa.


### Certifique-se de ter o Python instalado em seu sistema.
Copie o código fornecido da aplicação e cole em um arquivo Python com a extensão .py.
Abra um terminal ou prompt de comando e navegue até o diretório onde o arquivo Python está localizado.
Execute o seguinte comando para rodar a aplicação:
Copy code
python nomedoarquivo.py
Substitua "nomedoarquivo.py" pelo nome do arquivo Python que contém o código da aplicação.

### Funcionamento da Aplicação
Ao executar a aplicação, você será apresentado a um menu de opções com as seguintes escolhas:

* [d] Depositar
* [s] Sacar
* [e] Extrato
* [q] Sair
Você pode selecionar a opção desejada digitando a letra correspondente à opção no teclado e pressionando Enter.

### Opção [d] Depositar
Ao escolher esta opção, você será solicitado a informar o valor que deseja depositar na conta. Se o valor for maior que zero, o saldo da conta será atualizado e o histórico de transações será registrado. Caso contrário, uma mensagem de falha será exibida informando que o valor informado é inválido.

### Opção [s] Sacar
Nessa opção, você deve informar o valor que deseja sacar da conta. Antes de realizar o saque, a aplicação verifica se há saldo suficiente, se o valor do saque excede o limite permitido e se o número de saques já atingiu o limite máximo permitido. Se todas as verificações forem bem-sucedidas, o valor será subtraído do saldo, o histórico de transações será registrado e o contador de saques será incrementado. Caso contrário, uma mensagem de falha será exibida.

### Opção [e] Extrato
Ao escolher esta opção, você pode visualizar o extrato da conta bancária. O extrato mostrará todas as transações (depósitos e saques) realizadas até o momento, bem como o saldo atual da conta.

### Opção [q] Sair
Ao selecionar esta opção, o programa será encerrado, e a execução da aplicação será finalizada.



