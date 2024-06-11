# GDD #
## Nome do Jogo: Mind House ##

### 1. Visão Geral ###
#### 1.1. Resumo ####
- **Gênero**: Terror
- **Enredo**: O jogador está preso numa casa e precisa de explorar a mesma para encontrar três chaves e descobrir o porquê de estar nessa casa. A casa simboliza o limbo e a apatia mental do protagonista, que está a lidar com os stresses da vida adulta. Ao avançar no jogo, o jogador percebe que a felicidade inocente da infância é crucial e não deve ser perdida. A narrativa do jogo tenta ser o mais ambígua possível para o jogador poder auto inserir-se no papel do protagonista e para poder tirar as suas próprias conclusões da história.
- **Mecânica de Jogo**: Exploração, encontrar e obter itens e evitar o inimigo.
- **Ambiente**: Casa 3D com câmera em primeira pessoa, composta por dois andares.

#### 1.2. Cenas ####
- **Menu Principal**: Cena inicial onde podemos começar um jogo novo ou sair do jogo.
- **Tutorial**: Cena que contextualiza o jogador para a situação em que se encontra e explica as mecânicas básicas do jogo.
- **Jogo**: Cena onde decorre o jogo em si.
- **Game Over**: Cena que ocorre após o jogador ser apanhado pelo inimigo, permitindo sair do jogo ou voltar ao menu principal.
- **Fim**: Cena que ocorre quando o jogador chega ao fim do jogo depois de abrir a porta com a Chave de Ouro.

### 2. Elementos Principais ###
#### 2.1. Gameplay ####
- **Exploração**: O jogador explora a casa em busca de notas que dão contexto narrativo e chaves, evitando o inimigo que se encontra a patrulhar. Os objetos interativos são indicados por um cursor em forma de mão.

#### 2.2. Ambiente ####
- **Visão**: Câmera em primeira pessoa para maior imersão.
- **Design**: Casa com dois andares, contendo 10 divisões, 3 armários, diversas luzes e diversas portas e mobília para garantir imersão total.
- **Interface**: Interface mínima para imersão máxima do jogador.
- **Música**: Banda sonora variável dependendo do estado do inimigo, ajudando na imersão.
- **Efeitos Sonoros**: Efeitos sonoros imersivos para fornecer um bom ambiente de terror.

#### 2.3. Inimigo ####
- **Comportamento**: O inimigo patrulha áreas específicas e persegue o jogador ao detectá-lo. Se perder o jogador de vista, volta à última posição conhecida do jogador e procura na área durante um tempo, até reencontrar o jogador ou caso não o encontre volta à patrulha.
- **Consequência**: O inimigo apanhar o jogador resulta em game over.

### 3. Mecânicas Específicas ###
#### 3.1. Exploração ####
- **Objetivos**: Procurar pelas seis notas e três chaves específicas (bronze, prata e ouro).
- **Interação**: Jogador pode andar, obter objetos, ligar/desligar luzes, abrir/fechar portas e tem acesso a um inventário com 9 slots.

#### 3.2. Evitar o Inimigo ####
- **Evasão**: Jogador deve evitar ser detectado pelo inimigo. Não há botão de agachar nem maneira de diminuir a visão do inimigo, então baseia-se em evitar a linha de visão do inimigo e usar o ambiente para se esconder.
- **Inimigo**: Inimigo pode abrir portas e segue uma patrulha específica com vários pontos.

### 4. Itens e Objetos ###
#### 4.1. Chaves ####
- **Chave de Bronze**: Primeira chave necessária para abrir a porta onde se encontra a chave de prata. Localizada nos Arrumos em cima de um cesto de roupa.
- **Chave de Prata**: Segunda chave necessária para progredir no jogo, abrindo a porta que dá acesso à garagem. Localizada no quarto onde se encontra o urso de peluche e a cadeira de balançar.
- **Chave de Ouro**: Chave final necessária para abrir a porta de saída e concluir o jogo. Localizada na Garagem.

#### 4.2. Notas ####
- **Descrição**: Seis notas espalhadas pela casa que fornecem informações sobre a história e o estado mental do protagonista, sendo que três se encontram com as chaves para máximo contexto narrativo e as restantes fornecem contexto adicional, mas não são necessárias para a compreensão completa da história.
  - **URGÊNCIA**: Primeira nota encontrada ao lado da Chave de Bronze que mostra a urgência da tarefa de escapar e também o quão desesperante é a situação.
  - **AMIGO**: Segunda nota encontrada ao lado da Chave de Prata que aprofunda a conexão emocional evocando momentos da infância e de felicidade.
  - **LIBERTA**: Última nota principal encontrada ao lado da Chave de Ouro que renova o sentimento de esperança e que o objetivo está mesmo ao alcance do jogador.
  - **INFÂNCIA**: Nota adicional para oferecer contexto paternal e da infância do protagonista localizada em cima de uma mesa de cabeceira no Quarto perto das escadas.
  - **ROTINA**: Nota adicional para mostrar o estado mental lastimável do protagonista localizada num móvel perto dos sofás na Sala.
  - **AQUILO**: Nota adicional a falar do inimigo e oferecendo algum contexto adicional sobre ele localizada na casa de banho do Quarto longe das escadas.

### 5. Interface do Utilizador ###
#### 5.1. HUD e Menus ####
- **Inventário**: Menu com 9 slots para itens.
- **Menu de Pausa**: Opções para retomar o jogo, voltar ao menu principal e sair do jogo.

### 6. Design de Nível ###
#### 6.1. Estrutura da Casa ####
- **Andares**: Dois andares com várias salas e áreas específicas.
  - **Andar de Cima**: Quarto inicial com armário, Casa de Banho principal, Quarto perto das escadas, Quarto longe das escadas que tem uma casa de banho privada e um quarto onde se encontra o urso de peluche e a cadeira de balançar.
  - **Andar de Baixo**: Sala com um armário, Cozinha, Arrumos, Garagem.
- **Portas Trancadas**: Porta do quarto onde se encontra o urso de peluche e a cadeira de balançar, Porta da Garagem e Porta de Saída que requerem as chaves de bronze, prata e ouro respetivamente para serem abertas.




