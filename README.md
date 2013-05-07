vim
===

1. How to generate key 
====
  1) ssh_keygen -C <email> -t rsa
  2) cat ~/.ssh/id_rsa.pub
  3) copy the content to github.com->Account Settings->SSH Keys

2. How to pull the repository from remote 
====
  git pull git@github.com:peteryj/vim.git

3. How to push the repository to remote 
====
  git push git@github.com:peteryj/vim.git

4. For GO Language
====
  You need to disable 'syntax on' in '/etc/vim/vimrc', otherwise it will not work correctly.
