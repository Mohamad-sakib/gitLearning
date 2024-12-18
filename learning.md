step to setup personal device git to gitHub.
steps are :-
ssh-keygen -t ed25519 -C "myEmail@gmail.com"

ls ~/.ssh

To confirm further, type in ls -l ~/.ssh

ssh-add --apple-use-keychain ~/.ssh/id_ed25519

cat ~/.ssh/id_ed25519.pub | pbcopy

git config --global user.name "username"

git config --global --list

git config --global user.email "myEmail@gmail.com"
