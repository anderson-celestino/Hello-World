# Hello-World

Essa atividade é referente ao primeiro exercício realizado utilizando o RabbitMQ. Nele, o produtor envia uma mensagem para o RabbitMQ, que se encarrega de colocá-la em uma fila e depois utilizada pelo consumidor.

## Ferramentas utilizadas

RabbitMQ, Pycharm, Erlang

## Processo de execução

Depois de fazer a instalação das ferramentas necessárias, foram criados dois arquivos em python para fazer a comunicação através do RabbitMQ. Um dos arquivos seria responsável por ser o produtor e o outro consumidor. Assim, é possível encaminhar uma mensagem e recebê-la posteriormente.

## Resultado esperado

É esperado que a mensagem fique na lista de espera no RabbitMQ, esperando para ser pega pelo consumidor. Nesse exemplo, o produtor é o arquivo "send.py" e o consumidor é o "receive.py", que são executados através do terminal integrado no Pycharm.
