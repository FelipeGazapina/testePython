Estou lhe enviando o teste técnico conforme conversamos, peço que confirme o recebimento do mesmo.

O desafio constitui arquitetar e desenvolver um sistema cliente/servidor, seguindo as seguintes diretivas:

- Servidor deve implementar dois serviços: Um que retorne números pares, e outro números ímpares;
- Cada cliente ao se conectar ao servidor deve iniciar um processo que incrementa o valor recebido do servidor em 1 a cada 500ms, enviando o novo valor ao servidor;
- Cada cliente deve, em um intervalo aleatório entre 3 e 5 segundos, requisitar ao servidor um número par ou ímpar, escolhido de forma aleatória, que será utilizado como novo valor de incremento, ao invés de 1;
- Os números devem estar sempre no range 0-99;
- Servidor deve enviar um valor ao aceitar conexão do cliente;
- Servidor deve manter o último valor enviado para cada cliente. Caso um mesmo cliente se conecte, enviar esse valor para o mesmo. Caso não haja valor registrado, enviar 0;
- Servidor deve manter um log de todas as mensagens trocadas;
