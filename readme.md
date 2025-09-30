## Sobre o programa

    Este programa em python é um programa com o intuito de estudar python através de programas feitos
    sobre demandas reais no mercado.

    Nesse caso, é possível acessar um site de advogados que através do numero de oab do advogado, consultamos todos os processos dele

    Além de consultar, o programa salva o o número do advogado em questão, os participantes do polo ativo do processo, e o número do processo em uma planilha.

    Este foi um estudo sobre automação web e manipulação de planilhas via python.

## Como usar?

1- ative o ambiente virtual com o comando:

    linux ->  source venv/bin/activate
    windows -> ./venv/Scripts/activate

    verifique se o no inicio da sua linha de comando aparece "(venv)", caso apareça, o ambiente está ativo.

    caso não funcione

    Instale a biblioteca Selenium com o comando: pip install selenium

2- Explicando o código:

    Na linha 25 do script é possível atribuir o numero de oab do advogado escolhido (pode usar o número padrão para teste)

3- Inicializar o progama:

    Caso esteja utilizando uma IDE, basta executar o arquivo app_automação_consultas.py

    Caso esteja usando o CMD, utilize o comando: python app_automacao_consultas.py
