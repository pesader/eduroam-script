# Eduroam Script

Configure a eduroam no Linux com uma única linha de comando.

## O quê?

Este script é apenas uma versão levemente modificada do script disponibilizado
pela própria eduroam no site https://cat.eduroam.org/.

## Por quê?

Colocar o script pronto em um repositório reduz consideravelmente o número de
passos necessários para configurar a eduroam da Unicamp no Linux. Veja só a
comparação:

**Usando esse repositório**

1. Abrir um terminal
2. Rodar uma linha de comando

**Usando o site da eduroam**

1. Abrir um navegador
2. Acessar o site da eduroam
3. Selecionar a Unicamp
4. Baixar o script
5. Abrir um terminal
6. Rodar o script

## Como?

```bash
wget -qO- https://raw.githubusercontent.com/pesader/eduroam-script/main/eduroam.py > eduroam.py && python eduroam.py ; rm -rf eduroam.py
```
