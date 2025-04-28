# Aprender Python
## 1.Fundamentos da Linguagem Python

Tópicos fundamentais da linguagem Python e uma breve descrição de cada um:

### Top Level Categories:

#### 1. Operadores

* **Descrição:** Símbolos especiais em Python que realizam operações em valores (operandos). Incluem operadores aritméticos (`+`, `-`, `*`, `/`, `//`, `%`, `**`), de comparação (`==`, `!=`, `>`, `<`, `>=`, `<=`), lógicos (`and`, `or`, `not`), de atribuição (`=`, `+=`, `-=`, etc.), de identidade (`is`, `is not`), e de membro (`in`, `not in`).

#### 2. Variáveis

* **Descrição:** Nomes simbólicos usados para armazenar valores na memória do computador. Em Python, a tipagem é dinâmica, o que significa que você não precisa declarar o tipo de uma variável explicitamente. O tipo é inferido com base no valor atribuído.

#### 3. Tuplas

* **Descrição:** Sequências ordenadas e imutáveis de itens. São definidas usando parênteses `()` e os itens são separados por vírgulas. Uma vez criada, uma tupla não pode ser modificada (adição, remoção ou alteração de elementos).

#### 4. Conjuntos (Sets)

* **Descrição:** Coleções não ordenadas de elementos únicos. São definidos usando chaves `{}` ou a função `set()`. Conjuntos são úteis para realizar operações matemáticas como união, interseção e diferença.

#### 5. Condições

* **Descrição:** Estruturas de controle de fluxo que permitem executar diferentes blocos de código com base na avaliação de uma expressão booleana (verdadeira ou falsa). As principais estruturas condicionais em Python são `if`, `elif` (else if), e `else`.

#### 6. Funções

* **Descrição:** Blocos de código reutilizáveis que realizam uma tarefa específica. Funções ajudam a organizar o código, torná-lo mais legível e evitar repetições. São definidas usando a palavra-chave `def`, seguida pelo nome da função, parênteses para argumentos (opcionais) e dois pontos `:`.

#### 7. Manipulação de arquivos

* **Descrição:** Refere-se às operações de leitura e escrita de dados em arquivos armazenados no sistema. Python fornece funções embutidas como `open()` para abrir arquivos em diferentes modos (`'r'` para leitura, `'w'` para escrita, `'a'` para anexar, etc.) e métodos para ler (`.read()`, `.readline()`, `.readlines()`) e escrever (`.write()`, `.writelines()`) dados.

#### 8. Erros e exceções

* **Descrição:** Situações inesperadas que ocorrem durante a execução de um programa. Python usa um mecanismo de tratamento de exceções (`try`, `except`, `finally`, `raise`) para lidar com esses erros de forma controlada, evitando que o programa termine abruptamente.

#### 9. Tipos de dados

* **Descrição:** Categorias de valores que uma variável pode armazenar. Os tipos de dados básicos em Python incluem:
    * **Numéricos:** `int` (inteiros), `float` (ponto flutuante), `complex` (números complexos).
    * **Sequenciais:** `str` (strings), `list` (listas), `tuple` (tuplas), `range` (sequência de números).
    * **Mapeamento:** `dict` (dicionários).
    * **Conjuntos:** `set` (conjuntos), `frozenset` (conjuntos imutáveis).
    * **Booleanos:** `bool` (`True` ou `False`).
    * **Binários:** `bytes`, `bytearray`, `memoryview`.

#### 10. Listas

* **Descrição:** Sequências ordenadas e mutáveis de itens. São definidas usando colchetes `[]` e os itens são separados por vírgulas. Listas são muito flexíveis e permitem adicionar, remover e modificar elementos.

#### 11. Dicionários

* **Descrição:** Coleções não ordenadas de pares chave-valor. São definidos usando chaves `{}` e cada item consiste em uma chave única seguida por dois pontos `:` e o valor correspondente. Dicionários são úteis para armazenar e acessar dados de forma eficiente usando chaves.

#### 12. Loops

* **Descrição:** Estruturas de controle de fluxo que permitem executar um bloco de código repetidamente. Os dois tipos principais de loops em Python são `for` (para iterar sobre uma sequência) e `while` (para executar enquanto uma condição for verdadeira).

#### 13. Entradas e saídas

