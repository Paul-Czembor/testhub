on dell µ
git config --global user.name 'Paul-Czembor'
etc
git config --list
git add xxx
git add fred
git commit
git status -s
ssh-keygen -t ed25519 -C "pczembor@icloud.com"
caa-ll it testkey
 ssh-add testkey
 copy in key to github (ssh)
 cat testkey.pub
 test cnnection
 ssh -T git@github.com
 set up a reo on github$$
 copy local repo to github$-(first set location)
  git remote add origin git@github.com:Paul-Czembor/testhub.git
  see status
  git remote -v
  now can send it
  git push -u origin master
then copy the url andcan copy it anywhere
 git clone https://github.com/Paul-Czembor/testhub
