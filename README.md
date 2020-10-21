# ai_practical

In advance, you need to install anaconda.
you use usually pip or use pipenv from homebrew, apt chocolaty, anaconda maybe conflict these environment.
Because, when you want to use anaconda, you regist
this function and you use.

add this script .bash_profile
```
cat << END >> $HOME/.bash_profile
# this function is activate anaconda.

END

```
easiest solve is default shell is bash, when you want to use anaconda, use other shell, ex) if you are macOS user, use powershell.
```
conda init powershell
```

## install envs.yml

```
pwsh
conda env create -f=env.yml
```