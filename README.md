# -developing-task_term_true.dat
Challenge solution step by step

# Contextualização da tarefa:

O arquivo Term é o arquivo que contém dados sobre as usinas térmicas e contém um registro para cada usina. Uma das informações é sobre a geração térmica mínima dos 12 primeiros meses e um valor constante para os próximos anos (D+ANOS). Esse arquivo é uma das premissas de entrada para execução do modelo NEWAVE (modelo de longo prazo, ou seja, o modelo de planejamento de operação de médio prazo das usinas térmicas)

# A tarefa consiste em:

* Passo 1 - fauma solicitação (via código) usando o método GET para este link (link)

* Passo 2 - Nesse link, exite um arquivo zip que contém dois arquivos: arquivo1 e arquivo2

* Passo 3 - A tarefa consiste em ler o zip(via código), ediatr o arquivo (arquivo2) conforme a planilha arquivo1. Essa planilha contém informações de algumas usinas térmicas.

* Passo 4 - Para essas usinas, edite o arquivo2 com esse novos valores que foram obtidos na planilha.

* Passo 5 - Para as usinas que existem no arquivo2, mas não existem na planilha arquivo1, ignore e mantenha o mesmo valor

* Passo 6 - Ao final da edição, a usina deve estar com os valores: 62 SEROPEDICA 386. 100. 25.84 6.86 0.00 0.00 0.00 0.00 140 140 132 140 0.00 0.00 0.00 0.00 0.00

* Passo 7 - Após a edição salve o arquivo editado com o nome TERM_TRUE.DAT dentro do zip(via código) e mande por email, junto com o código