* **Descrição:** Refere-se à forma como um programa interage com o mundo exterior. A entrada geralmente envolve receber dados do usuário (usando a função `input()`) ou de arquivos. A saída geralmente envolve exibir informações para o usuário (usando a função `print()`) ou escrever dados em arquivos.

#### 14. Classes

* **Descrição:** Modelos para criar objetos. A programação orientada a objetos (POO) em Python se baseia em classes. Uma classe define os atributos (dados) e métodos (funções) que os objetos dessa classe terão.

#### 15. Módulos e pacotes

* **Descrição:**
    * **Módulos:** Arquivos Python que contêm definições de funções, classes e variáveis. Permitem organizar o código em unidades lógicas e reutilizáveis. São importados usando a palavra-chave `import`.
    * **Pacotes:** Coleções de módulos relacionados organizados em uma estrutura de diretórios. Ajudam a gerenciar projetos maiores e evitar conflitos de nomes.

#### 16. Ambientes virtuais

* **Descrição:** Ferramentas que criam um ambiente isolado para projetos Python. Isso permite instalar dependências específicas para cada projeto sem interferir nas dependências de outros projetos ou na instalação global do Python. `venv` e `conda` são ferramentas comuns para criar ambientes virtuais.

## 2. Second Level Categories and Associated Libraries:

## 2.1 Análise de dados & IA (Data Analysis & AI)

Esta seção apresenta bibliotecas Python essenciais para análise de dados, aprendizado de máquina e inteligência artificial.

- **Numpy**
    - **Descrição:** Oferece suporte para arrays multidimensionais e diversas funções matemáticas para operar nesses arrays de forma eficiente.
    - **Instalação via pip:**
      ```bash
      pip install numpy
      ```

- **Pandas**
    - **Descrição:** Fornece estruturas de dados de alto nível (como DataFrames) e ferramentas para análise e manipulação de dados tabulares. Facilita a leitura, limpeza, transformação e análise de dados.
    - **Instalação via pip:**
      ```bash
      pip install pandas
      ```

- **Matplotlib**
    - **Descrição:** Biblioteca para criação de gráficos e visualizações de dados estáticas, interativas e animadas em Python. Oferece controle granular sobre todos os aspectos dos gráficos.
    - **Instalação via pip:**
      ```bash
      pip install matplotlib
      ```

- **Seaborn**
    - **Descrição:** Construída sobre o Matplotlib, oferece uma interface de alto nível para criar gráficos estatísticos informativos e atraentes. Simplifica a criação de visualizações complexas.
    - **Instalação via pip:**
      ```bash
      pip install seaborn
      ```

- **Scikit-learn**
    - **Descrição:** Biblioteca abrangente para aprendizado de máquina em Python. Contém algoritmos para classificação, regressão, agrupamento, seleção de modelos, pré-processamento e muito mais.
    - **Instalação via pip:**
      ```bash
      pip install scikit-learn
      ```

- **TensorFlow**
    - **Descrição:** Framework de código aberto desenvolvido pelo Google para computação numérica e aprendizado de máquina em larga escala. Amplamente utilizado para construir e treinar redes neurais profundas.
    - **Instalação via pip:**
      ```bash
      pip install tensorflow
      # Para usar a versão com suporte a GPU, instale tensorflow-gpu:
      # pip install tensorflow-gpu
      ```

- **Keras**
    - **Descrição:** API de alto nível para construir e treinar redes neurais. Pode rodar sobre TensorFlow, Theano ou CNTK. Simplifica o desenvolvimento de modelos de deep learning.
    - **Instalação via pip:**
      ```bash
      pip install keras
      ```

- **PyTorch**
    - **Descrição:** Outro framework de código aberto popular para aprendizado de máquina, especialmente para pesquisa e prototipagem rápida. Conhecido por sua flexibilidade e natureza dinâmica.
    - **Instalação via pip:**
      ```bash
      pip install torch torchvision torchaudio
      ```

- **Theano**
    - **Descrição:** Biblioteca Python que permite definir, otimizar e avaliar expressões matemáticas envolvendo arrays multidimensionais de forma eficiente. Foi um dos primeiros frameworks de deep learning. (Atualmente em modo de manutenção).
    - **Instalação via pip:**
      ```bash
      pip install theano
      ```

