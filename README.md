# fundamentos-reactjs

Funcionalidades da aplicação
Agora que você já está com o template clonado e pronto para continuar, você deve verificar os arquivos da pasta src e completar onde não possui código, com o código para atingir os objetivos de cada rota.

Listar as transações da sua API: Sua página Dashboard deve ser capaz de exibir uma listagem através de uma tabela, com o campo title, value, type e category de todas as transações que estão cadastradas na sua API.
Dica: Você pode utilizar a função Intl para formatar os valores. Dentro da pasta utils no template você encontrará um código para te ajudar.

Exibir o balance da sua API: Sua página Dashboard, você deve exibir o balance que é retornado do seu backend, contendo o total geral, junto ao total de entradas e saídas.

Importar arquivos CSV: Na sua página Import, você deve permitir o envio de um arquivo no formato csv para o seu backend, que irá fazer a importação das transações para o seu banco de dados. O arquivo csv deve seguir o seguinte modelo.

Dica: Deixamos disponível um componente chamado Upload na pasta components para você ter já preparado uma opção de drag-n-drop para o upload de arquivos. PS: Caso você esteja no windows e esteja sofrendo com algum erro ao tentar importar CSV, altere o tipo de arquivo dentro do arquivo components/upload/index.ts de text/csv para .csv, application/vnd.ms-excel, text/csv.
