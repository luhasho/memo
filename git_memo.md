# sshエージェントへの登録

```bash
eval `ssh-agent`
ssh-add ~/.ssh/id_rsa_github

```

# github からクローンを作成 ssh

```bash

git clone git@github.com:luhasho/test.git
git clone git@github.com:luhasho/dotfiles.git
git clone git@github.com:luhasho/memo.git
git clone git@github.com:luhasho/Bat-to-Execute-PS

```

# github からクローン作成 https
```
git clone https://github.com/luhasho/dotfiles.git
git clone https://github.com:luhasho/memo.git

```

# git 基本

```bash

git --version

git status
git add *
git status
git commit
git push

git pull

```

# git config 設定

## git config 確認
```bash
git config --list

```

# user mail 設定
```bash
git config --global user.name "<user>"
git config --global user.email <mail>
```

# git editor gvimに変更 フルパス指定
```
# どちらでも良いが、/ を推奨 \ だと \\ になります
git config --global core.editor "'C:/Program Files/Vim/vim90/gvim.exe' -f -c 'set fenc=utf-8'"
git config --global core.editor "'C:\Program Files\Vim\vim90\gvim.exe' -f -c 'set fenc=utf-8'"

```

# git editor gvimに変更 パスが通ってる場合
```
git config --global core.editor 'gvim -f -c "set fenc=utf-8"'

```