- **MxNet**
    - **Descrição:** Framework de aprendizado profundo de código aberto que oferece suporte a múltiplas linguagens de programação e é conhecido por sua escalabilidade e eficiência. Pode haver variações dependendo da sua configuração.
    - **Instalação via pip:**
      ```bash
      pip install mxnet
      ```

- **Caffe**
    - **Descrição:** Framework de aprendizado profundo desenvolvido pela Berkeley AI Research (BAIR). Conhecido por sua velocidade e arquitetura modular. A instalação do Caffe pode ser mais complexa e geralmente envolve compilação a partir do código fonte. Pode haver wrappers Python como `python-caffe` que podem ser instalados via pip, mas dependem da instalação do Caffe.
    - **Instalação via pip (wrapper):**
      ```bash
      pip install caffe # Pode instalar um wrapper, a instalação completa é mais complexa.
      ```

- **CNTK (Microsoft Cognitive Toolkit)**
    - **Descrição:** Framework de aprendizado profundo de código aberto da Microsoft. Oferece suporte a diversos tipos de redes neurais e é otimizado para desempenho. (Descontinuado pela Microsoft, com suporte encerrado em 2023).
    - **Instalação via pip:**
      ```bash
      pip install cntk
      ```

- **Pillow**
    - **Descrição:** Biblioteca para manipulação de imagens em Python. Permite abrir, manipular e salvar diversos formatos de imagem. Embora não seja estritamente de "IA", é frequentemente usado em tarefas de pré-processamento de imagens para modelos de aprendizado de máquina.
    - **Instalação via pip:**
      ```bash
      pip install Pillow
      ```

- **OpenCV (Open Source Computer Vision Library)**
    - **Descrição:** Biblioteca abrangente para visão computacional. Oferece ferramentas para processamento de imagens, análise de vídeo, detecção de objetos e muito mais, sendo fundamental em muitas aplicações de IA.
    - **Instalação via pip:**
      ```bash
      pip install opencv-python
      # Para a versão completa com módulos extras:
      # pip install opencv-contrib-python
      ```

- **ApacheSpark**
    - **Descrição:** Plataforma de computação distribuída de código aberto para processamento de grandes volumes de dados. Possui módulos para SQL, streaming, aprendizado de máquina (MLlib) e processamento de grafos, essencial para escalar tarefas de análise e IA. (Geralmente instalado em um ambiente de cluster, não apenas via pip para uso distribuído). PySpark fornece a API Python para usar o Spark. A instalação completa do Spark é um processo separado.
    - **Instalação via pip (PySpark API):**
      ```bash
      pip install pyspark
      ```

- **Hadoop**
    - **Descrição:** Framework de código aberto para armazenamento e processamento distribuído de grandes conjuntos de dados. Forma a base de muitos sistemas de big data utilizados em tarefas complexas de análise e IA. (Geralmente instalado em um ambiente de cluster, não apenas via pip). Não há uma instalação direta via pip para o Hadoop em si. Você pode instalar algumas bibliotecas relacionadas ao Hadoop para interação, como `hdfs`.
    - **Instalação via pip (bibliotecas de interação):**
      ```bash
      pip install hdfs
      ```

## 2.2 Desenvolvimento Web (Web Development)

Esta seção lista alguns dos principais frameworks Python utilizados para o desenvolvimento de aplicações web, desde microframeworks até soluções mais completas.

- **Django**
    - **Descrição:** Um framework web de alto nível, conhecido por sua abordagem "batteries-included". Oferece muitas funcionalidades prontas para uso, como um ORM (Object-Relational Mapper), sistema de templates, administração automática e segurança robusta. É ideal para projetos complexos e de grande escala.
    - **Instalação via pip:**
      ```bash
      pip install Django
      ```

- **Flask**
    - **Descrição:** Um microframework web leve e flexível. Oferece as ferramentas essenciais para construir aplicações web, deixando para o desenvolvedor a escolha de componentes adicionais como ORM e sistema de templates. É popular para projetos menores, APIs e quando se precisa de maior controle.
    - **Instalação via pip:**
      ```bash
      pip install Flask
      ```

- **CherryPy**
    - **Descrição:** Um framework web minimalista orientado a objetos. Permite aos desenvolvedores web construir aplicações da mesma forma que constroem qualquer outra aplicação Python orientada a objetos. É conhecido por sua simplicidade e facilidade de uso.
    - **Instalação via pip:**
      ```bash
      pip install CherryPy
      ```

