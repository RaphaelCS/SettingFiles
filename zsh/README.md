# ZSH plugins & themes 





## 1. Plugins



### 1.1. zsh-syntax-highliting

#### Install

```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```



### 1.2. zsh-autosuggestions

[Official Site](https://github.com/zsh-users/zsh-autosuggestions)

#### Install

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```



### 1.3. fzf

```bash
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf && ~/.fzf/install
```





## 2. Themes



### 2.1. Powerlevel10k

[Official Site](https://github.com/romkatv/powerlevel10k#oh-my-zsh)

#### Install

```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k
```





# Python

1. conda init

   ```bash
   # >>> conda initialize >>>
   # !! Contents within this block are managed by 'conda init' !!
   __conda_setup="$('/home/raphael/miniconda3/bin/conda' 'shell.bash' 'hook' 2> /dev/null)"
   if [ $? -eq 0 ]; then
       eval "$__conda_setup"
   else
       if [ -f "/home/raphael/miniconda3/etc/profile.d/conda.sh" ]; then
           . "/home/raphael/miniconda3/etc/profile.d/conda.sh"
       else
           export PATH="/home/raphael/miniconda3/bin:$PATH"
       fi
   fi
   unset __conda_setup
   # <<< conda initialize <<<
   
   export PATH=/home/raphael/miniconda3/bin/conda:$PATH
   ```





# Proxy

```bash
export http_proxy=socks5://127.0.0.1:10808
export https_proxy=socks5://127.0.0.1:10808
```



