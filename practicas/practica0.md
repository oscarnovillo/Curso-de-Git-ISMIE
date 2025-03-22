# Practica 0 Setup

- Instalacion de GIT en Windows
    - [Git for windows](https://git-scm.com/)
    - [Cmder](https://cmder.app/)
- Instalacion de GIT en linux
    
    ``` bash 
        apt get install git 
    ```
- Instalacion de IDES
    - [GIT KRAKEN](https://www.gitkraken.com/)
    - [VSCODE](https://code.visualstudio.com/)
    - [WS intellij](https://www.jetbrains.com/webstorm/)
    - [INTELLIJ](https://lp.jetbrains.com/intellij-idea-promo/?source=google&medium=cpc&campaign=EMEA_en_ES_IDEA_Branded&term=intellij&content=693349187718&gad_source=1&gclid=CjwKCAjwnPS-BhBxEiwAZjMF0kPnvpQsgOXvlsq_elb-w59nzmDMxkhHA3Vf371coGksZLeLiJt7MxoCUCEQAvD_BwE)

- Configuracion global git
    ```bash
    git config --global user.name "John Doe"
    git config --global user.email "johndoe@example.com

    # solo si vas a usar windows y linux a la vez
    
    # en linux
    git config --global core.autocrlf input
    git config --global core.safecrlf true

    # en windows
    git config --global core.autocrlf true
    git config --global core.safecrlf true
    ```

- Alta en GITHUB
    - Alta con tu cuenta de educamadrid para luego poder pedir las ventajas de education
    - [Ayuda en esta pagina](https://docs.github.com/es/education/explore-the-benefits-of-teaching-and-learning-with-github-education/github-education-for-teachers/apply-to-github-education-as-a-teacher)