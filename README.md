# Controle de Processos (em desenvolvimento)

Conteúdo produzido pelo Prof. Julio Cesar Sampaio Dutra para auxiliar na disciplina de Controle de Processos ministrada para o curso de Engenharia Química da Universidade Federal do Espírito Santo (UFES).

Com o objetivo de aplicar os conceitos da disciplina de Controle de Processos, é proposta a realização de uma série de atividades aplicadas a exemplos da Engenharia Química ou de áreas afins. Isto é feito no intuito de desenvolver habilidades computacionais essenciais para o uso de software de computador para ajudar a descrever e projetar sistemas de controle, importantes também para as áreas de modelagem e simulação.

A partir da literatura, será selecionado um exemplo com modelagem matemática fenomenológica com dinâmica no tempo, bem como o conjunto de parâmetros necessários para a simulação. Para não elevar a complexidade de implementação computacional dos modelos, será escolhido um modelo com parâmetros concentrados.


**Serão trabalhadas as seguintes atividades:**

- Implementação de modelo matemático
- Linearização do modelo não lineares
- Obtenção de funções de transferência
-	Análise do processo (ordem, polos, zeros, ...)
-	Projeto de controladores e sintonia
- Simulação computacional - em malha fechada, com testes regulador e servo

Esses conteúdos serão desenvolvidos em Python, uma linguagem de programação que conquistou reconhecimento tanto na área de Ciência de Dados quanto como plataforma preferencial para solução de problemas de engenharia. Para trabalhar com Python, você dispõe de uma variedade de ambientes de desenvolvimento, e um dos mais populares hoje em dia é a Anaconda. Além disso, outra opção amplamente utilizada é o Google Colab, uma plataforma baseada em nuvem que oferece um ambiente integrado para escrever e executar código Python.

A Anaconda, por exemplo, disponibiliza ferramentas essenciais, incluindo o Spyder, um ambiente de programação dedicado ao Python, e já inclui uma ampla gama de pacotes populares preinstalados, como numpy, scipy, matplotlib, entre outros. Para aproveitar essas vantagens, é recomendado que os alunos realizem o download da plataforma Anaconda por meio do site www.anaconda.com/ e sigam o processo de instalação, que é bastante simples.

Além disso, o Google Colab oferece uma abordagem diferente ao desenvolvimento em Python, pois é uma plataforma baseada em nuvem que elimina a necessidade de configurações locais. Você pode acessar o Colab diretamente pelo navegador, o que facilita o compartilhamento de projetos e colaborações em equipe. Ele também já possui muitos pacotes comuns pré-instalados e oferece recursos de aceleração por hardware, como GPUs, para acelerar a execução de código intensivo computacionalmente.

Portanto, tanto a Anaconda quanto o Google Colab são opções valiosas para iniciar sua jornada de programação em Python, cada uma com suas próprias vantagens. A escolha entre essas plataformas dependerá das suas necessidades e preferências individuais.

# Requirementos
- numpy
- scipy
- matplotlib 
- python-control

# Referências Bibliográficas
- BEQUETTE, B. W., 2003, Process Control, Modeling, Design and Simulation, Prentice-Hall.
- LUYBEN, W.L., 1990, Process modeling, simulation, and control for chemical engineers, 2nd Edition. McGraw-Hill.
- SEBORG, D.E., EDGAR, T.F., MELLICHAMP, D.A., 2011, Process Dynamics and Control, 3rd Edition. John Wiley & Sons.