- **Pyramid**
    - **Descrição:** Um framework web versátil e flexível, descrito como "começando pequeno e terminando grande". Ele permite que os desenvolvedores escolham os componentes que desejam usar e oferece um bom equilíbrio entre simplicidade e poder para projetos de todos os tamanhos.
    - **Instalação via pip:**
      ```bash
      pip install Pyramid
      ```

- **TurboGears**
    - **Descrição:** Um framework web full-stack que visa tornar o desenvolvimento web rápido e fácil. Ele combina o melhor de vários outros frameworks e ferramentas, como SQLAlchemy para ORM e Genshi para templates, seguindo uma filosofia de "melhores escolhas".
    - **Instalação via pip:**
      ```bash
      pip install TurboGears2
      ```

- **Web2Py**
    - **Descrição:** Um framework web full-stack de código aberto escrito em Python. É conhecido por sua facilidade de uso, segurança e por não requerer instalação para começar a desenvolver (possui um IDE web integrado).
    - **Instalação via pip:**
      ```bash
      pip install web2py
      ```

- **Bottle**
    - **Descrição:** Um microframework web simples e leve para Python. É distribuído como um único arquivo e não possui dependências além da biblioteca padrão do Python. É ideal para construir pequenas APIs, protótipos e aplicações web simples.
    - **Instalação via pip:**
      ```bash
      pip install bottle
      ```

- **Tornado**
    - **Descrição:** Um framework web assíncrono e biblioteca de rede. É especialmente adequado para lidar com muitas conexões simultâneas, tornando-o ideal para aplicações em tempo real, WebSockets e outras aplicações de rede de alto desempenho.
    - **Instalação via pip:**
      ```bash
      pip install tornado
      ```

- **Falcon**
    - **Descrição:** Um microframework de alto desempenho para construir APIs web e backends de aplicativos. Ele se concentra em ser rápido, confiável e escalável, com ênfase no tratamento eficiente de solicitações HTTP.
    - **Instalação via pip:**
      ```bash
      pip install falcon
      ```

## 2.3 Desenvolvimento App (App Development)

Esta seção apresenta bibliotecas e ferramentas Python utilizadas para o desenvolvimento de aplicativos móveis para diversas plataformas.

- **Kivy**
    - **Descrição:** Um framework Python de código aberto para o desenvolvimento de aplicativos com interfaces de usuário inovadoras, como aplicativos multi-touch. Ele roda em Linux, Windows, macOS, Android e iOS.
    - **Instalação via pip:**
      ```bash
      pip install kivy
      ```

- **BeeWare**
    - **Descrição:** Um conjunto de ferramentas que permite aos desenvolvedores escrever aplicativos nativos usando Python e implementá-los em várias plataformas de desktop e móveis (iOS, Android, macOS, Windows, Linux) a partir de uma única base de código.
    - **Instalação via pip:**
      ```bash
      pip install briefcase
      # Outras ferramentas do BeeWare podem ter instalações separadas. Consulte a documentação.
      ```

- **Python-for-Android**
    - **Descrição:** Uma ferramenta para empacotar aplicativos Python como arquivos APK para rodar em dispositivos Android. Permite escrever aplicativos Android em Python, utilizando frameworks como Kivy ou Pygame.
    - **Instalação:**
      ```bash
      # Python-for-Android geralmente requer um setup mais complexo.
      # Consulte a documentação oficial para as instruções de instalação detalhadas.
      # Geralmente envolve clonar o repositório e executar scripts.
      # Exemplo (pode variar):
      # git clone [https://github.com/kivy/python-for-android.git](https://github.com/kivy/python-for-android.git)
      # cd python-for-android
      # ./toolchain.py ...
      ```

- **Android**
    - **Descrição:** Refere-se ao ecossistema de desenvolvimento Android. Embora a linguagem nativa seja Java ou Kotlin, ferramentas como Kivy e Python-for-Android permitem o uso de Python para desenvolver aplicativos para esta plataforma.
    - **Instalação:** N/A (é uma plataforma de desenvolvimento, não uma biblioteca Python instalável via pip diretamente).

- **Pyjnius**
    - **Descrição:** Uma biblioteca Python que permite interagir com o código Java de dentro do Python. É útil para acessar APIs Android diretamente de aplicativos Python desenvolvidos com ferramentas como Kivy.
    - **Instalação via pip:**
      ```bash
      pip install pyjnius
      ```

