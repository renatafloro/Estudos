echo "# capgimeni" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/instrutorvilson/capgimeni.git

git push -u origin main



gerar chave ssh
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-

ssh-keygen -t ed25519 -C "instrutorvilson@github.com"

No github, conecta com o usuario, seleciona settings -> generate chave ssh.

===nosso dia a dia====
git status -> verificar o status(o que está sendo rastreado)
git add . -> adicionar alteração no arquivo ao rastreio(stage)
git commit -m "xxxx" -> messagem para documentar o que foi feito
git push -u origin main -> sincroniza com repositório remoto
# capgimeni
