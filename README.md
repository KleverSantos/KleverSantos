### Hi there 👋
<div>
<h1> Ola, me chamo Klever Santos Ribeiro<h1>
<h4>Infos:</h4>
<h6>* Pretendo trabalhar em empresas onde posso me desenvolver e contribuir com a equipe</h4>
<h6>* Sou comunicativo e positivo</h6>
<h6>* Gosto de trabalhar em equipe
<h6>* Sou sempre focado nos objetivos
<h6>* Amo tecnologia

</div>

##

<div align="center">
  <a href="https://github.com/KleverSantos">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=KleverSantos&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=KleverSantos&layout=compact&langs_count=7&theme=dark"/>
</div>
  
  <div style="display: inline_block"><br>
  <img align="center" alt="Klever-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="KLever-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Klever-java" height="50" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original-wordmark.svg" />
  <img align="center" alt="klever-Git" height="60" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original-wordmark.svg" />
  <img align="center" alt="klever-bootstrap" height="50" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original-wordmark.svg" />  
  <img align="center" alt="klever-bootstrap" height="50" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original-wordmark.svg" />
          
          
          
</div>
  
  ##
  
  <div>
  <a href="https://www.instagram.com/klxvxr_/?hl=bg" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:kleversantosribeiro@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/klever-santos-ribeiro-021b7b230/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="https://www.facebook.com/klever.santosribeiro/"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"
target="_blank"></a>
  </div>

  - uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
