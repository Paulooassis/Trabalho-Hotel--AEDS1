# Trabalho-Hotel--AEDS1

## Projeto
O Hotel Descanso Garantido é um hotel localizado no centro de Itacaré – BA, com um forte compromisso em proporcionar um excelente atendimento e fidelizar seus clientes. O hotel conta com uma equipe composta por recepcionistas, auxiliares de limpeza, garçons e um gerente. Até o momento, o hotel realizava o controle de estadias, clientes e funcionários através de planilhas do Excel e registros em cadernos, o que frequentemente resultava em problemas organizacionais, incluindo conflitos de reserva, onde um mesmo quarto era reservado para mais de um cliente. Por isso, foi desenvolvido um sistema em linguagem C para resolver esses problemas e melhorar a eficiência operacional.

## Bibliotecas Usadas
* **stdbool.h**: Utilizada para utilizar valores booleanos (true e false), essenciais para verificação de datas e loops.
* **stdio.h**: Biblioteca essencial que fornece funções como printf e scanf, fundamentais para interação com o usuário e entrada/saída de dados.
* **stdlib.h**: Oferece funções para manipulação de memória, conversão de tipos, geração de números aleatórios e controle do ambiente de execução.
* **string.h**: Provê funções para manipulação de strings, como cópia, concatenação, comparação e busca de caracteres.

## Funções Utilizadas

* **imprimirclientetxt(hotel *h)**: Imprime os dados dos clientes em um arquivo de texto.

* **scanearclientetxt(hotel *h)**: Lê dados de clientes de um arquivo de texto para a memória.

* **imprimirfuncionariotxt(hotel *h)**: Imprime os dados dos funcionários em um arquivo de texto.

* **scanearfuncionariotxt(hotel *h)**: Lê dados de funcionários de um arquivo de texto para a memória.

* **imprimirestadiatxt(hotel *h)**: Imprime os dados das estadias em um arquivo de texto.

* **scanearestadiatxt(hotel *h)**: Lê dados das estadias de um arquivo de texto para a memória.

* **imprimirquartotxt(hotel *h)**: Imprime os dados dos quartos em um arquivo de texto.

* **scanearquartos(hotel *h)**: Lê dados dos quartos de um arquivo de texto para a memória.

* **menu(int *opcao)**: Exibe um menu de opções para o usuário e lê a escolha dele.

* **cadastrarcliente(hotel *h)**: Permite cadastrar um novo cliente no sistema.

* **cadastrarfuncionario(hotel *h)**: Permite cadastrar um novo funcionário no sistema.

* **validar_data(data d)**: Verifica se uma data é válida.

* **data_maior(data d1, data d2)**: Compara duas datas para determinar qual é maior.

* **cadastrarestadia(hotel *h)**: Permite cadastrar uma nova estadia no hotel, no qual verifica se possui quartos livres, se possui quartos para a quantodade de hospedes digitadas, verifica se a data de registro é compatível com o calendário, além de verificar se a data de saida é maior do que a data de entrada.

* **cadastrarquarto(hotel *h)**: Permite cadastrar um novo quarto no hotel, .

* **exibeestadia(hotel *h)**: Exibe as informações de uma estadia específica.

* **darbaixaestadia(hotel *h)**: Realiza o encerramento de uma estadia e calcula os valores devidos.

* **exibequartolivre(hotel *h)**: Exibe os quartos disponíveis para reserva.

* **pesquisar(hotel *h)**: Permite pesquisar clientes, funcionários, estadias ou quartos no sistema.

## MENU





