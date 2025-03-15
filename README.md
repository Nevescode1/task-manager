# task_manager / Gerenciador de tarefas
## Descrição  
Este projeto é um aplicativo simples de gerenciamento de tarefas que permite adicionar, editar e excluir tarefas.
## Tecnologias Usadas
- .NET
- C#
- SQL Server
- Visual Studio
## Instalação
1. Clone o repositório:
   ```bash
   git clone (https://github.com/Nevescode1/task-manager.git)

### 5. ##Como Usar

### Passo 1: Iniciar o Aplicativo
Após clonar o repositório e configurar o ambiente local conforme as instruções de instalação, abra o projeto no **Visual Studio** ou no editor de sua escolha.

### Passo 2: Configurar o Banco de Dados
O aplicativo utiliza um banco de dados **SQL Server** para armazenar as tarefas. Para configurar o banco de dados:

1. Abra o arquivo `appsettings.json` e verifique a string de conexão:
   ```json
   "ConnectionStrings": {
     "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=TaskManager;Trusted_Connection=True;"
   }
Você pode alterá-la caso queira usar um servidor de banco de dados diferente.

No Visual Studio, abra o Package Manager Console e execute o comando para aplicar as migrações do banco de dados:
bash
Copiar
Editar
Update-Database
Passo 3: Executar o Aplicativo
Agora você pode rodar o aplicativo. No Visual Studio, pressione Ctrl + F5 ou clique em Iniciar sem depuração para rodar a aplicação.

Passo 4: Interagir com a Interface
Ao iniciar o aplicativo, você verá a tela principal com as tarefas listadas.
Para adicionar uma tarefa, clique no botão Adicionar Tarefa, insira o nome e a descrição da tarefa e clique em Salvar.
Para editar uma tarefa, clique em Editar ao lado da tarefa que deseja modificar.
Para excluir uma tarefa, clique no ícone de lixeira ao lado da tarefa.
Passo 5: Testar Funcionalidades
Adicionar uma nova tarefa: Clique em Adicionar Tarefa, insira as informações e clique em Salvar.
Editar uma tarefa: Clique em Editar e faça as alterações que desejar.
Excluir uma tarefa: Clique no ícone de lixeira e confirme a exclusão.
Passo 6: Verificação no Banco de Dados
Você pode verificar se as tarefas foram realmente salvas no banco de dados acessando o SQL Server Management Studio (SSMS) e rodando a seguinte consulta SQL:

sql
Copiar
Editar
SELECT * FROM Tasks;
Passo 7: Finalizar
Quando terminar de usar o aplicativo, basta fechar a janela do programa. As tarefas que você adicionou ou alterou serão mantidas no banco de dados.
## Como Usar
1. Abra o aplicativo e faça login.
2. Adicione uma nova tarefa clicando em "Adicionar Tarefa".
3. Edite ou exclua as tarefas conforme necessário.
## Contribuição
1. Faça um fork do repositório.
2. Crie uma nova branch (`git checkout -b feature/nova-feature`).
3. Faça as alterações e commit (`git commit -am 'Adiciona nova feature'`).
4. Envie para o repositório remoto (`git push origin feature/nova-feature`).
5. Abra um pull request.
