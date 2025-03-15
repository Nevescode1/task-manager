# task_manager
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
