# DAE

Esse é um sistema feito para vincular a recepção com cada profissional através de scripts que o googlesheet oferece, na UFPE DAE/PROAES.

Recepção:
A recepção conta com uma planilha online que contém as abas TelaInicial, BancoDados, Extras e as abas dos profissionais em operação (vale ressaltar que qualquer nome de profissional são fictícios, assim sendo não condiz com a realidade).
  
Abas:
A aba de TelaInicial é a principal aba da recepção, cuja a finalidade é colocar os dados dos estudantes que chegam para serem atendidos. Estas possuem alguns "botões" feitos através do google script, o primeiro é o "Novo registro", este botão atualiza esta mesma aba, setando para nulo ou '', todos os campos de preenchimento de informações e atualizando a hora de acordo com o horário atual de Pernambuco/Brasil, o segundo botão é o "Salvar Registro", este botão tem a finalidade de inserir na aba "BancoDados" todas as informações referentes ao estudantes, o terceiro botão é o "Buscar Aluno", este botão só funciona quando é colocado ou o Nome do estudante ou seu CPF, e com esta informação faz a busca no BancoDados e preenche automáticamente com as informações do estudante, o quarto botão é o "Buscar Agendamento", diferente do "Buscar Aluno", este botão pesquisa de acordo com o Nome ou CPF, apenas os estudantes que são agendamento e que estão com o status vazio ou em branco, ele é diferente do botão "Buscar Aluno" pois ele busca o id {continua...}
