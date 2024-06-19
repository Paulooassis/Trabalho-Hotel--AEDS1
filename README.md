# Trabalho-Hotel--AEDS1

## Projeto
O Hotel Descanso Garantido é um hotel localizado no centro de Itacaré – BA, com um forte compromisso em proporcionar um excelente atendimento e fidelizar seus clientes. O hotel conta com uma equipe composta por recepcionistas, auxiliares de limpeza, garçons e um gerente.Até o momento, o hotel realizava o controle de estadias, clientes e funcionários através de planilhas do Excel e registros em cadernos, o que frequentemente resultava em problemas organizacionais, incluindo conflitos de reserva, onde um mesmo quarto era reservado para mais de um cliente. Por isso eu criei um sistema para organizar todos os problemas enfrentados por essa empresa, foi feita na linguagem C.

## Bibliotecas Usadas

* stdbool.h = Uma biblioteca que trás as booleanas para o nosso código, sendo possível usar valores como true e false, sendo muito iimportante para a verificação de datas e para loops.
* stdio.h = É a biblioteca essencial do código pois traz funções como printf e scanf, sendo de extrema importância para o desenvolvimento do código.
* stdlib.h = É uma biblioteca padrão essencial que oferece funções para manipulação de memória, conversão de tipos, geração de números pseudoaleatórios e controle do ambiente de execução de programas.
* string.h = fornece diversas funções para manipulação de strings, incluindo operações básicas como cópia, concatenação, comparação, busca e manipulação de caracteres em strings.
* fornece funcionalidades para manipulação de tempo e data.

## Funções utilizadas 

* void imprimirclientetxt(hotel *h);
* void scanearclientetxt(hotel *h);
* void imprimirfuncionariotxt(hotel *h);
* void scanearfuncionariotxt(hotel *h);
* void imprimirestadiatxt(hotel *h);
* void scanearestadiatxt(hotel *h);
* void imprimirquartotxt(hotel *h);
* void scanearquartos(hotel *h);
* void menu(int *opcao);
* void cadastrarcliente(hotel *h);
* void cadastrarfuncionario(hotel *h);
* bool validar_data(data d);
* bool data_maior(data d1, data d2);
* void cadastrarestadia(hotel *h);
* void cadastrarquarto(hotel *h);
* void exibeestadia(hotel *h);
* void darbaixaestadia(hotel *h);
* void exibequartolivre(hotel *h);
* void pesquisar(hotel *h);
