# linux_notes

## Diretórios Principais
### bin
Essencial em todos os sistemas operacionais baseados em Unix (Unix-like), esse diretório é onde ficam armazenadas os arquivos binários dos programas instalados no Linux, sejam eles nativos ou não. Os binários são para o linux aquilo que os arquivos .exe são para o Windows, literalmente os executáveis do SO.

Tambéns é na pasta bin/ onde ficam armazenadas os arquivosos dos comandos que utilizamos no terminal, como "ls" ou "cd". 

Duas pastas que tem relação comk o bin/ são as pastas "usr/bin", onde ficam os arquivos dos programas instalados pelo usuário no SO e o "sbin/"(superuser/bin), onde ficam armazenados os aquivos referentes aos programas que administram o SO. 

A pasta /bin também é um dos primeiros diretŕios a serem montados na inicalização do SO. Devido a estrem nele os arquivos responsáveis pelo funcionamento dos comandos essenciais do sistema, para que assim, esses possam estar disponíveis até mesmo em momentos de recuperação ou troubleshoot na inicialização do SO. Por esses motivos, praticamente todas as instalações mímimas do Linux irão conter a pastas /bin.

* boot
* dev
* etc
* home
* lib
* mnt
* opt
* sbin
* srv
* tmp
* usr
* var

## Comandos Úteis
trocar senha do user: passwd username
pesquisar palavras ou comandos no history: history | grep comando ou "pedaço" do mesmo 
