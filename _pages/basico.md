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

## Como usar a protoboard 

Uma protoboard é um dispositivo simples, porém inteligente, para prototipagem rápida de eletrônicos. 
Ela consiste em uma carcaça de plástico com uma série de furos dispostos em linhas e colunas. 
Quando um terminal de componente ou fio é inserido em um desses furos, ele fica eletricamente conectado a qualquer outra coisa inserida em um dos outros furos na mesma linha ou coluna.

![Imagem ilustrativa de uma protoboard](/assets/i/basico/breadboard.png){: .img-fluid}


### Prós e Contras da Protoboard

Protoboards são extremamente úteis para muitos projetos e são praticamente indispensáveis para trabalhar com Arduino e microprocessadores semelhantes, mas é importante entender seus prós e contras para saber onde podem ser aplicadas e onde podem não funcionar conforme você espera.

**Prós:**

- Protoboards fornecem uma maneira barata e fácil de começar com um conjunto de prototipagem eletrônica.
- Circuitos podem ser construídos facilmente e rapidamente, simplesmente inserindo componentes e fios nos furos da protoboard. Fios-jumper também podem ser usados para conectar o circuito a um microcontrolador ou outro dispositivo externo, conforme necessário.
- Não é necessário soldar.
- Mudanças no circuito podem ser feitas facilmente, simplesmente conectando e desconectando componentes e fios conforme necessário.
- Uma vez que você termina com o circuito, os componentes podem ser facilmente removidos e reutilizados em um novo circuito no futuro.

**Contras:**

Os contras das protoboards estão principalmente relacionados às limitações das conexões elétricas feitas pelos contatos de mola. A qualidade desses contatos tem um impacto significativo em quão grande é o problema de qualquer um desses contras, e isso será abordado em detalhes mais tarde.

- Conexões não são tão robustas quanto as soldadas e não são adequadas para circuitos colocados em operação permanente de longo prazo. Vibração ou choque na montagem pode fazer com que as conexões falhem com o tempo.
- Se a protoboard tiver contatos de má qualidade, as conexões podem ser intermitentes se os terminais forem mexidos.
- Conexões podem ter uma resistência (impedância) maior do que uma conexão soldada. Essa impedância é afetada pela qualidade dos contatos usados na protoboard, pelo tamanho do componente ou fio inserido nos contatos e pelo quanto os contatos foram usados. Em alguns casos, isso pode ser como adicionar um resistor de série de 5 ohms a uma conexão de circuito. Se essa pequena impedância cria um problema para o circuito depende do tipo de circuito que é.
- Conexões não são adequadas para fluxo de corrente alta, como pode ser necessário ao prototipar algo como um circuito de MOSFET de potência. Isso se deve principalmente à maior impedância dessas conexões, que pode causar aquecimento resistivo, e ao fato de que o diâmetro máximo do terminal é limitado a 20AWG, que é pequeno demais para lidar com correntes maiores. A corrente geralmente é limitada a cerca de 2A com uma protoboard de boa qualidade.
- Conexões não são adequadas para componentes que dependem de uma grande conexão de terra para alguns de seus terminais para dissipação térmica, como pode ser o caso com algo como um CI de amplificador de potência operando em altos níveis de potência. Para trabalhos experimentais com protoboards, estes podem ser frequentemente operados em níveis mais baixos, onde a dissipação de calor não é necessária, ou um dissipador de calor pode ser adicionado ao dispositivo para ajudar na dissipação de calor.
- Conexões não são adequadas para trabalhos de frequência muito alta, pois a resistência e a capacitância parasitas dos terminais, contatos de mola e fios-jumper podem introduzir alguma degradação nas formas de onda, como sinais de clock, à medida que a frequência aumenta. 1MHz geralmente é seguro e circuitos operando em até 10MHz a 16MHz são geralmente possíveis se cuidado for tomado no layout e a protoboard for de boa qualidade.
- Nodos de conexão para alguns tipos de circuitos precisam ser mantidos o mais curtos possível para que um circuito funcione corretamente. A técnica de construção da prot
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