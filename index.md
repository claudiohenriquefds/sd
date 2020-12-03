# Sistemas Distribuidos - Pesquisa sobre Sistemas operacionais

## Cláudio Henrique Ferreira da Silva - 4ADS


### Sistema Operacional Centralizado

Um sistema de operacional centralizado (SOC) é aquele executado em uma coleção de máquinas, que se utiliza de seus recursos individuais e possui uma máquina servidora que centraliza todas as informações. São sistemas que possuem pouco poder de processamento sequencial (tempo compartilhado) e necessitam de um mainframe para que possa funcionar com qualidade. Porém, por maior que seja a velocidade de processamento de um mainframe, ele jamais conseguirá alcançar o poder de processamento de vários microcomputadores interligados, como se fosse um único sistema.

**Algumas caracteristicas:**
- Existem três modelos de sistemas centralizados: Monousuário, Cliente-servidor (duas camadas) e Multicamadas.
- São utilizadas as máquinas clientes com pouca capacidade e um servidor robusto.
- Um sistema centralizado não há necessidade de um diretório distribuído.

![Image](https://github.com/claudiohenriquefds/chfs/blob/master/src/assets/1.jpeg?raw=true)

[Referencia](https://www.infoescola.com/informatica/sistema-de-informacao-centralizado/)

### Sistema Operacional De Rede

Um Sistema Operacional de Redes é um conjunto de módulos que amplíam os sistemas operacionais, complementando-os com um conjunto de funções básicas, e de uso geral, que tornam transparente o uso de recursos compartilhados da rede

**Algumas caracteristicas:**
- Portes diversos
- Sistemas operacionais diversos
- Redes diversas
- Compartilhamento de arquivos e impressoras
- Servidores: Servidor de Arquivos, Servidor de Banco de Dados, Servidor de Impressão, Servidor de Comunicação, Servidor de Gerenciamento.

![Image](https://github.com/claudiohenriquefds/chfs/blob/master/src/assets/2.jpeg?raw=true)

[Referencia](http://rrbrandt.dee.ufcg.edu.br/br/docs/redes/sor)

### Sistema Operacional Distribuido

Um sistema distribuído é um conjunto de computadores independentes entre si que se apresenta a seus usuários como um sistema único e coerente, com base nessa afirmação podemos considerar que um sistema distribuído é uma colação de computadores e softwares interconectados por uma rede, projetados para resultar em uma aplicação integrada.

**Tipos de transferencia:**
- Transparência de Acesso
- Transparência de Localização
- Transparência de Migração
- Transparência de Relocação
- Transparência de Replicação
- Transparência de Concorrência
- Transparência de falhas

**Abertura:**
- É a característica que determina se um sistema pode ser ampliado de formas diferentes, com relação a hardware, onde podem ser incluídos dispositivos de fabricação diversa, e software, inclusão de modulo do sistema operacional, adição de protocolos de comunicação e compartilhamento de recursos. A interoperabilidade é a forma de garantir que duas ou mais implementações de sistemas ou componentes de fornecedores diferentes trabalhem de forma conjunta.

**Portabilidade:**
- Também é uma característica da abertura, a portabilidade é a maneira de garantir que um sistema funcione em um outro sistema sem a mesma interfaces e equipamentos do sistema de origem. É muito importante para esta característica é a padronização dos serviços.

**Escalabilidade:**
- Podemos afirmar que os sistemas são classificados de 3 formas com relação a escalabilidade, por tamanho, em termos geográficos e termos administrativos. O aumento do tamanho dos sistemas faz com que o problemas também aumente, podemos conceituar o tamanho como serviços centralizados, onde um servidor único é usado por todos os usuários, pode gerar um gargalo no sistema.

![Image](https://github.com/claudiohenriquefds/chfs/blob/master/src/assets/3.jpeg?raw=true)

[Referencia](https://tecnologia.culturamix.com/dicas/o-que-e-um-sistema-distribuido)

### Sistema Operacional Paralelo

“O principal propósito de processamento paralelo é realizar computação mais rápida do que pode ser feita com um único processador, usando mais do que um processadores concorrentes” (JaJa, 1992) O processamento paralelo pode ser definido como “uma forma eficiente de processamento da informação com ênfase na exploração de eventos concorrentes no processo computacional” Hwang PROGRAMAÇÃO PARALELA “Programação paralela implica em dividir problemas em partes nas quais processadores realizam a computação.” (WILKINSON e ALLEN, 1999)

**Algumas caracteristicas:**
- Sistemas com mais do que uma unidade de processamento.
- Unidades trabalham em paralelo para resolver um problema.
- Maquinas paralelas caracterizam-se por custo elevado e/ou dificuldade de programação.
- Custo pode ser diminuído a partir do entendimento das alternativas de construção de máquinas paralelas, possibilitando uma arquitetura mais acessível que obtenha o desempenho desejado.
- Necessidade de conhecimento de características específicas da máquina para a qual serão implementados as aplicações paralelas aumentam a complexidade no desenvolvimento de programas.

![Image](https://github.com/claudiohenriquefds/chfs/blob/master/src/assets/4.jpeg?raw=true)
