# Utilização da plataforma LabViR

 O LabViR utiliza o conceito de conteiner para executar os cursos. Os containers são imagens docker que contém todos os recursos necessários para executar os cursos. Eles podem ser baixados e executados localmente ou executados em nuvem através de um navegador. Neste projeto optamos por utilizar o GitHub Codespaces como ambiente de execução virtual. Sua utilização é grattuita para usuários de GitHub e possui um limite de 60 horas de uso por mês.

 As imagens foram criadas utilizado o repositório oficial do ROS 1 - noetic - no Docker Hub ([ttps://hub.docker.com/r/osrf/ros/tags](https://hub.docker.com/r/osrf/ros/tags)) no ambiente Linux Ubuntu Focal 20.04. 

# Para executar **localmente** os cursos desta plataforma é necessário

    - Ter uma conta no github - www.github.com
    - Ter o Docker instalado e configurado em sua máquina
    - Ter o VSCode instalado em sua máquina com extensão Remote Development, ROS e Docker
    - Sua máquina pode utilizar Windows, Mac ou Linux (recomendamos Linux por conveniência)

Os procedimentos para executar os cursos localmente são:

- Crie no seu computador uma pasta para armazenar os cursos - exemplo: cursos_ros_labvir
- Acesse o repositório no curso que deseja executar através do botão **"GitHub"**. Isso criará uma cópia do repositório no seu computador.
- Abra o VSCode e abra a pasta criada (File -> Add Folder to workspace).
- Dentro do VSCode, clique em **"Remote-Containers: Reopen in Container"**. Isso irá criar um container com todas as dependências necessárias para executar os cursos. 

**Importante:** 
    1. A criação do container pode demorar alguns minutos e requer um espaço de disco de aproximadamente 6 a 8 GB.
    2. Uma vez criado o container a próxima execução será muito mais rápida.

- Uma vez aberto o container, o ambiente virtual estará disponível para uso no seu **navegador**, para isso acesse o endereço: http://localhost:6080/ conecte e faça os ajustes necessários para resolução de tela, conforme seu computador.

- A partir daqui você poderá abrir o VSCode dentro do ambiente virtual e poderá trabalhar normalmente nas atividades do curso. Para isso inclua o folder do curso no seu workspace (File -> Add Folder to workspace) e abra o arquivo README.md (clique com o botão direito na aba para exibir o preview) e siga as instruções para executar o curso.

**Importante:**
    1. Você poderá executar o curso a partir do vscode no ambiente local, mas **as janelas gráficas do ROS não serão exibidas**, elas serão exibidas apenas no ambiente virtual exibido no navegador.

# Para executar **remotamente** os cursos desta plataforma é necessário

    - Faça login conta no github - [www.github.com](www.github.com) - recomendamos utilizar o GitHub Education com uma conta de estudante/professor - [link](https://docs.github.com/en/education/about-github-education/github-education-for-students/about-github-education-for-students)
    - Acesse o curso que deseja executar através do botão **"Open in Codespaces"**. Você será direcionado a uma página no Codespaces onde poderá escolher o tamanho da máquina virtual.

    - Se for a primeira vez que você está utilizando o repositorio no Codespaces você deverá criar o ambiente virtual. Para isso clique em **"Create codespace on main"** e aguarde o ambiente ser criado (pode demorar alguns minutos).

    - Uma vez aberto o ambiente o Codespaces irá abrir o VSCode no seu navegador. Da mesma forma que para o ambiente local, acesse o endereço disponibilizado na aba "Ports", clicando em **"Open in Browser"**. Isso irá abrir o ambiente virtual no seu navegador. Faça os ajustes necessários de resolução de tela, conforme seu computador.

    - A partir daqui você poderá abrir o VSCode dentro do ambiente virtual e poderá trabalhar normalmente nas atividades do curso. Para isso inclua o folder do curso no seu workspace (File -> Add Folder to workspace) e abra o arquivo README.md (clique com o botão direito na aba para exibir o preview) e siga as instruções para executar o curso.

    **Importante:**
        1. A utilização do Codespaces é gratuita **até o limite de 60 horas por mês**, por isso, é importante que você sempre feche o ambiente depois de utilizar.
        2. Para fechar o ambiente remoto, no VSCODE clique em Status Bar -> Remote-Containers: Stop Remote Container. 
        3. Para ter certeza que o ambiente foi fechado, aAcesse o link [github.com/codespaces](www.github.com/codespaces) e clique em **"Stop my codespace"**





    
    
    






