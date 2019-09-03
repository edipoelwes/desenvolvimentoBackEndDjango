# disciplinaDesevolvimentoWebBackend
Para cada projeto foi criado uma nova branch
    * Projeto 1 / controle de gastos de carolina = branch controleGastos

        01. As informações a seguir se referem à Planilha Excel de Vera, que faz o controle de seus gastos diários.
        Para cada gasto, Vera cadastra: o tipo do gasto (remédio, roupa, refeição etc.), a data do gasto, o valor
        gasto e a forma de pagamento (dinheiro, cheque, cartão ou cheque pré).
        Utilizando Python com Django, crie uma aplicação para armazenar os gastos de Vera.

                                    Despesas
                                _____________________
                                data_criacao: string
                                _____________________
                                tipo_despesa: string
                                _____________________
                                descrição: string
                                _____________________
                                forma_pagamento: string
                                _____________________
                                vencimento: data
                                _____________________
                                quitado: bool
                                _____________________

        Opcional: Aplique as opções com choices para os campos Forma Pagamento de Tipo de Despesa. Choices
        são listas ou tuplas que definem opções restritivas à campos. Se as forem informadas, elas serão aplicadas
        pela validação do modelo, podendo até mesmo substituir um campo Foreign Key. Para ver a documentação,
        clique aqui.