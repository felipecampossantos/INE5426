# INE5426 - Construção de Compiladores
## Analisador Léxico
Implementação do Analisador Léxico para a linguagem gerada por CC-2021-2.

## Requerimentos
- Python 3 (versão ^3.6.9)
- PIP 3, para instalação de pacotes necessários para execução do programa
- Python 3 virtual environment (python3.8-venv)

## Execução
A execução do programa irá criar automaticamente o ambiente virtual e irá instalar as dependências necessárias.
Para executar o programa, digitar o comando  `make run filepath=<file/path>`. 

Caso não seja passado o caminho do arquivo para o `filepath`, por padrão será utilizado o arquivo `src/examples/examplo1.lcc`.
Para facilitar os testes, foi adicionado ao makefile um "filepath coringa", que permite rodar as análises para todos os exemplos do codigo. Para isso, digite o comando `make run filepath=all`.

Exemplo de uso: `make run filepath=src/examples/utils.lcc`

## Relatório
O Relatório do trabalho se encontra no mesmo diretório deste ReadMe, assim como os diagramas de transição.


