Olá, sou o Eduardo!

🌱 Olá, sou Eduardo! Formado em Administração de Empresas com foco em coaching e análise comportamental. Buscando uma nova paixão, me encontrei no universo da tecnologia. Atualmente, estou trabalhando como desenvolvedor AEM, especificamente com desenvolvimento de aplicações web. Curioso, criativo e disciplinado, fico na maior parte do meu tempo livre estudando novas tecnologias, batendo papo em calls com amigos e com a família (sou casado). Tenho experiência em visão de negócios e gestão de pessoas, assim como habilidades em liderança e comunicação com foco em entrega de resultados.

:books: Acesse o meu Web Currículo e conheça mais sobre mim: https://61e59dcf10fde3fa1ca706b2--keen-montalcini-4cd445.netlify.app

:hammer: Hoje, sou colaborador da Compass, do grupo UOL, focado no desenvolvimento Web Front-End com React.js.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Eduardo-SBorges)](https://github.com/Eduardo-SBorges/github-readme-stats)


📫 Contato:
WhatsApp: 53 9 9138-6031
| E-mail: eduardosorbor@gmail.com

name: WakaTime status update

on:
  schedule:
    # Runs at 12 am  '0 0 * * *'  UTC
    - cron: "1 0 * * *"

jobs:
  update-readme:
    name: Update the WakaTime Stat
    runs-on: ubuntu-latest
    steps:
      # Use avinal/Profile-Readme-WakaTime@<latest-release-tag> for latest stable release
      # Do not change the line below until you have forked this repository
      # If you have forked this project you can use <username>/Profile-Readme-WakaTime@master instead
      - uses: avinal/Profile-Readme-WakaTime@master
        with:
          # WakaTime API key stored in secrets, do not directly paste it here
          WAKATIME_API_KEY: 5553fd58-8452-4394-88a4-707b8a3536c3
          # Automatic github token
          GITHUB_TOKEN: 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
          # Branch - newer GitHub repositories have "main" as default branch, change to main in that case, default is master
          BRANCH: "master"
          # Manual Commit messages - write your own messages here
          COMMIT_MSG: "Automated Coding Activity Update :alien:"
