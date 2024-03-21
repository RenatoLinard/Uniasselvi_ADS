# Introdução

Nesta unidade, será apresentada a arquitetura básica de um computador e como a matemática binária está 
presente no computador e em seus circuitos digitais. Além disso, será abordado o conhecimento sobre portas 
lógicas e expressões booleanas.

# Tópico 1

## Arquitetura Básica de um Computador

Um computador é uma máquina complexa composta por partes eletrônicas e eletromecânicas, como memória, 
processador, discos rígidos e drives de CD, capaz de coletar, armazenar e manipular dados automaticamente. 
Funciona por meio de um sistema digital programável, executando instruções armazenadas em memória para 
realizar diversas operações e fornecer resultados aos humanos.

Os chips, também conhecidos como Circuitos Integrados (CIs) ou microchips, são circuitos eletrônicos 
compostos por milhares de transistores, formados por processos químicos controlados, garantindo alta 
resistência mecânica e confiabilidade.

Os programas, armazenados em formato binário na memória, são conjuntos de instruções que permitem ao 
computador executar tarefas em áreas como científica, comercial, de simulação e controle de processos.

Os computadores se destacam por sua alta velocidade, grande capacidade de armazenamento, capacidade de 
trabalho contínuo e execução de longas sequências de operações. Suas vantagens incluem processamento rápido 
de grandes quantidades de dados, execução de tarefas repetitivas e cálculos precisos, mas apresentam 
limitações como falta de criatividade, dificuldade na interpretação da voz humana e alto custo.

Apesar das desvantagens, o uso generalizado de computadores é indispensável em áreas como comércio, 
finanças, saúde e outros setores. Compreender sua arquitetura e funcionamento é fundamental, especialmente 
para profissionais de informática, garantindo sua eficiência e utilidade nos mais diversos contextos.

## Elementos Básicos da Arquitetura Computacional

Apesar da existência de uma grande diversidade em termos de arquiteturas, pode-se enumerar, num ponto de 
vista mais genérico, os componentes básicos da arquitetura computacional atual. Por esse motivo, até hoje 
essa arquitetura é conhecida como Arquitetura de Von Neumann.

- **CPU (Unidade Central de Processamento):** Responsável pelo processamento das informações armazenadas 
em memória, executando programas em código de máquina e manipulando dados.
- **Memória:** Responsável pelo armazenamento de programas e dados que serão processados pela CPU.
- **Dispositivos de Entrada e Saída (I/O):** Permitem a interação entre o computador e o mundo externo, 
possibilitando entrada e saída de dados. Exemplos incluem monitor, teclado, mouse e impressora.
- **Barramentos:** Conectam todos os componentes e são vias de comunicação de alto desempenho, permitindo 
o tráfego de dados entre eles. Dividem-se em barramentos de dados, controles e endereços.

Os usuários fornecem dados por meio de dispositivos de entrada, como teclado e mouse. Esses dados são 
processados pela CPU, que os busca na memória, executa as operações necessárias e envia os resultados para 
dispositivos de saída, como um monitor de vídeo, através dos barramentos apropriados. Esses componentes e 
a comunicação entre eles são essenciais para o funcionamento do computador conforme a arquitetura de Von Neumann.

## CPU

A Unidade Central de Processamento (CPU) é o componente central da arquitetura computacional, responsável 
por executar programas e controlar todos os dispositivos do computador. Trata-se de um circuito integrado 
que busca dados na memória, realiza procedimentos com esses dados e retorna os resultados para o usuário. 
Conhecida por siglas como CPU em inglês (Central Processing Unit) ou UCP em português (Unidade Central de 
Processamento), desempenha um papel fundamental na operação e funcionamento de um sistema computacional.

O processador é um componente vital do computador, evoluindo de múltiplos chips para um único 
microprocessador, permitindo a construção de computadores em uma única placa, conhecida como placa-mãe. 
Internamente, o processador é dividido em unidades funcionais:

