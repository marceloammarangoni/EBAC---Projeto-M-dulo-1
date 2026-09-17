# Calculadora em Python
Este repositório contém uma calculadora simples desenvolvida em Python, além de um script shell para facilitar sua execução em ambientes Linux.
# Estrutura do repositório
```
.
├── projeto_calculadora.py   # Script principal da calculadora
├── python_script.sh      # Script shell para execução automatizada
└── README.md
```
# Pré-requisitos
Sistema operacional Linux (ou WSL, no caso de Windows) Python 3 instalado.
Para verificar se o Python 3 está instalado, execute:
```bash
python3 --version
```
# Como usar o script Python diretamente
Clone o repositório em sua máquina:
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```
Execute o script com o Python 3:
```bash
python3 projeto_calculadora.py
```
Siga as instruções exibidas no terminal para realizar os cálculos.
# Como usar o script shell
O script `python_script.sh` automatiza a execução da calculadora, chamando o interpretador Python corretamente.
Dê permissão de execução ao script (necessário apenas na primeira vez):
```bash
chmod +x python_script.sh
```
Execute o script:
```bash
./python_script.sh
```
Isso iniciará a calculadora automaticamente, sem a necessidade de chamar o Python manualmente.
# Funcionalidades da calculadora
Operações básicas: soma, subtração, multiplicação e divisão;
Entrada de dados via terminal;
Tratamento de erros para entradas inválidas (ex.: divisão por zero).
# Padrão de commits
Este projeto segue a convenção de mensagens de commit no modo imperativo, descrevendo a ação realizada, por exemplo:
`Adiciona script da calculadora`,
`Atualiza instruções no README` e
`Corrige erro de divisão por zero`.
Esse padrão facilita o entendimento do histórico de alterações do projeto.
# Autor
Marcelo Augusto Menezes Marangoni
