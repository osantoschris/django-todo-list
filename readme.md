# Django ToDo List

## A aplicação
Esta aplicação faz parte de um conjunto de projetos construidos com o Framework Django do Python. Para a construção e execução desta aplicação, foi utilizada a versão 5.0.6 deste Framework. As demais bibliotecas podem ser encontradas no requirements deste repositório, basta seguir as instruções da seção de Instalação.

## Instalação
Para executar o projeto em abmientes de teste, recomenda-se criar ativar o ambiente virtual dentro da pasta do projeto (.venv). Utilize o arquivo requeriments.txt para instalar as biblitecas necessárias para a correta execução.

## Funcionalidades
### Nova Tarefa
Utilize a função de nova tarefa para adicionar novos itens a lista ToDo. Assim que a inclusão for finalizada, será listada na tela inicial da aplicação. 

### Concluir
Cada tarefa possui a opção de <i>concluir</i> para que seja reportada como finalizada. Assim que a tarefa for concluída, será adicionada a data de conclusão e os botões Concluir e Editar serão desabilitados. 

### Editar
Para cada tarefa ainda não concluída, é possivel realizar a edição de suas informações, como:
- Nome da Tarefa
- Data de Entrega

### Excluir
Caso seja necessário, realize a exclusão da tarefa após a confirmação. Para garantir que o usuário não realizará uma exclusão equivocada, ao clicar no botão <i>excluir</i> da tarefa, o mesmo será redirecionado para uma página de confirmação de exclusão. Ao confirmar, a tarefa será excluída do banco de dados.