# MacOS utilities

- [tilde-switch](./tilde-switch) is a script to replace the "\`" and "§"

To fix the Fin/Inicio or End/Start keys in terminal, just write this in your `~/.zshrc`

```shell
bindkey "\e[H" beginning-of-line
bindkey "\e[F" end-of-line
```