## 2.4 Desenvolvimento Games (Games Development)

Esta seção destaca bibliotecas Python populares para a criação de jogos, desde jogos 2D simples até ambientes 3D.

- **Pygame**
    - **Descrição:** Um conjunto de módulos Python projetados para escrever videogames. Inclui funcionalidades para gráficos, som, entrada (teclado, mouse, joystick) e detecção de colisões. É amplamente utilizado para criar jogos 2D.
    - **Instalação via pip:**
      ```bash
      pip install pygame
      ```

- **PyKyra**
    - **Descrição:** Uma "fast 2D game development library" escrita em C++ e Python. Visa fornecer uma maneira fácil e rápida de criar jogos 2D com recursos como gerenciamento de cenas, animações e física básica. *(Projeto parece menos ativo atualmente)*
    - **Instalação via pip:**
      ```bash
      pip install pykyra
      ```

- **Pyglet**
    - **Descrição:** Uma biblioteca multimídia Python para criar jogos e outras aplicações multimídia. Oferece suporte para OpenGL, gerenciamento de janelas, entrada de usuário, carregamento de imagens e vídeos, e reprodução de som.
    - **Instalação via pip:**
      ```bash
      pip install pyglet
      ```

- **Arcade**
    - **Descrição:** Uma biblioteca Python moderna e fácil de usar para criar jogos 2D. É construída sobre Pyglet e oferece uma abordagem mais orientada a objetos e recursos convenientes para iniciantes e desenvolvedores experientes.
    - **Instalação via pip:**
      ```bash
      pip install arcade
      ```

- **PyOpenGL**
    - **Descrição:** Uma biblioteca que fornece ligações Python para a API gráfica OpenGL. Permite criar gráficos 2D e 3D avançados, sendo a base para muitas aplicações de visualização e jogos 3D em Python.
    - **Instalação via pip:**
      ```bash
      pip install pyopengl PyOpenGL_accelerate
      ```

- **Panda3D**
    - **Descrição:** Um motor de jogo 3D de código aberto desenvolvido pela Disney e Carnegie Mellon. Oferece um conjunto completo de ferramentas para criar jogos 3D com gráficos avançados, física, áudio e entrada.
    - **Instalação:**
      ```bash
      # A instalação do Panda3D pode variar dependendo do sistema operacional.
      # Consulte a documentação oficial para as instruções detalhadas.
      # Geralmente envolve baixar um instalador específico.
      # pip install panda3d (pode instalar uma versão limitada ou antiga em alguns sistemas)
      ```

- **Ren'Py**
    - **Descrição:** Um motor visual novel gratuito que facilita a criação de histórias interativas com texto, imagens, áudio e vídeo. É amplamente utilizado para desenvolver visual novels e jogos de simulação de encontros.
    - **Instalação:** N/A (geralmente baixado como um pacote completo do site oficial).

- **Cocos2d**
    - **Descrição:** Uma família de frameworks de desenvolvimento de jogos 2D multiplataforma. Cocos2d-x é escrito em C++, mas existem versões em Python como Cocos2d-python, que permitem criar jogos 2D para diversas plataformas. *(Cocos2d-python parece menos ativo atualmente)*
    - **Instalação via pip (se disponível):**
      ```bash
      pip install cocos2d
      # Pode haver variações dependendo da versão. Consulte a documentação.
      ```

## 2.5 Automação WEB & Scraping (Web Automation & Scraping)

Esta seção lista bibliotecas Python essenciais para automatizar interações com a web e extrair dados de páginas web.

- **Urllib**
    - **Descrição:** Um módulo da biblioteca padrão do Python para trabalhar com URLs. Permite fazer requisições HTTP, baixar dados da web e manipular cookies e cabeçalhos. É uma biblioteca de baixo nível, mas fundamental.
    - **Instalação:** Já incluído na biblioteca padrão do Python (não requer instalação via pip).

- **Requests**
    - **Descrição:** Uma biblioteca HTTP para Python mais amigável e poderosa que o Urllib. Simplifica o envio de requisições HTTP, o tratamento de respostas e a manipulação de cookies e sessões. É amplamente utilizada para web scraping e interação com APIs web.
    - **Instalação via pip:**
      ```bash
      pip install requests
      ```

