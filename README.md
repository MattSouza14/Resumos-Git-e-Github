
# Resumos sobre Git e GitHub

Repositorio para armazenar resumos sobre o Git e Github

## 📃 Documentação
- [Documentação Git](https://git-scm.com/doc)

## 📚 Resumos
- Iniciando um repositório local:
Git init -> 

O comando "git init" é utilizado para iniciar um repositório Git em um diretório local. Quando executado, ele cria um novo repositório Git vazio no diretório especificado. Esse comando é geralmente o primeiro passo ao começar um novo projeto ou ao adicionar controle de versão a um projeto existente.

- Vinculando o repositório local ao remoto:
Git remote add origin "link do repositório" ->

O comando "git remote add origin" é usado para associar um repositório remoto ao repositório local em um projeto Git. "origin" é um apelido convencional comumente usado para se referir ao repositório remoto principal. Este comando estabelece uma conexão entre o repositório local e o repositório remoto, permitindo que você envie e receba alterações entre eles.

- Clonando um repositório existente:
Git clone "link do repositório" -> 

O comando "git clone" é utilizado para criar uma cópia local de um repositório Git existente. Ao executar "git clone", você especifica a URL do repositório remoto que deseja clonar. O Git então faz uma cópia completa do histórico de versões, dos arquivos e do ramo principal do repositório remoto para o seu diretório local.

- Verificando o status de alterações:
Git status -> 

O comando "git status" é usado para exibir o estado atual do seu repositório Git local. Ao executar "git status", você recebe informações sobre arquivos que foram modificados, adicionados ou removidos no seu diretório de trabalho. O comando também informa sobre alterações que estão prontas para serem confirmadas (staged) e se há diferenças entre o seu branch local e o branch remoto.

-  Registrar as alterações feitas.
Git commit -m "MENSAGEM" ->

O comando "git commit" é utilizado no Git para registrar as alterações feitas nos arquivos que foram previamente adicionados ao índice (staged). Ele cria um novo commit no repositório com as alterações realizadas desde o último commit.
-m: É uma opção para adicionar uma mensagem de commit diretamente na linha de comando.

- Branch:
No Git, uma branch é uma linha de desenvolvimento independente. Ela permite que você trabalhe em funcionalidades específicas do projeto sem afetar o código principal (normalmente chamado de branch "master" ou "main").

#### Git branch: Lista todas as branches locais.
#### Git branch <Nome> :  Cria uma nova branch.
#### Git checkout <branch>: Muda para uma branch específica.
#### Git merge <branch>: Mescla as alterações de uma branch para a branch atual.

- Atualiza o repositório local com as alterações do repositório remoto:
Git pull -> 

O comando git pull é usado para buscar e integrar as alterações de um repositório remoto para o seu repositório local.

- Enviar as alterações locais para o repositório remoto.
Git push ->

O comando git push é usado para enviar as alterações locais do seu repositório Git para um repositório remoto. Ele é fundamental para colaboração e compartilhamento de código entre desenvolvedores.





