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

Soldagem é uma habilidade útil, fácil e divertida para unir peças de metal com um metal de preenchimento, conhecido como solda. Isso cria uma forte ligação elétrica que permite criar seus próprios projetos eletrônicos.

### Quais ferramentas você precisa para soldar?

- ferro de solda
- solda de boa qualidade
- suporte = 3ª mão
- esponja
- cortador de fio
- solda

### Quais componentes você precisa para soldar?

circuitos eletrônicos
- componentes em uma Placa de Circuito Impresso (PCI)
- terminais, almofadas e trilhas para fácil montagem

### Como você solda?

#### Como se preparar para soldar?

cuidado / atenção

segurança


- pegue o componente e a superfície alvo, resistor em uma PCI
- dobre seus terminais
- insira os terminais através das almofadas da PCI para posicionar o resistor

#### Como fazer a conexão da solda
- como limpar o ferro de solda
- aqueça a almofada e o terminal
- adicione solda
- remova o ferro enquanto a solda esfria
- como garantir uma boa conexão
	- ponta tocando a almofada e o terminal com solda derretida formando ao redor deles

### Finalizando o Processo de Soldagem
- como verificar boas conexões de solda
- como lidar com excesso de solda
	- sugá-lo
como cortar terminais excessivos.

### Dicas Pós-Soldagem
Sugestões para melhorar as habilidades de soldagem ao longo do tempo, e um lembrete da importância da segurança e prática.
- Praticar melhora as habilidades de soldagem
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