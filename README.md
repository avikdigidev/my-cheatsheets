# my-cheatsheets
----------------------------------------------------------------------------------------------------------
##Configuring git and github on a new machine
git config --global user.name "avikdigidev"
git config --global user.email "avikdigidev@gmail.com"
git config --global --list
git config --global color.ui true
git config --global core.editor emacs
ssh-keygen -t rsa -C "avikdigidev@gmail.com"
#Copy your public key (the contents of the newly-created id_rsa.pub file) into your clipboard.

#In a terminal/shell, type the following to test it:

ssh -T git@github.com
#If it says something like the following, it worked:

#Hi username! You've successfully authenticated, but Github does not provide shell access.
