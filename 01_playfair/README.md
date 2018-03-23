
-O que você fez
 Neste 1º trabalho eu fiz tudo na questão de estar colocando o código para rodar na IDE.

-Com quem e como você fez
Fiz com meu colega, Antônio Matheus Cavalcante da Silva. Nós fizemos em conjunto, discutindo a lógica ideal para se resolver o problema.
O problema foi resolvido da seguinte maneira: Criamos uma função para validar a chave. Se contiver a letra (K) então não poderia continuar já que ela foi retirada para poder facilitar o problema. Após a chave ser validade a matriz é montada a partir da chave que é passada na função monta_matriz(). Como não consegui já formar a matriz 5x5 com seus respectivos elementos, primeiramente criei um vetor que tinha os 25 elementos (respectivas letras montadas a partir da chave), e após isso usei slices para jogar em outro vetor, podento assim finalmente ter uma matriz 5x5. Após ter a matriz pronta é chamada a função cifra_msg(msg), na qual é passada a mensagem que o usuário quer cifrar, que também não deve conter a letra (K). A mensagem passa por um (FOR) em joga apenas as letras pertencentes a mesangem, ignorando por sua vez os espaços. Após isso são feitos os bigramas, respeitando as regras de que não podem terminar em um número ímpar as letras e caso letras se repitam, dependendo da letra em questão, na posição onde ela se encontra, será adicionada uma nova letra que pode ser "X" ou "Z". Em seguida eu crio outro vetor onde eu irei pegar de duas em duas letras da mensagem e guardar em cada posição desse outro vetor, as posição de onde essas letras se encontram na matriz 5x5 para posteriormente fazer as comparações (se estão em mesma linha, mesma coluna ou linhas e colunas diferentes). Logo após isso crio outro vetor no qual serão inseridas as letras após sempre cifradas seguindo as regras. Como elas ficam todas em um vetor, porém em posições diferentes, como estão na ordem correta, basta apenas usar a função (join()) que juntará os elementos finalmente ficando a palavra cifrada no final. O de decifragem faz praticamente a mesma coisa só que não precisa da parte de formar os bigramas, pois entende-se que a palavra que foi cifrada já passou por esse processo.

-O que aprendeu e sabe fazer
Aprendi a guardar posições de elementos de um vetor fazendo a comparação com elemento que coincidem com o mesmo. Aprendi também a usar o método insert em um vetor que coloca um elemento na posição passada e o restante depois desse elemento é passado para a direita. Do trabalho por completo eu sei fazer tudo. Meu problema inicial foi pegar a lógica, após isso tudo é fácil de desenrolar

-O que tem dificuldade ainda
Não tenho dificuldade, porém no decorrer do processo tive dificuldade para entender a lógica da cifra de PlayFair. Tive ajuda do meu colega Matheus que martelou bastante e desenhou até que eu finalmente entendesse.

-Quanto tempo levou pra fazer a atividade
Foram cerca de umas 10h para terminar, pois começamos no laboratório, continuamos no ônibus na ida para casa, fizemos mais um pouco no final de semana e terminamos no dia em que deveria ser entregue pois continha alguns erros.
