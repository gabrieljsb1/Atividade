EBOOK
1. Download e Instalação do Git
Baixar e instalar: Acesse o site oficial do Git ([git-scm.com/downloads](https://gitscm.com/downloads)), baixe o instalador para Windows e conclua o processo de 
instalação.
Abrir o Git Bash: Inicie o terminal nativo do Git (Git Bash).
Verificar instalação: Execute o comando para conferir se o Git foi instalado 
corretamente:
Bash
git --version
2. Criação do Projeto e Arquivo Inicial
Criar pasta: Crie a pasta projeto-git na Área de Trabalho.
Abrir no VS Code: Abra a pasta criada dentro do Visual Studio Code.
Criar arquivo de introdução: Crie o arquivo README.md e insira uma breve 
descrição sobre o projeto.
3. Primeiro Commit e Gerenciamento do Repositório Local
Abrir Git Bash na pasta: Abra o terminal diretamente na pasta do projeto:
Inicializar o Git: Transforme a pasta em um repositório Git:
Bash
git init
Mover para a Staging Area: Prepara o arquivo README.md para ser commitado:
Bash
git add README.md
Verificar status: Confere o estado dos arquivos:
Bash
git status
Realizar o commit: Salva a primeira versão no repositório local:
Bash
git commit -m "Primeiro commit"
Renomear a branch principal: Altera o nome padrão da branch de master para main:
Bash
git branch -M main
4. Conexão com o GitHub e Primeiro Push
Criar repositório remoto: Acessa o GitHub (github.com), cria um novo repositório 
chamado projeto-git (público) e obtém o link HTTPS.
Vincular o repositório local ao GitHub: Adiciona o repositório remoto apelidado de 
origin:
Bash
git remote add origin https://github.com/seu-usuario/projeto-git.git
Enviar as alterações (Push): Faz o envio dos commits para a branch main do GitHub.
Bash
git push -u origin main
5. Edição, Novos Arquivos e Adição Global
Modificar arquivos: Edita o README.md e crie um novo arquivo chamado 
projeto.md.
Adicionar todos os arquivos de uma vez:
Bash
git add .
Criar novo commit e enviar ao GitHub:
Bash
git commit -m "cria"
git push origin main
6. Trabalhando com Branches e Merge
Criar e mudar de branch: Cria a branch novo-botao e alterna para ela
Bash
git checkout -b novo-botao
Criar arquivo na nova branch: Cria o arquivo botao.md
Commit e push da nova branch:
Bash
git add .
git commit -m "novo botão"
git push origin novo-botao
Voltar para a branch principal:
Bash
git checkout main
Unir as alterações (Merge): Junta o conteúdo da branch novo-botao na branch main
Bash
git merge novo-botao
Atualizar a main no GitHub:
Bash
git push origin main
7. Clonando Repositórios e Atualizando Alterações (git pull)
Copiar link de um repositório: Acessa um repositório no GitHub (git-tutorial) e copia 
a URL para clone.
Clonar o projeto para a máquina:
Bash
git clone <URL_DO_REPOSITORIO>
Atualizar o repositório local (git pull): Após simular uma edição diretamente no 
GitHub, entra na pasta clonada e baixa as atualizações 
Bash
git pull
8. Fork e Pull Request
Fazer Fork: Explica e demonstra como fazer a cópia (Fork) de um repositório de 
outro usuário para o seu próprio perfil do GitHub.
Modificar o repositório forkeado: Faz uma pequena alteração diretamente pelo 
GitHub.
Abrir um Pull Request: Envia uma solicitação de alteração para o dono do repositório 
origina.
Revisar Pull Requests: Mostra na prática a aba de Pull Requests de um repositório 
próprio e como aceitar ou rejeitar contribuições