1. Unidade de Controle: Analisa e controla as instruções do programa, gerenciando a memória, ativando 
operações aritméticas e lógicas, e coordenando dispositivos de entrada/saída.
2. Memória Cache: Armazena dados para processamento. Inicialmente na placa-mãe, agora integrada ao CPU para 
melhor desempenho.
3. Registradores: Memória crucial na CPU, contendo instruções em execução.
4. Unidade Aritmética e Lógica: Realiza operações matemáticas e lógicas.

Essas unidades executam as atividades essenciais do ciclo de busca e execução:

1. Buscar instrução na memória e carregá-la na CPU;
2. Controlar o processo de busca e execução;
3. Executar as instruções;
4. Retornar resultados à memória principal.

Essas operações envolvem dados e dispositivos externos à CPU, representados pelos demais elementos da 
arquitetura de Von Neumann.

## Memória

A memória é um componente essencial em qualquer computador, classificada em diferentes tipos:

### Memória Principal:

Também chamada de memória de trabalho, é onde os programas e dados manipulados pelo processador são 
normalmente armazenados. Quantidades usuais de memória incluem 6GB, 4GB, 2GB e 1GB, referenciadas em 
microcomputadores. Consiste em chips inseridos na placa-mãe.

### Memória Secundária:

Não acessada diretamente pela CPU, é permanente e de alta capacidade. Armazena dados a um custo mais baixo. 
Exemplos incluem disco rígido, BluRay, DVD, CD-ROM, disquetes, fitas magnéticas e memórias flash.

### Memória Cache:

Pequena e rápida, geralmente localizada dentro dos processadores. Transfere dados da memória principal 
para o núcleo do processador mais rapidamente. Dividida em três níveis (L1, L2 e, se presente, L3), sendo 
mais cara quanto maior sua capacidade.

### Registradores:

Memórias de menor capacidade dentro do núcleo do processador, essenciais para a execução de instruções.

## Barramentos

Os barramentos, também

 conhecidos como BUS, são caminhos pelos quais os dados viajam dentro do computador, permitindo a comunicação 
 entre os componentes. São linhas condutoras de eletricidade utilizadas para transferir informações da CPU 
 aos periféricos e vice-versa. O tamanho de um barramento determina a quantidade de dados transmitidos de 
 uma só vez, por exemplo, um barramento de 16 bits transmite 16 bits de dados de uma vez.

Todo barramento consiste em três partes: barramento de endereçamento, barramento de dados e barramento de 
controle. O barramento de dados transmite os dados propriamente ditos, o barramento de endereço transmite 
informações sobre onde os dados estão localizados na memória e o barramento de controle mantém a sincronização 
e gerencia o uso dos canais pelos dispositivos compartilhados.

Existem dois tipos principais de barramentos:

1. Barramentos Internos: Ligam a CPU diretamente aos periféricos. Exemplos incluem IDE, ISA, PCI, AGP e SCSI.

2. Barramentos Externos: Conectam os periféricos à placa-mãe. Exemplos são PS/2, Serial, Paralela, USB, Firewire e PCMCIA.

## Unidades de Entrada e Saída (Periféricos)

Os Dispositivos de Entrada/Saída, também conhecidos como periféricos, são utilizados como meios para o 
computador interagir com o ambiente externo e processar informações. Por exemplo, ao pressionar uma tecla, 
o teclado transmite o código correspondente à tecla pressionada através de uma interface específica. 
Quando a CPU necessita exibir informações para o usuário, utiliza uma interface de vídeo para enviar 
mensagens para o monitor, seja em forma de texto ou imagem.

Esses dispositivos de Entrada/Saída permitem ao computador armazenar, ler, transmitir e receber dados. 
Existem periféricos especializados em entrada, como teclados e scanners, outros especializados em saída, 
como monitores e impressoras, e ainda aqueles que realizam tanto entrada quanto saída, como discos rígidos 
e unidades de CD/DVD.