- **Selenium**
    - **Descrição:** Uma ferramenta para automatizar navegadores web. É usada principalmente para testes de aplicações web, mas também é poderosa para web scraping de sites dinâmicos que dependem de JavaScript para renderizar conteúdo. Requer um driver de navegador (como ChromeDriver para Chrome).
    - **Instalação via pip:**
      ```bash
      pip install selenium
      ```

- **Webbot**
    - **Descrição:** Uma biblioteca para automatizar a interação com navegadores web. Oferece uma API simples para navegar em páginas, preencher formulários, clicar em botões e extrair dados. *(Projeto parece menos ativo atualmente)*
    - **Instalação via pip:**
      ```bash
      pip install webbot
      ```

- **Beautifulsoup**
    - **Descrição:** Uma biblioteca para analisar documentos HTML e XML. Facilita a navegação na estrutura do documento, a busca por elementos específicos e a extração de dados. Geralmente usada em conjunto com bibliotecas de requisição HTTP como Requests.
    - **Instalação via pip:**
      ```bash
      pip install beautifulsoup4
      ```

- **Scrapy**
    - **Descrição:** Um framework poderoso para web scraping e extração de dados em grande escala. Fornece uma arquitetura robusta para construir crawlers (spiders) que seguem links, extraem dados e os armazenam de forma estruturada.
    - **Instalação via pip:**
      ```bash
      pip install scrapy
      ```

- **PyAutoGUI**
    - **Descrição:** Uma biblioteca para controlar programaticamente o mouse e o teclado. Pode ser usada para automatizar interações com a interface gráfica do usuário (GUI) de aplicativos web rodando em um navegador.
    - **Instalação via pip:**
      ```bash
      pip install pyautogui
      ```

- **Keyboard**
    - **Descrição:** Uma biblioteca para controlar e monitorar eventos de teclado. Permite simular pressionamentos de teclas e capturar eventos de teclado globais.
    - **Instalação via pip:**
      ```bash
      pip install keyboard
      ```

- **Pynput**
    - **Descrição:** Uma biblioteca que permite controlar e monitorar dispositivos de entrada (teclado e mouse). Fornece uma maneira de escutar eventos de entrada e controlar o mouse e o teclado.
    - **Instalação via pip:**
      ```bash
      pip install pynput
      ```

## 2.6 Automação de Tarefas (Task Automation)

Esta seção apresenta bibliotecas Python úteis para automatizar tarefas repetitivas no sistema operacional e em outras aplicações.

- **OS**
    - **Descrição:** Um módulo da biblioteca padrão do Python que fornece uma maneira de usar funcionalidades dependentes do sistema operacional, como interagir com o sistema de arquivos, executar comandos do shell e obter informações sobre o ambiente.
    - **Instalação:** Já incluído na biblioteca padrão do Python (não requer instalação via pip).

- **RPA (Robotic Process Automation)**
    - **Descrição:** Refere-se a um campo de automação que utiliza software para automatizar tarefas repetitivas baseadas em regras, geralmente realizadas por humanos interagindo com sistemas digitais. Existem bibliotecas Python que auxiliam em tarefas de RPA, mas "RPA" em si não é uma biblioteca específica para instalar via pip. Algumas bibliotecas como `pyautogui` e outras podem ser usadas em soluções de RPA.

- **APScheduler**
    - **Descrição:** Uma biblioteca para agendar tarefas Python para serem executadas em momentos específicos ou em intervalos regulares. Suporta diferentes tipos de gatilhos (data, intervalo, cron) e backends de armazenamento para persistência.
    - **Instalação via pip:**
      ```bash
      pip install apscheduler
      ```

- **Watchdog**
    - **Descrição:** Uma biblioteca para monitorar mudanças no sistema de arquivos. Permite executar ações personalizadas em resposta a eventos como criação, modificação ou exclusão de arquivos e diretórios.
    - **Instalação via pip:**
      ```bash
      pip install watchdog
      ```

- **Paramiko**
    - **Descrição:** Uma biblioteca Python que fornece suporte para os protocolos SSHv2. Permite conectar-se a servidores remotos, executar comandos e transferir arquivos de forma segura, sendo essencial para automação de tarefas em servidores remotos.
    - **Instalação via pip:**
      ```bash
      pip install paramiko
      ```