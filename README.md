# Ponderada CPU

###### Aluno: Gabriel Gallo Menequini Coutinho

## O que é?

Esse repositório contém os arquivos do Digital (.dig) criados para desenvolver uma CPU baseada na arquitetura SAP de Albert Malvino com algumas mudanças estruturais, como:

* Palavra de controle de 13 bits para acomodar 4 operações na ALU
* Sinal NLi utilizado como Clear do Program Counter
* Uso de ROMs ao invés de RAMs
* Padronização de todas as saídas para o W bus para terem 8 bits
* Separação do MAR e ROM para os ciclos de fetch e execute

Entre outras alterações.

## Como executar?

Para consiguir executar os arquivos e visualizar a arquitetura construída, deve-se:

1. Baixar o Digital (https://github.com/hneemann/Digital)
2. Descompilar o zip baixado e executar o arquivo de a cordo com o sistema operacional (para Linux, o comando é `source Digital.sh`, para Windows, basta clicar no executável)
3. Com o Digital aberto, basta selecionar o arquivo de CPU.dig para ser aberto e executar o programa

## Vídeo explicativo:

https://drive.google.com/file/d/1KdCYkly-IS02cinLVBasSOACUjyuB3gN/view?usp=sharing
