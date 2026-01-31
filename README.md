# Jogo: História da Lunda

Este é um jogo para computadores desenvolvido em **Java Swing** que visa testar e ensinar conhecimentos sobre a rica história do Império Lunda, abrangendo desde as suas origens com a Rainha Lueji até a atualidade.

## Funcionalidades

* Banco de Dados de Questões: Contém 50 perguntas variadas sobre cultura, sociedade, conflitos e figuras históricas.
* Sistema de Cronômetro: Cada pergunta deve ser respondida em até **15 segundos**, incentivando o raciocínio rápido.
* Feedback Visual Imediato: O jogo indica em tempo real se a resposta está correta (verde) ou incorreta (vermelho).
* Aleatoriedade: As perguntas são embaralhadas a cada nova partida usando `Collections.shuffle`.
* Pontuação Acumulativa: Sistema de pontos que recompensa o acerto do usuário.

## Tecnologias Utilizadas

* Linguagem: Java
* Interface Gráfica: Java Swing (JFrame, JPanel, JButton)
* Componentes:
* `javax.swing.Timer` para a gestão do tempo.
* `ArrayList` para armazenamento dinâmico de objetos da classe `Questao`.

## Como Jogar

1. Ao iniciar o jogo, uma pergunta aleatória será exibida no painel central.
2. Você tem 15 segundos para escolher uma das três opções (A, B ou C).
3. Se acertar: O botão fica verde e você ganha 2 pontos.
4. Se errar: O botão clicado fica vermelho e a resposta correta é destacada em verde.
5. O jogo termina após percorrer todas as questões disponíveis ou ao fechar a janela.

## Estrutura do Código Principal

O arquivo `Jogo.java` é o motor principal do aplicativo:

* `perguntasEOpcoes()`: Método responsável por popular a lista de perguntas.
* `processarResposta(int escolha)`: Lógica que valida o acerto e atualiza a interface.
* `iniciarCronometro()`: Controla a contagem regressiva de cada rodada.
* `carregarPergunta()`: Atualiza os textos dos botões e labels para a pergunta atual.

## Temas Abordados

* Reino Lunda e a Rainha Lueji.
* Expansão e Migrações (Bangalas, Chokwe, Luvaras).
* Cultura e Tradições (Mukanda, Sona, Máscaras).
* Geografia e Recursos (Rio Cassai, Diamantes).

Para tornar o seu jogo ainda mais profissional e envolvente, aqui estão as sugestões de melhorias futuras que você pode adicionar ao seu arquivo `README.md` ou ao seu plano de desenvolvimento:

### Melhorias Futuras

* Sistema de Áudio Imersivo: Inclusão de efeitos sonoros para respostas certas (sucesso) e erradas (alerta).
* Trilha sonora de fundo com músicas tradicionais da cultura Lunda para maior imersão.
* Som de "tique-taque" acelerado quando o cronômetro estiver abaixo de 5 segundos.

* Níveis de Dificuldade: Implementação de níveis (**Fácil, Médio e Difícil**).
* Variação do tempo de resposta (ex: 20s no fácil, 10s no difícil).
* Filtragem de perguntas por complexidade histórica.

* Sistema de Prêmios e Conquistas: Emblemas digitais (ex: "Historiador Iniciante", "Mestre da Lunda").
* Galeria de troféus baseada na pontuação final.
* Certificado virtual gerado ao acertar 100% das questões.

* Futuramente criar também uma versão para Android

* Modo Multiplayer Local: Disputa em turnos entre dois jogadores para ver quem pontua mais rápido.
* Interface Responsiva e Design: Transição para o visual *Flat Design* com ícones personalizados.
* Inclusão de imagens históricas e mapas da região para cada pergunta.

* Ranking Global (Leaderboard): Integração com um banco de dados simples (ou arquivo local) para salvar as melhores pontuações dos jogadores.

 **Nota**: Este projeto foi desenvolvido com fins pedagógicos para a valorização do património histórico angolano.
