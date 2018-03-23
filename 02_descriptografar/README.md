-O que você fez
Montei a lógica usada para realizar a primeira parte do trabalho que é como montar as combinações possíveis para descriptografar o texto e também joguei no código essa lógica, que é usando 8 FORs para ir montando as combinações.

-Com quem e como você fez
Fiz com meu colega Antonio Matheus Cavalcante da Silva, Esdras Emanuel Mariano Moreira.
Usei a linguagem python para resolver o problema. Primeiramente fiz de uma maneira errada. Usei uma função pronta de permutações que montava todas as combinação possível de 8 caracteres que vão de A a Z. Essas combinações eram todas colocadas em um único vetor, porém como dava mais de 200 bilhoes de possibilidades estava comendo muita memória, infelizmente demoramos um pouco para perceber isso. Rodamos em IDEs online, notebook e até mesmo no celular do Matheus. Depois usamos 8 FORs que montavam as possibilidades de combinações e quando não batia com o padrão encontrado ele apaga a combinação montada e adicionava a próxima, assim ocupando sempre o mesmo espaço de memória e não sobrecarregando a máquina. A cada combinação montada, era chamada uma função (desc(chave, v)) na qual são passadas a combinação atual e a mensagem a ser descriptografada. Essa função descriptografa essa mensagem usando a chave passada na função após descriptografar, é verificado se naquela mensagem existe a palavra amor. Usando na força bruta haverão várias combinações que acarretarão na palavra amor na mensagem cifrada, porém apenas uma dará sentido ao texto por inteiro. Na primeira vez que encontramos o padrão da palavra amor, as letras da chave que descriptografavam eram as 4 últimas, mas percebemos que no restante do texto onde essas 4 letras descriptografavam não faziam nenhum sentido. Após isso procuramos o padrão com as 4 primeiras letras. A 3º palavra da mensagem dava amor, e logo notamos que o restante do texto onde as 4 primeiras letras descriptografavam começavam a fazer sentido. Logo depois só precisamos manipular manualmente a chave completando os restantes das letras que poderiam fazer sentido. Quando descobrimos as 5 primeiras letras (aluno) ficou mais dedutivo de se responder qual a cifra correta. Ao testarmos a chave alunoufc descobrimos a senha. Ficamos sem acreditar no começo mas comemoramos bastante na madrugada em que tudo se resolveu.

-O que aprendeu e sabe fazer
Eu aprendi duas coisas. Como montar combinações sendo passados determinados elementos, que infelizmente não é a opção ideal quando se tem mais de 200 bilhões de possibilidades e como montar combinações e testá-las usando apenas FORs e TABELA ASCII.

-O que tem dificuldade ainda
Não tenho dificuldades. 

-Quanto tempo levou pra fazer a atividade
Levamos cerca de 8h, pois começamos na faculdade e terminanos de madrugada em casa.
