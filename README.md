# Guia definitivo Git e GitHub

    ## Iniciando um Repositório

    - 1º Passo - Instalar o Git no Computador (Software de Versionamento local);

    - Configurar o Software de Versionamento:
        - git config --global user.name "Adrielly0124"
        - git config --global user.email "drika.dantas24@gmail.com"
        - git config --list

    - 3º Passo - Iniciar o Repositorio Local
        - git init (cria o ambiente de versionamento na pasta do Projeto)

    - 4º Passo - Iniciar o Repositório online (site GitHub) GIT-GITHUB
        - git remote add origin + link_do_repositorio_github
        - git remote get-url origin (verificar o link)
        - git remote set0url origin +link_do_repositorio_github (modificar o link)

    - 5º Passo - Adicionar meus Arquivos ao Repositório local
        - git add +nome_do_arquivo
        - git add . (adiciona todos os arquivos de uma única vez)
    