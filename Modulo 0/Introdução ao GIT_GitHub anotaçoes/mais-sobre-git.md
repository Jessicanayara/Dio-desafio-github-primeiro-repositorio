### **CONFIGURAR** 

**git config --global user.name “[nome]”**

Este comando define o nome de usuário, o que ajuda a revisar por quem as alterações foram feitas. 

**git config --global user.email “[endereço de e-mail]”**

Este comando define um endereço de e-mail, este por sua vez ajuda a rastrear por quem a atividade de commit ou merge foi feita.

**git config --global color.ui auto**

Este comando define um efeito de coloração de linha de comando automático para facilitar a revisão. 

### **CRIAR E INICIALIZAR** 

**git init**

Este comando inicializa o diretório existente como um repositório git

**git init [nome do repositório]**

Este comando é usado para criar ou iniciar um novo repositório git.

**git clone [url]**

Este comando é usado para obter todo o repositório ou baixar o código-fonte existente da URL fornecida. Basicamente faz uma cópia idêntica da última versão do repositório no sistema local.

### **PREPARAÇÃO E COMPROMISSO**

**git add [arquivo]**

Este comando adiciona um arquivo da árvore de trabalho à área Staging/ramificação atual.

**git add \***

Este comando adiciona um ou mais arquivos da árvore de trabalho à área Staging/ramificação atual.

**git add.**

Prepara todos os arquivos em todo o repositório para a área Staging/ramificação atual.

**git rm [arquivo]**

Este comando exclui o arquivo existente do seu diretório de trabalho.

**status do git**

Este comando lista todos os arquivos que devem ser confirmados.

**git diff** 

Este comando mostra o conteúdo alterado que não é preparado.

**git diff --staged** 

Este comando mostra o conteúdo alterado que é testado, mas não confirmado.

**git commit -m “[mensagem de commit]”**

Este comando registra ou captura as alterações permanentemente no histórico de versões do repositório.

**git commit -a**

Este comando confirma todos os arquivos modificados ou criados no repositório.

**git reset [arquivo]**

Este comando desmonta um arquivo sem nenhuma alteração no diretório de trabalho.

**git reset [commit]**

Este comando desfaz todos os commits após o commit específico mencionado e preserva as alterações localmente.

**git reset --hard [commit]**

Este comando descarta todo o histórico e volta para o commit específico mencionado.

### **FILIAL E FUSÃO**

**git branch**

Este comando lista as ramificações disponíveis no repositório.

**git branch [nome do branch]**

Este comando cria uma nova ramificação.

**git branch -d [nome do branch]**

Este comando exclui a ramificação do recurso.

**git checkout [nome da filial]**

Este comando é usado para fazer check-out para a ramificação especificada.

**git checkout -b [nome da filial]**

Este comando cria uma nova ramificação e, em seguida, faz check-out na mesma.

**git merge [nome da filial]**

Este comando mescla ramificações especificadas com a ramificação atual.

### **LOGS E REVISÃO**

**git log**

Este comando é usado para listar o histórico de versões do branch atual.

**git log -follow [arquivo]**

Este comando mostra particularmente as versões do arquivo mencionado.

**git show [commit]**

Este comando mostra a mudança de conteúdo e o status de metadados do commit específico. 

### **ATUALIZAÇÃO REMOTA E COMPARTILHAMENTO**

**git remote add [nome da variável] [URL]**

Este comando é usado para conectar seu repositório local ao servidor remoto.

**git push [nome da variável] [nome da filial]**

Este comando envia os commits do branch para o seu servidor remoto

**git push --set-upstream [nome da variável] [nome da filial]**

***ou\*** 

**git push -u origin [nome da filial]**

Se a ramificação for recém-criada, podemos fazer o upload com o comando acima 

**git push [nome da variável] master**

Este comando envia as alterações confirmadas do branch master para seu repositório remoto.

**git push -all [nome da variável]**

Este comando envia todas as ramificações para seu repositório remoto.

**git pull [link do repositório]**

Este comando busca e mescla as alterações no servidor remoto para seu diretório de trabalho. 
