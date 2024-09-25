---
layout: post
title: serviço de rede <i>melhor esforço</i>
date: 2015-03-15 23:30:00
description: não espperes ter sempre toda a largura de banda nas ligações de rede
tags: tráfego rede dados transferência melhor esforço
categories: network
featured: true
---

As redes IP, operam na base do melhor esforço. É o caso das redes de pequena, média e grande dimensão que encontramos de há uns anos a esta parte em nossas casa, empresas, incluindo organizações com presença em todo o mundo e, na maior de todas as redes, a Internet.

Mas afinal o que significa e ao que é que se refere o termo <i>melhor esforço</i>?

Este termo é usado devido à abordagem relativa à qualidade do serviço prestado dado que a rede em si não diferencia ativamente o seu comportamente no que respeita aos serviços que transitam na rede.

Em termos simples, isto significa que numa rede de melhor esforço, todos os pacotes IP são tratados da mesma maneira. A rede faz o "melhor esforço" para transportar e entregar ao destino cada pacote, tão rapidamente quanto possível, sem qualquer compromisso de tratamente priveligiado de nenhum tipo de pacote.

Embora pareça uma abordagem imparcial e justa, não é incomum ouvir-se que, dependendo do contexto ou aplicação, o “melhor esforço” não é suficiente. É habitual pedirem-nos que, de alguma forma, determinada aplicação ou tipo de tráfego tenham um tratamento priveligiado - "melhor que o melhor esforço”.

No entanto, o modelo base do IP não foi inicialmente concebido para tratar uma ou outra aplicação de forma distinta. Basta fazermos um exercício simples: se fosse possível dar prioridade a determinada aplicação, tipo de tráfego, posto de trabalho ou servidor indiscriminadamente, rápidamente surgiriam inúmeras prioridades e, em simultâneo, tudo o resto deixava de comunicar!


As primeiras redes de telefone públicas tinham de facto uma abordagem muito distinta das redes IP. Estas redes, tinham por base uma rede - componentes centrais - muito elaborada que suportavam dispositivos periféricos muito simples. Na altura, um telefone era um dispositivo constituído apenas por um microfone e um altifalante sem qualquer capacidade em si próprio de fazer nada o que colocava na própria rede, a capacidade de estabelecer a ligação em tempo real entre dois telefones.

A verdade que a rede telefónica global é uma obra de engenharia extremamente complexa. Os telefones estão nos extremos com simples conversores de sinais analógico para digitais. Estes sinais eram alimentados em <u>comutadores de circuitos</u> que estabeleciam ligações entre telefones a pedido.

Nos componentes centrais da rede, havia dispositivos responsáveis pela multiplexagem dos sinais o que permitia intercalar fluxos de dados de frequências mais baixas (até 64 Kbps) de telefones, em sinais de frequências maiores no centro da rede telefónica.

A abordagem adotada para as redes IP onde assenta a Internet (e a maior parte das redes de menor dimensão), foi totalmente oposta. Ou seja, na Internet, as funcionalidades passaram da rede em si para o software existente no dispositivo - portátil, telefone, servidor, dispositivo IoT, etc.. 

Nesta abordagem, os dispositivos não assumem nada sobre as capacidades das redes que usam. Apenas confiam que a rede é capaz de entregar pacotes a um endereço de destino. Não podem assumir que todos os pacotes vão mesmo ser entregues com sucesso, ou seque se serão informados caso algum pacote não chegue ao destino, nada. Mesmo que todos os pacotes sejam entregues ao destino, não é possível garantir que são entregues de forma ordenada respeitando a sequªência de envio.

Um dispositivo não pode assumir a taxa de transferência, largura de banda, atraso ou necessidade de retransmissão.

As redes IP foram contruídas para funcionar em qualquer condição, interligando outras redes com capacidades distintas e por isto, sem garantias de serviço.
As capacidades deixaram de estar na rede e passaram para os dispositivos nas extremidades, que têm agora a respnsabilidade de garantir que os pacotes seguem até ao destino e este, por sua vez, os agrega novamente, na sequência indicada pelo remetente, que espera por pacotes que tenha seguido uma caminho mais demorado, pedir a retransmissão de pacotes que não tenham segado ao destino, etc..

_________________________________________________________________________________________________

