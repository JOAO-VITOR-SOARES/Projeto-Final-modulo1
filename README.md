Projeto Final - Módulo 1 – Pado Labs

Como projeto final, cada grupo devera desenvolver um programa em
linguagem C que seja capaz de resolver um sistema de equações relativo a um
circuito elétrico resistivo ou encontrar o valor de saída expressão booleana. Os
detalhes de como o programa deve funcionar estão descritos a seguir.
A tela inicial do programa (menu principal) deve ser uma tela de seleção,
onde o usuário deve escolher se deseja resolver o sistema de equações de um
circuito elétrico ou obter o valor de saída da expressão booleana. Assim, fica
claro que o programa deve ter duas partes.
Dentro da resolução dos sistemas de equações de um circuito elétrico, o
usuário deve inicialmente selecionar se ele deseja resolver um sistema de 2 ou
3 equações. Feita a seleção, o usuário deve inserir as 2 ou 3 equações e é
importante que o programa indique o formato que as equações devem ser
inseridas. Vale ressaltar que cada equação deve ser inserida de uma vez, não
sendo permitida a leitura termo a termo. A seguir estão apresentados exemplos
do formato que as equações devem ser inseridas. Contudo, o programa deve ser
capaz de resolver qualquer sistema de equações, não somente os apresentados
no exemplo.

- Exemplo de sistema com 3 equações:
2.i1 + 3.i2 + 1.i3 = 0
i1 + 2.i2 + 6.i3 = 6
5.i1 + 4.i2 + 2.i3 = 3

- Exemplo de sistema com 2 equações:
4.i1 + 3.i2 = 0
6.i1 + 1.i2 = 0

Feita a leitura dos sistemas de equações, elas devem ser resolvidas e o
valor das correntes deve ser retornado na tela. Com os resultados exibidos, o
programa deve perguntar se o usuário deseja resolver uma nova equação ou
retornar ao menu principal.

Quando o usuário fizer a seleção da opção de obtenção do valor de saída
de uma expressão booleana, deve ser solicitado que ele entre com a expressão
booleana a ser trabalhada. A expressão deve considerar os aspectos

relacionados as operações lógicas, que são as operações AND(*), OR(+) e
NOT(’). Para montar o algoritmo para a detecção das operações de cada
equação, considere alguns exemplos:

1) A*B*C
2) A+B+C
3) A*B+C*D
4) A*(B+C)+D
5) A’*B+C’*D’
6) B’*(B’+C)+A*D’
7) (A*B)’+(A+B)’

Repare que os tipos de equações apresentados nos exemplos possuem
um grau de dificuldade crescente conforme a ordem que foram apresentados.
Desta forma, realize a criação do algoritmo por partes, adicionado
funcionalidades conforme o tipo de equação que ele poderá tratar.
Após a inserção da equação, o programa deverá perguntar ao usuário
qual o valor das entradas, conforme a quantidade de variáveis que a expressão
tiver. Feito isso, o programa deverá retornar o valor de saída da expressão.
Retornado o valor, ele deve questionar se o usuário deseja digitar uma nova
combinação de entradas, ou retornar ao menu principal.
Como documentação do projeto, seu grupo deverá entregar:
- O programa criado em um ou mais arquivos .c, até o dia 29/12/2021. Coloque
no cabeçalho de cada arquivo um comentário com o nome do grupo e seus
integrantes. Além disso, indique com comentário quem foi o responsável pela
elaboração e teste de cada uma das funções presentes no arquivo.
- Uma apresentação sobre o programa que foi desenvolvido, indicando qual
membro ficou responsável por qual parte do programa e uma breve revisão
conceitual sobre análise de circuitos e álgebra booleana. Essa apresentação
será feita à banca de professores no dia 30/12/2021, onde todos os integrantes
do grupo devem participar, falando sobre as suas contribuições com o projeto,
explicando o código criado e mostrando a sua execução. A apresentação deverá
ter a duração de 15 a 20 minutos e será seguida de uma arguição da banca.
Assim, cada grupo terá um tempo total de 30 minutos para sua apresentação e
arguição. Os slides a serem utilizados na apresentação devem ser entregues até
o dia 29/12/2021.
