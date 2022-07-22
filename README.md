### Hi there 👋

- 🌱 I’m currently learning NLP,ML,deep learning, python, javascript & READTJS & TS
- 🤔 I’m looking for help with JS&TS
- 💬 Ask me about anything
- quote : We can only see a short distance ahead, but we can see plenty there that needs to be done.
  ![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=shel104&show_icons=true&theme=radical)
  [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=shel104&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
[![Ashutosh's github activity graph](https://activity-graph.herokuapp.com/graph?username=shel104&theme=rogue)](https://github.com/ashutosh00710/github-readme-activity-graph)
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
