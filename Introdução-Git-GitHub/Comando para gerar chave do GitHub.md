# Comando para gerar chave do GitHub:cat:

### Passo 1

Abrir o Gitbash.

### Passo 2

Digitar... ssh-keygen –t ed25519 –c + (email usado no github).

### Passo 3 

Apertar "enter".

### Passo 4

Digitar senha desejada.

### Passo 5

Digitar... cd /endereço do directorio onde esta a chave ssh.

### Passo 6

Digitar... comando.. cat mais nome da chave publica (.pub).

### Passo 7

Digitar... eval $(ssh-agent –s).