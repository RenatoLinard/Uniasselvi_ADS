# Introdução

Nesta unidade, será mostrada a arquitetura básica de um computador e como a matemática binária está 
presente no computador e em seus circuitos digitais. Além disso, será abordado o conhecimento sobre portas lógicas e expressões booleanas.

# Tópico 1

## ARQUITETURA BÁSICA DE UM COMPUTADOR

Um computador é uma máquina complexa composta por partes eletrônicas e eletromecânicas, como memória, processador, hard drives e drives de CD, capaz de coletar, armazenar e manipular dados automaticamente. Funciona por meio de um sistema digital programável, executando instruções armazenadas em memória para realizar diversas operações e fornecer resultados aos humanos.

Os chips, também conhecidos como Circuitos Integrados (CIs) ou microchips, são circuitos eletrônicos compostos por milhares de transistores, formados por processos químicos controlados, garantindo alta resistência mecânica e confiabilidade.

Os programas, armazenados em formato binário na memória, são conjuntos de instruções que permitem ao computador executar tarefas em áreas como científica, comercial, de simulação e controle de processos.

Os computadores se destacam por sua alta velocidade, grande capacidade de armazenamento, capacidade de trabalho contínuo e execução de longas sequências de operações. Suas vantagens incluem processamento rápido de grandes quantidades de dados, execução de tarefas repetitivas e cálculos precisos, mas apresentam limitações como falta de criatividade, dificuldade na interpretação da voz humana e alto custo.

Apesar das desvantagens, o uso generalizado de computadores é indispensável em áreas como comércio, finanças, saúde e outros setores. Compreender sua arquitetura e funcionamento é fundamental, especialmente para profissionais de informática, garantindo sua eficiência e utilidade nos mais diversos contextos.

## ELEMENTOS BÁSICOS DA ARQUITETURA COMPUTACIONAL

Apesar da existência de uma grande diversidade em termos de arquiteturas, pode-se enumerar, num ponto de vista mais genérico, os componentes básicos da arquitetura computacional atual. Por esse motivo, até hoje essa arquitetura é conhecida como Arquitetura de Von Neumann.

- **CPU (Unidade Central de Processamento):** Responsável pelo processamento das informações armazenadas em memória, executando programas em código de máquina e manipulando dados.

- **Memória:** Responsável pelo armazenamento de programas e dados que serão processados pela CPU.

- **Dispositivos de Entrada e Saída (I/O):** Permitem a interação entre o computador e o mundo externo, possibilitando entrada e saída de dados. Exemplos incluem monitor, teclado, mouse e impressora.

- **Barramentos:** Conectam todos os componentes e são vias de comunicação de alto desempenho, permitindo o tráfego de dados entre eles. Dividem-se em barramentos de dados, controles e endereços.

Os usuários fornecem dados por meio de dispositivos de entrada, como teclado e mouse. Esses dados são processados pela CPU, que os busca na memória, executa as operações necessárias e envia os resultados para dispositivos de saída, como um monitor de vídeo, através dos barramentos apropriados. Esses componentes e a comunicação entre eles são essenciais para o funcionamento do computador conforme a arquitetura de Von Neumann.

## CPU

A Unidade Central de Processamento (CPU) é o componente central da arquitetura computacional, responsável por executar programas e controlar todos os dispositivos do computador. Trata-se de um circuito integrado que busca dados na memória, realiza procedimentos com esses dados e retorna os resultados para o usuário. Conhecida por siglas como CPU em inglês (Central Processing Unit) ou UCP em português (Unidade Central de Processamento), desempenha um papel fundamental na operação e funcionamento de um sistema computacional.o

O processador é um componente vital do computador, evoluindo de múltiplos chips para um único microprocessador, permitindo a construção de computadores em uma única placa, conhecida como placa-mãe. Internamente, o processador é dividido em unidades funcionais:

1. Unidade de Controle: Analisa e controla as instruções do programa, gerenciando a memória, ativando operações aritméticas e lógicas, e coordenando dispositivos de entrada/saída.

2. Memória Cache: Armazena dados para processamento. Inicialmente na placa-mãe, agora integrada ao CPU para melhor desempenho.

3. Registradores: Memória crucial na CPU, contendo instruções em execução.

4. Unidade Aritmética e Lógica: Realiza operações matemáticas e lógicas.

Essas unidades executam as atividades essenciais do ciclo de busca e execução:

1. Buscar instrução na memória e carregá-la na CPU;
2. Controlar o processo de busca e execução;
3. Executar as instruções;
4. Retornar resultados à memória principal.

Essas operações envolvem dados e dispositivos externos à CPU, representados pelos demais elementos da arquitetura de Von Neumann.