A maior parte desta rica funcionalidade pode ser encontrada no protocolo TCP, o protocolo utilizado para suportar a transferência fiável de dados de ponta a ponta. Este protocolo é o porta-estandarte da maioria das redes da Internet, suportando o funcionamento da World Wide Web, o correio electrónico e a transferência de filtros. A abordagem básica utilizada pelo TCP é a do reconhecimento positivo, onde um remetente só pode considerar que um pacote foi entregue com sucesso quando recebe uma confirmação da extremidade remota que sinaliza a recepção do pacote enviado anteriormente. Além disso, o TCP é um protocolo adaptativo de taxa, em vez de um protocolo de taxa constante. Isto implica que uma transferência TCP tentará aumentar a sua taxa de transferência de dados enquanto a rede for capaz de entregar com sucesso todos os pacotes, assumindo que tanto o emissor como o recetor podem suportar a taxa aumentada. O TCP interpreta a perda de pacotes como um sinal de congestionamento da rede e reage ao congestionamento da rede reduzindo a sua taxa de envio. Os protocolos adaptativos de taxa podem fazer uma utilização muito eficiente da rede, permitindo que os sistemas finais aumentem as suas taxas de dados enquanto existe capacidade de rede disponível e reduzindo drasticamente as taxas de dados face ao congestionamento de rede observado. Isto funciona se o protocolo estiver a funcionar numa LAN de alta largura de banda e baixa latência ou se o protocolo estiver a funcionar num circuito de satélite de baixa largura de banda e alta latência. A pilha de protocolos TCP tentará otimizar a utilização do sistema de comunicações subjacente, independentemente das características específicas desse sistema.

Do ponto de vista da rede, os protocolos adaptativos de taxa são os que mais eliminam a capacidade da rede, o que resulta em redes muito eficientes e de baixo custo. Se a capacidade de rede disponível for considerada como um custo comercial e o tráfego da Internet como receita, a tarifa adaptativa




____________________________________________________________________________________________________

Jean shorts raw denim Vice normcore, art party High Life PBR skateboard stumptown vinyl kitsch. Four loko meh 8-bit, tousled banh mi tilde forage Schlitz dreamcatcher twee 3 wolf moon. Chambray asymmetrical paleo salvia, sartorial umami four loko master cleanse drinking vinegar brunch. [Pinterest](https://www.pinterest.com) DIY authentic Schlitz, hoodie Intelligentsia butcher trust fund brunch shabby chic Kickstarter forage flexitarian. Direct trade <a href="https://en.wikipedia.org/wiki/Cold-pressed_juice">cold-pressed</a> meggings stumptown plaid, pop-up taxidermy. Hoodie XOXO fingerstache scenester Echo Park. Plaid ugh Wes Anderson, freegan pug selvage fanny pack leggings pickled food truck DIY irony Banksy.

#### Hipster list

- brunch
- fixie
- raybans
- messenger bag

#### Check List

- [x] Brush Teeth
- [ ] Put on socks
  - [x] Put on left sock
  - [ ] Put on right sock
- [x] Go to school

Hoodie Thundercats retro, tote bag 8-bit Godard craft beer gastropub. Truffaut Tumblr taxidermy, raw denim Kickstarter sartorial dreamcatcher. Quinoa chambray slow-carb salvia readymade, bicycle rights 90's yr typewriter selfies letterpress cardigan vegan.

<hr>

Pug heirloom High Life vinyl swag, single-origin coffee four dollar toast taxidermy reprehenderit fap distillery master cleanse locavore. Est anim sapiente leggings Brooklyn ea. Thundercats locavore excepteur veniam eiusmod. Raw denim Truffaut Schlitz, migas sapiente Portland VHS twee Bushwick Marfa typewriter retro id keytar.

> We do not grow absolutely, chronologically. We grow sometimes in one dimension, and not in another, unevenly. We grow partially. We are relative. We are mature in one realm, childish in another.
> —Anais Nin

Fap aliqua qui, scenester pug Echo Park polaroid irony shabby chic ex cardigan church-key Odd Future accusamus. Blog stumptown sartorial squid, gastropub duis aesthetic Truffaut vero. Pinterest tilde twee, odio mumblecore jean shorts lumbersexual.
