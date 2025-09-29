# Vá até a pasta extraída
cd "C:/Users/SeuNome/Documents/trabalho01"

# Inicializa o git
git init

# Conecta com o repositório do GitHub
git remote add origin https://github.com/SEU-USUARIO/trabalho01.git

# Adiciona os arquivos
git add .

# Cria o primeiro commit
git commit -m "Primeira versão do trabalho01"

# Envia para o GitHub
git branch -M main
git push -u origin main
