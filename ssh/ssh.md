# SSH

1. Baixar as chaves pública e privada e conceder permissão 600.

~~~sh
# Conceder a permissão 600 para as chaves
$ chmod 600 ssh-key-2022-08-23.key
$ chmod 600 ssh-key-2022-08-23.key.pub
~~~

2. Acessar á máquina

~~~sh
# Conectar
$ ssh opc@150.136.5.64 -i ssh-key-2022-08-23.key
~~~

[Voltar](/README.md)