---
layout: wiki
permalink: '/basico'

nomeEditores: Lina Lopes, Mau Jabur
dataUpdate: 23/12/2023
---

# Instrucional Básico {#basico}
Escolha no Menu qual tutorial básico quer seguir.
<div markdown="1" id="soldarcircuitos" class="conteudo-item">

## Como soldar circuitos

{% include como-soldar.html%}

### O que é soldagem?

A soldagem é uma habilidade útil, fácil e divertida para unir peças de metal com um metal de preenchimento, conhecido como solda. Isso cria uma ligação forte e condutora de eletricidade para criar seus próprios projetos eletrônicos.

### Quais ferramentas você precisa para soldar?

- *Ferro de Solda*: Uma ferramenta com uma ponta que aquece para derreter a solda, permitindo unir componentes metálicos em eletrônicos.
- *Solda*: Uma mistura de estanho e chumbo com um núcleo de fluxo usado para criar juntas condutivas e fortes em eletrônicos. O fluxo remove camadas de óxido, garantindo que as juntas de solda não rachem quando expostas a estresse térmico e físico. Você vê o fluxo evaporando durante o processo de soldagem.
- *Suporte / Terceira Mão*: Um dispositivo com grampos ou braços para segurar componentes, liberando suas mãos para o trabalho de soldagem.
- *Esponja*: Usada para limpar a ponta do ferro de solda, removendo solda velha e impurezas para garantir uma transferência de calor eficiente.
- *Cortador de Fios*: Uma ferramenta usada para cortar e aparar fios ou terminais de componentes no comprimento desejado.

### O que você faz antes de soldar?

*Organize os componentes na sua placa de circuito*
- insira os terminais dos componentes nos furos da placa
- dobre os terminais sob a placa para fixar a posição do componente

*Lembre-se das dicas de segurança*
1. A ponta do ferro de solda fica quente o suficiente para derreter metais de solda. Se você tocar a ponta, soltará muito rapidamente!
2. Chumbo é venenoso. Ele fica na sua pele quando você segura a solda, então lave as mãos após soldar!
3. Cortar terminais pode criar projéteis cegantes. SEMPRE segure o terminal que está cortando com uma mão enquanto corta com a outra.

### Como você cria uma conexão de solda?

- *Limpe o Ferro de Solda*: Limpe a ponta quente em uma esponja úmida para remover a solda velha e impurezas, garantindo uma transferência de calor eficaz e juntas de solda limpas.

- *Aqueça o Pad e o Terminal*: Toque a ponta tanto no pad (superfície metálica ao redor do furo na placa de circuito) quanto no terminal (a perna metálica do componente) para aquecê-los uniformemente.

- *Adicione Solda*: Aplique solda na junção onde a ponta do ferro encontra o pad e o terminal, permitindo que a solda flua e crie uma conexão.

- *Remova o Ferro Enquanto a Solda Esfria*: Retire o ferro mantendo a junta soldada parada, permitindo que a solda esfrie e solidifique sem perturbação.

- *Lembre-se*: Para criar uma junta de solda confiável, certifique-se de que a ponta do ferro toque simultaneamente no pad e no terminal para que a solda fundida possa fluir ao redor deles.

### O que você faz após a soldagem?

- *Verifique as Conexões de Solda*: Inspecione cada junta de solda para garantir que esteja lisa, brilhante e unida sem rachaduras.

- *Lide com o Excesso de Solda*: Remova qualquer solda extra das juntas usando um sugador de solda para aspirá-la ou um pano de cobre para absorvê-la.

- *Corte Terminais Excessivos*: Apare quaisquer terminais longos de componentes próximos à junta de solda para evitar curtos-circuitos acidentais.

- *Lembre-se:* Lave as mãos e divirta-se aprimorando suas habilidades de soldagem.
</div>

<div markdown="1" id="usarprotoboard" class="conteudo-item">

### Como usar a protoboard 

