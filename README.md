Para começarmos, instalamos o NODE.js pelo prompt de comando do Linux usando os seguintes:

.sudo apt install python3-pip

Aguarde a instalação

.pip3 install --user nodeenv

Teste a instalação usando o comando:

.nodeenv --version 

Digite no terminal do prompt:

.source ~/.profile

Para instalar o nodeenv, escolha a pasta que você irá instalar (Recomendo a pasta Downloads)

.nodeenv  nodejs-env 
Onde o nodeenv e o comando, e o nodejs-env se trata da pasta.

Após isso, ative:

.source ./nodejs-env/bin/activate

O indicador do prompt irá mudar, o que signifique que deu certo. Para testar digite:

.node --version 
