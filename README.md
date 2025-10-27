📦 1. Criar um novo repositório

No terminal:

git init


Isso cria uma pasta .git escondida — o “cérebro” do seu controle de versão.

📁 2. Adicionar arquivos
git add .


O add envia seus arquivos para a área de stage, ou seja, estão prontos para o commit.

🧱 3. Criar um commit (salvar uma versão)
git commit -m "Primeiro commit"


Agora o Git salva um ponto de restauração com essa mensagem.

💡 Dica: cada commit deve ter uma mensagem clara, como:

git commit -m "Adiciona seção de login ao site"

🔍 4. Ver o histórico de commits
git log --oneline (PARA SAIR DO PAGINADOR APERTE A TECLA "Q")


Mostra os commits já feitos e seus códigos de identificação.