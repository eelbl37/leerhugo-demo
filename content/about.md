Deze site is gemaakt om het deploy process te leren.

Een beschrijving van de stappen staat hier:
https://theplaybook.dev/docs/deploy-hugo-to-github-pages/


Een you tube filmpje staat hier:
https://www.youtube.com/watch?v=_QSr2_pxIJs

Een eigen domein maken voor je site:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain


Repo van de playbook:
https://github.com/dhij/theplaybook

you tube film over  deploy hugo maakt gebruik van docs/
https://www.youtube.com/watch?v=6BLFYo1wc0Q


Bij github is een nieuwe repo gemaakt leer-hugo
Er is een README.md aangemaakt en een licens

In de github repo is bij settings/pages

onder branch ingevuld in het eerste veld
       master  2e veld    /docs     save knop





De repo is lokaal gekloond.
In de config file is de baseDir aangepast naar:
https://github.com/eelbl37/leer-hugo

hugo # genereed de complete site in publick
hugo --minify  # maakt de site een kleinbeetj kleiner
hugo --minify --destination docs  # maakt de complete site nu aan in dics

alle aanpassingen in een commit opslaan

git add *
git remote origing git@github.com:eelbl37/leer-hugo.git

git push -u origin master   


