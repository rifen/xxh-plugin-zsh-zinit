<p align="center">  
<a href="https://github.com/zdharma/zinit/">Zinit</a> plugin for <a href="https://github.com/xxh/xxh-shell-zsh">xxh-shell-zsh</a>.
</p>

<p align="center">  
If you like the idea of xxh click ⭐ on the repo and stay tuned.
</p>

## Install
From xxh repo:
```
xxh +I xxh-plugin-zsh-zinit
```
From any repo:
```
xxh +I xxh-plugin-zsh-zinit+git+https://github.com/yourname/xxh-plugin-zsh-zinit
```    
Connect:
```
xxh [user@]host[:port] +s zsh +if
```

## Seamless mode
To use seamless mode with saving your theme and plugins use `source` command: 
```
source xxh.zsh myhost
```

## Environment variables

Xxh support environment variables: `xxh myhost +e NAME=VAL` or `~/.config/xxh/config.xxhc` (`$XDG_CONFIG_HOME`) config.

* `+e ZSH_THEME=clean` - set theme
* `+e plugins="(git ubuntu)"` - set plugins list
