# sshエージェントへの登録

```
eval `ssh-agent`
ssh-add ~/.ssh/id_rsa_github

```

# github からクローンを作成

```

git clone git@github.com:luhasho/test.git
git clone git@github.com:luhasho/dotfiles.git
git clone git@github.com:luhasho/memo.git

```

## git editor gvimに変更

```
#フルパス指定
git config --global core.editor '"C/Program Files (x86)/Vim/vim82/gvim.exe" -f -c "set fenc=utf-8"'

#パスが通ってる場合
git config --global core.editor 'gvim -f -c "set fenc=utf-8"'

```

