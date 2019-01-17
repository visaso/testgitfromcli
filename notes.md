  215  cd Desktop/
  216  cd Angular/
  217  git clone https://github.com/mattpe/git-intro.git
  218  ll
  219  cd git-intro/
  220  ll
  221  ssh-keygen -t rsa -b 4096 -C "visa.soininen@metropolia.fi"
  222  ls -al ~/.ssh
  223  ssh-keygen -t rsa -b 4096 -C "visa.soininen@metropolia.fi"
  224  eval $(ssh-agent -s)
  225  ssh-add ~/.ssh/id_rsa
  226  clip < ~/.ssh/id_rsa.pub
  227  ssh -T git@github.com
  228  git remove origin
  229  git remote remove origin
  230  git remote add origin https://github.com/visaso/testgitfromcli.git
  231  git remote -v
  232  git push
  233  git push --set-upstream origin master
  234  git push origin master
  235  git push -u origin master
  236  git remote -v
  237  vi notes.md
  238  history
  239  cat notes.md
  240  vi notes.md
  241  git commit -u -m "Created notes.md"
  242  git commit -a -m "Created notes.md"
  243  git commit -A -m "Created notes.md"
  244  git commit --all -m "Created notes.md"
  245  git add notes.md
  246  git commit -u -m "Created notes.md"
  247  git push
  248  history

