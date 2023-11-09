# Arquitetura de Computadores - Ficha 1

## Informação do aluno

    Nome: Tomás Ferreira

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### P1. Identifica e descreve os principais componentes de um processador. Fornece uma breve explicação da função de cada componente

- Lista os componentes principais de um processador.
- Para cada componente, descreve o seu papel e função no processador.
- Considera componentes como unidade lógica aritmética (ALU), unidade de controlo (UC), registos internos, memória e interfaces de entrada/saída (I/O).

P1 - Resposta:

    Unidade de Controle (UC): Responsável por coordenar as operações do processador, controlando a execução das instruções.
    Unidade Lógica e Aritmética (ULA): Executa operações aritméticas (como adição e subtração) e operações lógicas (como AND, OR e NOT).
    Registradores: Pequenas áreas de armazenamento de alta velocidade que mantêm dados temporários e resultados de operações.
    Unidade de Gerenciamento de Memória (UMM): Gerencia o acesso à memória, garantindo que os dados necessários estejam disponíveis para as operações.
    Unidade de Ponto Flutuante (FPU): Responsável por executar operações que envolvem números de ponto flutuante, comumente encontrados em cálculos científicos e gráficos.
    Cache: Memória de acesso rápido que armazena dados frequentemente usados para reduzir o tempo de acesso à memória principal.
    Barramento: Viabiliza a comunicação entre diferentes partes do processador e outros componentes do computador, como a memória RAM.

### P2. Compara as arquiteturas de Von Neumann e Harvard em termos de características e principais diferenças

- Lista as principais características da arquitetura Von Neumann.
- Lista as principais características da arquitetura de Harvard.
- Explica as principais diferenças entre as duas arquiteturas, particularmente na organização da memória, busca de instruções e separação de dados.
- Fornece exemplos de sistemas de computação que usam cada arquitetura.

P2 - Resposta:

    A arquitetura de Von Neumann, fundamental para computadores modernos, tem como características principais a presença de uma CPU, memória única para dados e instruções, registradores para armazenamento temporário, unidade de controle para gerenciar operações, barramento para comunicação, execução sequencial de instruções e a ideia de programas armazenados na memória. 
    Essa arquitetura oferece uma base eficiente para a execução de programas em computadores. Na arquitetura de Harvard, as memórias para dados e instruções são separadas, com barramentos independentes, permitindo acesso simultâneo e potencial aumento de desempenho. Essa arquitetura é eficiente para programação paralela, mas pode ser mais complexa que a arquitetura de Von Neumann É comumente usada em sistemas embarcados e microcontroladores.
    A principal diferença entre as arquiteturas de Von Neumann e Harvard está na organização da memória e na busca de instruções. Von Neumann utiliza uma única memória para dados e instruções, enquanto Harvard possui memórias separadas. Na busca de instruções, Von Neumann é sequencial, enquanto Harvard permite busca simultânea de dados e instruções. 
    A separação de dados na arquitetura de Harvard é mais eficiente, resultando em um potencial aumento de desempenho, especialmente em sistemas embarcados. Sistemas de computação baseados na arquitetura de Von Neumann incluem computadores pessoais e servidores convencionais, enquanto a arquitetura de Harvard é comumente encontrada em microcontroladores, processadores de sinal digital (DSPs) e sistemas embarcados específicos, como roteadores. Cada arquitetura é escolhida com base nas necessidades específicas de desempenho e aplicação do sistema.

### P3. Descreve o ciclo *fetch-decode-execute* num processador, detalhando cada etapa e explicando a sua importância na execução de programas de computador

- Fornece uma explicação detalhada da fase de busca de instrução, incluindo o que ela envolve e por que é importante na operação do processador.
- Explica a fase de descodificação e o seu papel na interpretação das instruções de execução.
- Descreve a fase de execução, destacando a execução propriamente dita das instruções e quaisquer interações com dados.
- Conclui explicando a ordem destas fases e como elas garantem a execução adequada dos programas de computador.
- Usa um diagrama para ilustrar o ciclo.

P3 - Resposta:

    A fase de busca de instrução é crucial no ciclo de execução do processador. Envolve o acesso à memória para buscar a próxima instrução com base no endereço armazenado no Contador de Programa (PC). A instrução é lida, transferida para a CPU e, após a execução, o PC é incrementado para apontar para a próxima instrução. Essa fase é fundamental para a execução sequencial e eficiente de programas, garantindo controle adequado do fluxo do programa e otimizando o desempenho ao buscar instruções enquanto executa outras.
    A fase de decodificação é essencial no ciclo de execução do processador. Nessa etapa, a CPU interpreta a instrução, reconhecendo seu tipo, identificando operandos e configurando unidades internas. Isso traduz a instrução em ações concretas, preparando a CPU para a execução na próxima fase. A decodificação coordena diferentes partes do ciclo, garantindo a interpretação correta do programa e a execução eficiente das operações.
    Na fase de execução, a CPU realiza efetivamente as operações indicadas pelas instruções. Isso envolve a manipulação de dados, acesso a operandos, atualização de registradores e memória, e, em alguns casos, a transferência de controle do programa. Durante essa fase, a CPU executa as operações específicas, influenciando o estado interno e avançando a progressão do programa.A ordem sequencial das fases - busca de instrução, decodificação e execução - é essencial para a execução adequada de programas de computador. A CPU busca a próxima instrução, a interpreta durante a decodificação, executa a operação indicada e repete o ciclo. O Contador de Programa guia a ordem das instruções, assegurando uma execução precisa e sequencial do programa armazenado na memória. Essa coordenação eficiente garante a interpretação correta das instruções e a realização adequada das operações especificadas no programa.


![diagrama fetch](https://i.ytimg.com/vi/xs5oq-i_rTc/maxresdefault.jpg)















