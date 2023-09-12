# Jogo da Velha em C

Este repositório contém o código-fonte de um jogo da velha implementado em linguagem C. O jogo permite que dois jogadores joguem ou que um jogador enfrente o computador. Abaixo, fornecemos uma análise detalhada do código.

## Estrutura do Código

### Bibliotecas
O código começa incluindo várias bibliotecas padrão do C, como `stdio.h`, `string.h`, `stdlib.h`, `windows.h`, `time.h` e `locale.h`. Essas bibliotecas fornecem funcionalidades para manipulação de entrada/saída, manipulação de strings, alocação dinâmica de memória, temporização e configuração de localização.

### Variáveis Globais
O código utiliza diversas variáveis globais para armazenar informações importantes, como a matriz do tabuleiro, o número de jogadas, a escolha do jogador, entre outras.

### Struct
Uma estrutura chamada `t_dados` é definida para armazenar informações sobre os jogadores, incluindo seus nomes e o número de vitórias.

### Funções Principais

#### `rank()`
Esta função lida com a classificação dos jogadores, registrando suas vitórias em um arquivo chamado "ranking.txt". Os nomes dos jogadores e o número de vitórias são armazenados no arquivo.

#### `tabela()`
A função `tabela()` é responsável por exibir o tabuleiro do jogo na tela, atualizando-o conforme as jogadas são feitas.

#### `menu()`
A função `menu()` apresenta um menu principal que permite ao jogador escolher entre diferentes opções, como jogar, ver o ranking geral, visualizar créditos ou sair do jogo.

#### `propriedade()`
A função `propriedade()` aloca dinamicamente memória para a matriz que representa o tabuleiro do jogo. Ela inicializa a matriz com espaços vazios.

#### `interacao()`
A função `interacao()` lida com a interação entre os jogadores ou entre o jogador e o computador, dependendo da escolha feita pelo usuário. Ela solicita as coordenadas para o próximo movimento e verifica se a posição escolhida é válida.

#### `VerificaVitoria()`
Esta função verifica se algum dos jogadores venceu o jogo ou se houve um empate. Ela identifica a vitória ou empate com base no estado atual do tabuleiro.

#### `main()`
A função `main()` é a função principal do programa. Ela inicia o jogo, exibe o menu principal e controla o fluxo geral do jogo. O jogo é executado em um loop que permite jogar novamente ou sair do jogo após o término de uma partida.

## Conclusão

Este código implementa um jogo da velha funcional em linguagem C. Ele oferece uma experiência interativa para dois jogadores ou um jogador contra o computador. Além disso, o código possui recursos adicionais, como registro de vitórias e opções de visualização de ranking e créditos. O código é uma ótima demonstração de programação em C e é adequado para fins educacionais e de entretenimento.
