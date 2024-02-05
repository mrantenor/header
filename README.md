![File 1](/header.png)

## Aplicação
1) Instalar o visualizador de imagens **tiv**:

```
sudo snap install tiv --edge
```
2) Instalar lolcat
```
sudo snap install lolcat
```  
3) Fazer o download do arquivo txt na pasta ```.config```.
4) Colocar o seguinte texto no arquivo .bashrc ou .zshrc
```
######## INICIALIZAÇÃO #########
printf "%67s\n" "M87󰫢" | lolcat

cat $HOME/.config/M87.txt

echo -e "\e[7A  ╭─  HELLO WORLD!\n  │\n  ├─󱑓  $(date)\n  │\n  ╰─  Bruno Antenor\n
" | lolcat
```
