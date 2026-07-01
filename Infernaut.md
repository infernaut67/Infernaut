\# Infernaut



\## Game Design Document (GDD)



\*\*Versão:\*\* 1.0

\*\*Status:\*\* Pré-produção

\*\*Engine:\*\* Godot

\*\*Linguagem:\*\* GDScript

\*\*Plataformas:\*\* PC e Android
\*\*Requisitos mínimos:\*\*

Minimos
i5 2500 ou ryzen 3 1200
4 gb RAM
hd 7850 ou gt 740
50mb de espaço livre

\*\*Gênero:\*\* Run and Gun / Plataforma de Ação 2D



\---



\# Visão Geral



\## Conceito



Infernaut é um jogo de ação 2D inspirado nos clássicos run and gun dos anos 80 e 90. O jogador assume o papel de um bombeiro equipado com tecnologia especial capaz de combater criaturas de fogo e sobreviver em ambientes devastados por incêndios sobrenaturais.



O jogo combina movimentação rápida, combate intenso, chefes desafiadores e progressão simples.



\---



\# Objetivos do Projeto



\* Criar uma experiência de ação rápida e divertida.

\* Homenagear os clássicos do gênero.

\* Funcionar tanto em dispositivos móveis quanto em computadores.

\* Possuir escopo viável para desenvolvimento independente.



\---



\# História



Uma série de incêndios misteriosos começa a surgir pelo mundo.



As chamas parecem possuir vida própria e transformam tudo ao seu redor em criaturas flamejantes.



Durante uma operação de emergência, um bombeiro encontra um equipamento experimental capaz de canalizar água pressurizada em ataques extremamente poderosos.



Agora ele deve enfrentar a origem da infestação antes que o planeta seja consumido pelo fogo.



\---



\# Gameplay



\## Loop Principal



1\. Entrar na fase.

2\. Avançar derrotando inimigos.

3\. Coletar recursos.

4\. Enfrentar um chefe.

5\. Concluir a fase.

6\. Prosseguir para a próxima área.



\---



\# Personagem Principal



\## Bombeiro



\### Habilidades



\* Andar

\* Correr

\* Pular

\* Agachar

\* Atirar em múltiplas direções



\### Atributos



\* Vida

\* Velocidade

\* Poder de ataque



\---



\# Sistema de Combate



\## Arma Principal



\### Mangueira de Alta Pressão



Características:



\* Munição infinita

\* Disparo contínuo

\* Dano básico

\* Alcance médio



\---



\# Sistema de Vida



\* Barra de vida

\* Checkpoints durante as fases

\* Continues limitados



\---



\# Inimigos



\## Faísca



Pequena criatura flamejante.



Comportamento:



\* Anda em direção ao jogador.



\---



\## Chama Voadora



Criatura aérea.



Comportamento:



\* Move-se pelo cenário.

\* Ataca por contato.



\---



\## Soldado Flamejante



Inimigo mais resistente.



Comportamento:



\* Dispara projéteis de fogo.

\* Mantém distância do jogador.



\---



\## Torre de Fogo



Estrutura fixa.



Comportamento:



\* Dispara em intervalos regulares.



\---



\# Chefes



\## Núcleo Infernal



Entidade responsável pela propagação das chamas.



\### Ataques



\* Bolas de fogo

\* Ondas de calor

\* Investidas



\### Fases



\#### Fase 1



Ataques básicos.



\#### Fase 2



Ataques mais rápidos.



\#### Fase 3



Combinação de todos os ataques.



\---



\# Estrutura das Fases



\## Fase 1 - Cidade em Chamas



Objetivo:



Introduzir os controles e mecânicas básicas.



Elementos:



\* Ruas destruídas

\* Prédios incendiados

\* Inimigos básicos



\---



\## Fase 2 - Zona Industrial



Objetivo:



Aumentar a dificuldade.



Elementos:



\* Plataformas móveis

\* Tubulações

\* Novos inimigos



\---



\## Fase 3 - Complexo Vulcânico



Objetivo:



Preparar o jogador para o chefe final.



Elementos:



\* Lava

\* Armadilhas ambientais

\* Grande quantidade de inimigos



\---



\## Fase Final - Coração das Chamas



Objetivo:



Derrotar o Núcleo Infernal.



Elementos:



\* Arena de chefe

\* Obstáculos de fogo

\* Desafio máximo



\---



\# Controles



\## PC



\### Teclado



\* A / D = Movimento

\* W = Olhar para cima

\* S = Agachar

\* Espaço = Pular

\* J = Atirar



\---



\## Android



\### Interface Touch



\* Analógico virtual esquerdo

\* Botão de pulo

\* Botão de tiro



\---



\# Interface do Usuário



\## HUD



Exibir:



\* Barra de vida

\* Continues restantes

\* Progresso da fase

\* Tela de pausa



\---



\# Direção de Arte



\## Estilo



Pixel Art.



\## Resolução Base



320x180.



\## Paleta



\### Herói(Bombeiro)



\* Laranja

\* Vermelho

\* Cinza



\### Inimigos



\* Vermelho

\* Laranja

\* Amarelo



\### Ambientes



\* Tons escuros

\* Contraste forte entre fogo e água



\---



\# Áudio



\## Música



\* Rock retrô

\* Eletrônica industrial

\* Temas de ação



\## Efeitos Sonoros



\* Jatos de água

\* Explosões

\* Chamas

\* Passos

\* Sons de chefes



\---



\# Arquitetura do Projeto



\## Cenas Principais



MainMenu



Game



Level01



Level02



Level03



BossStage



Player



Enemy



Boss



HUD



PauseMenu



GameOver



Victory



\---



\# Estrutura de Pastas



res://



├── scenes/



├── scripts/



├── sprites/



├── audio/



├── ui/



├── effects/



└── data/



\---



\# MVP (Primeira Versão Jogável)



\## Conteúdo



\* 1 personagem jogável

\* 1 arma principal

\* 3 tipos de inimigos

\* 1 chefe

\* 1 fase completa

\* Sistema de vida

\* Sistema de checkpoints

\* Controles para PC

\* Controles para Android



\---



\# Metas Futuras



\* Novas armas

\* Sistema de upgrades

\* Mais chefes

\* Mais fases

\* Modo difícil

\* Conquistas

\* Ranking de pontuação



\---



\# Resumo



Infernaut é um run and gun 2D focado em ação rápida, inspirado nos clássicos do gênero como Contra(NES). O jogador controla um bombeiro equipado com tecnologia avançada para combater criaturas de fogo e impedir uma catástrofe global causada por uma força misteriosa que controla as chamas.



