# Stock Market
Repositório do meu jogo de mercado de trocas. Inclui as versões para Windows e para Android

<p>Este projeto consiste no desenvolvimento de um jogo sobre <b>mercados de stock</b>, onde o
objetivo principal é <b>acumular dinheiro</b> e <b>sobreviver o máximo de dias
possível</b>.</p>
<p>O jogo baseia-se em decisões estratégicas de <b>compra</b> e <b>venda</b> de produtos. Para isso, o
utilizador deve tentar <b>comprar produtos quando estão baratos para depois vendê-los quando
estão caros</b>. Os preços <b>mudam todos os dias</b>, dentro de um alcance específico, por isso o
utilizador deve tentar perceber esse alcance para cada artigo, a fim de saber quando é seguro
investir neles.</p>
<p>Além disso, o utilizador é obrigado a <b>pagar uma renda</b> todos os dias, que vai aumentando
com o tempo. Isto requer uma estratégia mais exigente, obrigando o utilizador a guardar sempre
um pouco de dinheiro para continuar a jogar. Também se deve ter o cuidado com o número de
investimentos, uma vez que o artigo pode manter um preço baixo no dia seguinte, o que pode
fazer o jogador ficar sem dinheiro para pagar a renda.</p>

<p><img width="1919" height="1197" alt="Captura de ecrã 2026-01-29 162847" src="https://github.com/user-attachments/assets/2e994633-3c09-43cf-87b7-6053e4bea5a6" /></p>

<p>Funcionalidades e Características:</p>

- <b>Compra e Venda de Stock</b> – O utilizador pode comprar e vender stock para tentar obter o melhor valor possível, dentro dos requisitos de cada artigo. A quantidade de stock do utilizador é guardada numa variável global. Cada artigo tem um multiplicador, para facilitar a compra e venda de grandes quantidades de produtos
- <b>Criação de um Perfil no Sistema</b> – O utilizador requer um perfil para poder jogar. Ao iniciar o programa, será pedida a inserção de uma conta (email + password), juntamente com a opção de criar uma conta. A criação de um perfil requer também um username e uma imagem de perfil, que podem ser alterados mais tarde se o utilizador assim entender. Cada perfil será armazenado online numa base de dados, para que o utilizador possa aceder à sua conta em vários dispositivos
- <b>Sistema de Dias</b> – O utilizador deve tentar sobreviver ao máximo de dias, sem que perca todo o dinheiro que tem. Avançar o dia requer apenas uma condição, ter dinheiro suficiente. Se o utilizador tentar avançar o dia sem dinheiro para a renda, o jogo acaba, caso contrário, a renda é paga e o mercado reinicia (os preços mudam)
- <b>Estatísticas e Recordes</b> – Os utilizadores podem ver as suas estatísticas no perfil, o qual inclui o recorde de dias alcançado, maior valor de dinheiro obtido, número de conquistas desbloqueadas, entre outras. Cada utilizador pode também comparar as suas estatísticas com outros jogadores, através do menu de rankings. Nesse menu podemos ver os jogadores com o número de dias alcançado mais alto ou os jogadores que obtiveram o maior lucro nas trocas
- <b>Conquistas (Windows apenas)</b> – O jogo inclui conquistas, que requerem que o utilizador atinga metas específicas. Por agora existem dois tipos de conquistas: Chegar a x dia e Acumular 1000 de x produto. Quando o utilizador alcança uma conquista durante o jogo, uma notificação aparecerá na parte inferior do ecrã
- <b>Modos de Jogo (Windows apenas)</b> – O projeto tem dois modos de jogo: Dia e Noite. Dia é o modo normal, onde os jogadores são postos com uma renda equilibrada. Noite é um modo mais estratégico, com rendas mais elevadas, mas uma carteira mais pesada no começo. O modo Noite também acrescenta um timer de 5 minutos, forçando o user a ser mais rápido com as suas trocas durante cada noite. Sempre que uma noite é avançada, são retirados 10 segundos do tempo base do timer. Estes modos de jogo existem para fornecer diferentes estilos de jogo aos utilizadores, de forma a que cada um possa escolher o modo mais confortável para si, ou, no caso do modo Noite, oferecer um maior desafio para jogadores mais experientes

<p><img width="1919" height="1199" alt="Captura de ecrã 2026-01-29 162912" src="https://github.com/user-attachments/assets/2c2f5188-4524-4fb7-ba80-d444837cf4f4" /></p>

<p>Ferramentas Utilizadas:</p>

- <b>Unity</b> – Motor de jogo usado para criar a interface, lógica e exportação do jogo.
- <b>C#</b> – Linguagem de programação principal para desenvolver a lógica do jogo.
- <b>Firebase</b> – Base de dados online para guardar perfis de utilizador e estatísticas.
- <b>Visual Studio 2022</b> – Editor de código onde a lógica será programada, usando C#
- <b>Piskel, Paint e PowerPoint</b> – Design dos elementos gráficos do projeto
- <b>Unity Version Control</b> – Controlo e gestão das versões do projeto + armazenamento externo do
source code
- <b>Android Studio (Kotlin + XML)</b> - Versão Android

<p><img width="1919" height="1199" alt="Captura de ecrã 2026-01-29 162902" src="https://github.com/user-attachments/assets/7507a0a9-ded6-48d3-9d90-b9871e290e4d" /></p>

<p>O source code será distribuído em breve</p>
