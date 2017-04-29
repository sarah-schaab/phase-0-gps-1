  643  cd desktop
  644  git clone https://github.com/sarah-schaab/phase-0-gps-1.git
  645  cd phase-0-gps-1/
  646  touch awesome_page.md
  647  git add awesome_page.md
  648  git commit -m "add initial commit"
  649  git push origin master
  650  git checkout -b add-command-log
  651  subl readme.md
  652  history 20
  653  history 20
  654  history 20 >> readme.md
