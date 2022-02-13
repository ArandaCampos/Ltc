## Ltc - lista correlacionada

![Badge de licença](http://img.shields.io/static/v1?label=LICENÇA&message=GNU&color=sucess&style=for-the-badge)   ![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=CONCLUÍDO&color=sucess&style=for-the-badge)   ![Badge versionamento](http://img.shields.io/static/v1?label=VERSAO&message=1.0&color=sucess&style=for-the-badge)

&emsp;O projeto nasceu da necessidade que eu tinha de armazenar e consultar pequenas informações durante o meu dia, como comandos bash, <strong>OS DIVERSOS PARÂMETROS DO GCC </strong>, bibliotecas específicas, entre outros. Pensando nisso, o script armazena qualquer tipo de dado sem nenhum critério e, para consultá-lo, basta informar uma palavra chave ou parte do dado em que deseja buscar<br>
&emsp;Vale destacar que este script Shell <strong>não criptografa os dados</strong>, portanto, não deve ser usado para guardar dados sensíveis!

## Modo de usar

    # Ajuda
    $ ltc --help

    # Adicionar dado
    $ ltc --new [ARGUMENTO1] [ARGUMENTO2] ... [ARGUMENTON]

    # Consultar dados
    $ ltc --search [ARGUMENTO]

    # Remover dados
    $ ltc --remove [ARGUMENTO]

    # Remover todos os dados
    $ ltc --allremove

    # Imprimir todos os dados da lista
    $ ltc --allprint

    # Versão
    $ ltc --version

## Pré-requisitos

- Bash
- Sistema operacional Linux

## Instalação

    # Clonar o repositório
    $ git clone https://github.com/ArandaCampos/Config-Neovim.git

    # Entrar no diretório
    $ cd Ltc/usr

    # Para executá-lo através do bash
    $ bash ltc --verion

    # Para torná-lo executável
    $ chmod u+x ltc || ltc --version


E está pronto para usá-lo 👨‍💻

