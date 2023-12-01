# Configurando Chave SSH para o GitHub

1 - ssh-keygen -t rsa -b 4096 -C "seu_email@example.com"

2 - eval "$(ssh-agent -s)"
    ssh-add ~/.ssh/id_rsa

3 - cat ~/.ssh/id_rsa.pub


