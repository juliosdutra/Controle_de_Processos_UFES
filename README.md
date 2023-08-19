# Controle de Processos (em desenvolvimento)

Conteúdo produzido pelo Prof. Julio Cesar Sampaio Dutra para auxiliar na disciplina de Controle de Processos ministrada para o curso de Engenharia Química da Universidade Federal do Espírito Santo (UFES).

Com o objetivo de aplicar os conceitos da disciplina de Controle de Processos, é proposta a realização de uma série de atividades aplicadas a exemplos da Engenharia Química ou de áreas afins. Isto é feito no intuito de desenvolver habilidades computacionais essenciais para o uso de software de computador para ajudar a descrever e projetar sistemas de controle, importantes também para as áreas de modelagem e simulação.

A partir da literatura, será selecionado um exemplo com modelagem matemática fenomenológica com dinâmica no tempo, bem como o conjunto de parâmetros necessários para a simulação. Para não elevar a complexidade de implementação computacional dos modelos, será escolhido um modelo com parâmetros concentrados.


** Serão trabalhadas as seguintes atividades: **

** 1. Implementação de modelo matemático ** <br>
- Linearização do modelo não lineares
- Obtenção de funções de transferência
-	Análise do processo (ordem, polos, zeros, ...)
-	Projeto de controladores e sintonia
- Simulação computacional - em malha fechada, com testes regulador e servo

Esses conteúdos serão desenvolvidos em Python. Esta linguagem de programação ganhou notoriedade na área de Ciência de Dados, mas também tem tido preferência como plataforma de solução de problemas de engenharia. Existem diversas opções de ambientes para desenvolvimento em Python, sendo que a plataforma mais popular hoje é a Anaconda. Ela contém ferramentas importantes como o Spyder (que é um ambiente para programar em Python), além de um conjunto enorme de pacotes populares já instalados (numpy, scipy, matlibplot, etc). Por isso, é necessário que os alunos façam o download da plataforma Anaconda em seus computadores a partir do site www.anaconda.com/, e procedam a instalação que é muito simples. 

# Requirementos
- numpy
- scipy
- matplotlib 
- python-control

# Referências Bibliográficas
- BEQUETTE, B. W., 2003, Process Control, Modeling, Design and Simulation, Prentice-Hall.
- LUYBEN, W.L., 1990, Process modeling, simulation, and control for chemical engineers, 2nd Edition. McGraw-Hill.
- SEBORG, D.E., EDGAR, T.F., MELLICHAMP, D.A., 2011, Process Dynamics and Control, 3rd Edition. John Wiley & Sons.
