<hr>
<img src="https://media.giphy.com/media/c2lbMLWfL1mQ8/giphy.gif" align="right" widht="400" height="250">

### Hi there I'm Eren KALAYCI

### Reach out to me
<p align="left" dir="auto">
<a href="https://twitter.com/erenklyctr" rel="nofollow"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" height="20" width="20" style="max-width: 100%;"></a>
&nbsp;
<a href="https://www.linkedin.com/in/erenklyc/" rel="nofollow"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" height="20" width="20" style="max-width: 100%;"></a>
</p>

### Languages and tools
<p align="left" dir="auto">
<img src="https://avatars.githubusercontent.com/u/38549573?s=200&v=4" widht="25" height="25">
&nbsp;
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/dart/dart.png" widht="25" height="25">
&nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" widht="25" height="25">
&nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" widht="25" height="25">
&nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" widht="25" height="25">
&nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" widht="25" height="25">
</p>

<br>
<hr>

<details>
<summary> 💡Github Stats </summary>
<br>
<img src="https://github-readme-stats.vercel.app/api?username=KLYCHUB&show_icons=true&theme=graywhite">
</details>

<details>
<summary> 💡Most Used Langues </summary>
<br>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KLYCHUB&layout=compact">
</details>

<hr>

<img src="https://komarev.com/ghpvc/?username=your-github-KLYCHUB&label=PROFILE+VIEWS">


- uses: Platane/snk@v2
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
      
      <picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg">
  <img alt="github-snake" src="github-snake.svg">
</picture>
