# disciplinaDesevolvimentoWebBackend
    Para cada projeto foi criado uma nova branch

        * Projeto 1 / controle de gastos de carolina = branch controleGastos

            01. As informações a seguir se referem à Planilha Excel de Vera, que faz o controle de seus gastos diários.
            Para cada gasto, Vera cadastra: o tipo do gasto (remédio, roupa, refeição etc.), a data do gasto, o valor
            gasto e a forma de pagamento (dinheiro, cheque, cartão ou cheque pré).
            Utilizando Python com Django, crie uma aplicação para armazenar os gastos de Vera.

                                    _________________________
                                             Despesas
                                    _________________________
                                    data_criacao: string
                                    _________________________
                                    tipo_despesa: string
                                    _________________________
                                    descrição: string
                                    _________________________
                                    forma_pagamento: string
                                    _________________________
                                    vencimento: data
                                    _________________________
                                    quitado: bool
                                    _________________________

            Opcional: Aplique as opções com choices para os campos Forma Pagamento de Tipo de Despesa. Choices
            são listas ou tuplas que definem opções restritivas à campos. Se as forem informadas, elas serão aplicadas
            pela validação do modelo, podendo até mesmo substituir um campo Foreign Key. Para ver a documentação,
            clique aqui.



        
        * Projeto 2 / Compras Carolina = branch compras

            02. Carolina não tem mais tempo de fazer as compras pessoalmente. Precisou detalhar o produto, de forma
            a lhe permitir delegar essa tarefa a outra pessoa. Além disso, não quer que paguem um valor absurdo
            por algum produto. Sendo assim, incluiu a coluna "preço máximo já comprado". O "preço máximo já
            comprado" é inserido, a partir das compras efetivamente realizadas.
            Utilizando Python com Django, crie uma aplicação para armazenar as compras de Carolina.


                                    ______________________
                                            Compras
                                    ______________________
                                    nome: string
                                    ______________________
                                    descricao: string
                                    ______________________
                                    unidadeCompra: string
                                    ______________________
                                    preco: real
                                    ______________________
                                    precoMaximo: real
                                    ______________________
                        