Uma protoboard é um dispositivo simples, porém inteligente, para prototipagem rápida de eletrônicos. 
Ela consiste em uma carcaça de plástico com uma série de furos dispostos em linhas e colunas. 
Quando um terminal de componente ou fio é inserido em um desses furos, ele fica eletricamente conectado a qualquer outra coisa inserida em um dos outros furos na mesma linha ou coluna.

![Imagem ilustrativa de uma protoboard](/assets/i/basico/breadboard.png){: .img-fluid}


### Prós e Contras da Protoboard

Protoboards são extremamente úteis para começar a trabalhar com microprocessadores como o Arduino. 
Mas, como tudo na vida, é importante entender seus prós e contras para saber onde podem ser aplicados e quais são suas limitações.
Em muitos casos, um circuito destinado a uma aplicação permanente pode ser prototipado em uma protoboard sem solda e, depois, transferido para uma placa de circuito impresso soldada para construção final, uma vez que todos os problemas tenham sido resolvidos.

*Prós:*

- Protoboards são uma maneira barata e fácil de criar circuitos eletrônicos inserindo componentes e fios nos orifícios da protoboard.
- Não é necessário soldar.
- O circuito pode ser facilmente alterado simplesmente conectando e desconectando componentes e fios conforme necessário.
- Uma vez terminado o circuito, os componentes podem ser facilmente removidos e reutilizados em um novo circuito no futuro.

*Contras:*

Os contras das protoboards estão principalmente relacionados às limitações das conexões elétricas feitas pelos contatos de mola.

- As conexões da protoboard não são tão robustas quanto as conexões soldadas e não são adequadas para operação a longo prazo. Vibrações podem fazer com que as conexões falhem ao longo do tempo.
- Conexões de protoboard podem ter uma resistência maior do que conexões soldadas (cerca de +5 ohms).
- Conexões não são adequadas para fluxo de corrente alta, por exemplo, para um circuito de MOSFET de potência. Devido ao aquecimento resistivo e a um diâmetro máximo de condutor de 20AWG, a corrente geralmente é limitada a cerca de 2A com uma protoboard de boa qualidade.
- Devido à resistência e capacitância dispersas dos condutores, contatos de mola e fios de ligação, protoboards não são adequadas para operação de alta frequência acima de 10MHz.
</div>

<div markdown="1" id="arduinolovers" class="conteudo-item">

## Arduino Lovers

- [Ir para A00](#a00)
- [Ir para A01](#a01)
- [Ir para A02](#a02)


### [A00](#a00)

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSyjJxrExF9MK8NIn9H-y39bi18uhR1mVBi6ZLjevmcnZq8KCLuJM-1Ay-JM9XvwL4kSzurz38w8EqQ/embed?start=false&loop=false&delayms=3000" frameborder="0" width="100%" height="600" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


Esta apresentação introduz o Arduino, uma plataforma de prototipagem eletrônica de código aberto. Explica o que se pode fazer com um Arduino, incluindo a construção de robôs que seguem a luz, cafeteiras que twittam, sistemas automáticos de rega e mais. O foco é no modelo Arduino UNO. É necessário um computador (compatível com Windows, Mac ou Linux) e um cabo USB B para conexão. A apresentação orienta sobre a instalação do software do Arduino a partir do site oficial, com opções para doação ou download direto. Conclui preparando o espectador para os próximos passos na programação do Arduino.


### [A01](#a01)

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ_wzq588o1ObCDzo00-nTMgLjJ5C27I_ly2lyeAdZ4bASO9B-7QhaWCxuj4zH1XEUUgRdISpV99mtq/embed?start=false&loop=false&delayms=3000" frameborder="0" width="100%" height="600" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Esta apresentação introduz o Arduino, uma plataforma de prototipagem eletrônica de código aberto. Explica o que se pode fazer com um Arduino, incluindo a construção de robôs que seguem a luz, cafeteiras que twittam, sistemas automáticos de rega e mais. O foco é no modelo Arduino UNO. É necessário um computador (compatível com Windows, Mac ou Linux) e um cabo USB B para conexão. A apresentação orienta sobre a instalação do software do Arduino a partir do site oficial, com opções para doação ou download direto. Conclui preparando o espectador para os próximos passos na programação do Arduino.