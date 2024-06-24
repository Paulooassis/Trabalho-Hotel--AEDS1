# Trabalho-Hotel--AEDS1

## Projeto
O Hotel Descanso Garantido é um hotel localizado no centro de Itacaré – BA, com um forte compromisso em proporcionar um excelente atendimento e fidelizar seus clientes. O hotel conta com uma equipe composta por recepcionistas, auxiliares de limpeza, garçons e um gerente. Até o momento, o hotel realizava o controle de estadias, clientes e funcionários através de planilhas do Excel e registros em cadernos, o que frequentemente resultava em problemas organizacionais, incluindo conflitos de reserva, onde um mesmo quarto era reservado para mais de um cliente. Por isso, foi desenvolvido um sistema em linguagem C para resolver esses problemas e melhorar a eficiência operacional.

## Bibliotecas Usadas
* **stdbool.h**: Utilizada para utilizar valores booleanos (true e false), essenciais para verificação de datas e loops.
* **stdio.h**: Biblioteca essencial que fornece funções como printf e scanf, fundamentais para interação com o usuário e entrada/saída de dados.
* **stdlib.h**: Oferece funções para manipulação de memória, conversão de tipos, geração de números aleatórios e controle do ambiente de execução.
* **string.h**: Provê funções para manipulação de strings, como cópia, concatenação, comparação e busca de caracteres.

## Funções Utilizadas

* **imprimirclientetxt(hotel *h)**: Imprime os dados dos clientes em um arquivo de texto, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item, sendo printado no txt a primeira linha o total de cliente e nas demais, cada linha representa um cliente e suas informações são separadas por um ";".

* **scanearclientetxt(hotel *h)**: Lê dados de clientes de um arquivo de texto para a memória,  tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item, sendo scaneado no txt a primeira linha o total de cliente e nas demais, cada linha representa um cliente e suas informações são separadas por um ";", que são lidas ao inicializar a main, sendo possível utilizar as informações já armazenadas no txt.

* **imprimirfuncionariotxt(hotel *h)**: Imprime os dados dos funcionários em um arquivo de texto, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item, sendo printado no txt a primeira linha o total de funcionario e nas demais, cada linha representa um funcionario e suas informações são separadas por um ";".

* **scanearfuncionariotxt(hotel *h)**: Lê dados de funcionários de um arquivo de texto para a memória, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item, sendo scaneado no txt a primeira linha o total de funcionarios e nas demais, cada linha representa um funcionario e suas informações são separadas por um ";", que são lidas ao inicializar a main, sendo possível utilizar as informações já armazenadas no txt.

* **imprimirestadiatxt(hotel *h)**: Imprime os dados das estadias em um arquivo de texto, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item, sendo printado no txt a primeira linha o total de estadias e nas demais, cada linha representa uma estadia e suas informações são separadas por um ";".

* **scanearestadiatxt(hotel *h)**: Lê dados das estadias de um arquivo de texto para a memória, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item, sendo scaneado no txt a primeira linha o total de estadias e nas demais, cada linha representa uma estadia e suas informações são separadas por um ";", que são lidas ao inicializar a main, sendo possível utilizar as informações já armazenadas no txt.

* **imprimirquartotxt(hotel *h)**: Imprime os dados dos quartos em um arquivo de texto, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item, sendo printado no txt a primeira linha o total de quartos e nas demais, cada linha representa um quarto e suas informações são separadas por um ";".

* **scanearquartos(hotel *h)**: Lê dados dos quartos de um arquivo de texto para a memória, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item, sendo scaneado no txt a primeira linha o total de quartos e nas demais, cada linha representa um quarto e suas informações são separadas por um ";", que são lidas ao inicializar a main, sendo possível utilizar as informações já armazenadas no txt.

* **menu(int *opcao)**: Exibe um menu de opções para o usuário e lê a escolha dele.

* **cadastrarcliente(hotel *h)**: Permite cadastrar um novo cliente no sistema, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item e lê as informações que deseja ser cadastrada para o cliente.

* **cadastrarfuncionario(hotel *h)**: Permite cadastrar um novo funcionário no sistema, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item e lê as informações que deseja ser cadastrada para o funcionario.

* **validar_data(data d)**: Verifica se uma data é válida, sendo usada na função cadastrar estadias.

* **data_maior(data d1, data d2)**: Compara duas datas para determinar qual é maior, sendo usada na função de cadastrar estadias.

* **cadastrarestadia(hotel *h)**: Permite cadastrar uma nova estadia no hotel, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item, além disso possui restrições que verifica se possui quartos livres, se possui quartos para a quantodade de hospedes digitadas, verifica se a data de registro é compatível com o calendário, além de verificar se a data de saida é maior do que a data de entrada.

* **cadastrarquarto(hotel *h)**: Permite cadastrar um novo quarto no hotel, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item e lê as informações que deseja ser cadastrada para o cliente.

* **exibeestadia(hotel *h)**: Exibe as informações de uma estadia específica, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item, e é solicitado o codigo do cliente que deseja verificar as suas estadias.

* **darbaixaestadia(hotel *h)**: Realiza o encerramento de uma estadia e calcula os valores devidos, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item.

* **exibequartolivre(hotel *h)**: Exibe os quartos disponíveis para reserva, tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item.

* **pesquisar(hotel *h)**: Permite pesquisar clientes, funcionários, estadias ou quartos no sistema., tem como paramêtro um ponteiro para um struct que contém todas as structs do hotel e o total de cada item

## MENU

            MENU DE OPCOES !!
    1. Cadastrar um cliente
    2. Cadastrar um funcionario
    3. Cadastrar uma estadia
    4. Cadastrar um quarto
    5. Ver estadias do cliente
    6. Dar baixa na estadia
    7. Ver quartos livres
    8. Pesquisar informacoes
    9. Sair do programa
    Digite a opcao desejada: 

* Sendo possivel escolher cada uma das seguintes opções que redirecionará para a tela da opção desejada.

## ARQUIVOS TXT

* Todos os arquivos do txt possui a seguinte lógica, a primeira linha contém o total de itens cadastrados naquele arquivo, por exemplo, clientes, aparece um 2 no topo do arquivo, que significa que possuem 2 clientes separados, e cada linha representa um desses itens, sendo separados por um ";" cada informação, deixando o código bem compreensível e legível.
