Documentação da atividade Git


Objetivo


Praticar o uso de branches e commits semânticos com o Git.

Comandos utilizados

git init: inicializa um repositório Git.


git branch: lista as branches existentes.


git branch -M main: define o nome da branch principal.


git switch -c desenvolvimento: cria e acessa uma nova branch.


git add: prepara arquivos para o commit.


git commit -m: registra alterações com uma mensagem.


git switch main: alterna para a branch principal.


git merge desenvolvimento: integra as alterações à branch atual.


git log --oneline --graph --all: mostra o histórico de commits e branches.


git status: verifica a situação dos arquivos.



Commits semânticos

Foram utilizados os prefixos docs, para documentação, e feat, para adicionar conteúdo ou funcionalidade.

Aprendizados

Aprendi a criar branches para desenvolver alterações separadamente, registrar mudanças com commits 
semânticos e integrar o trabalho à branch principal. Também compreendi como o histórico do Git 
ajuda a organizar e acompanhar a evolução de um projeto.

Histórico dos comandos executados



1. Preparação do repositório


cd %USERPROFILE%\Desktop\teste-git — acessa a pasta do projeto.


git init — inicializa o repositório Git.


git branch -M main — define o nome da branch principal como main.

2. Criação dos primeiros 

commits

git add README.md — prepara o arquivo para ser registrado.


git commit -m "docs: adicionar descrição do projeto" — registra a descrição inicial.


git switch -c desenvolvimento — cria e acessa a branch desenvolvimento.


git commit -m "feat: adicionar tecnologias utilizadas" — registra a inclusão das tecnologias.


git commit -m "docs: registrar aprendizados sobre Git" — registra os aprendizados.

3. Integração das alterações



git switch main — retorna à branch principal.


git merge desenvolvimento — integra as alterações da branch de desenvolvimento à principal.


git commit -m "docs: documentar comandos e aprendizados" — registra a documentação da atividade.

4. Publicação no GitHub

git 

remote add origin https://github.com/FlaviaFigueiredo86/teste-git.
git — conecta o repositório local ao GitHub.


git push -u origin main — publica a branch principal.


git push -u origin desenvolvimento — publica a branch de desenvolvimento.



5. Verificação do projeto



git status — verifica se existem alterações pendentes.


git log --oneline --graph --all — exibe o histórico de commits e branches.


git remote -v — mostra o endereço do repositório remoto.


dir — lista os arquivos da pasta no Windows.

Conclusão



A atividade permitiu praticar a criação de um repositório, o uso de branches, a realização de commits
 semânticos, a integração de alterações e a publicação do projeto no GitHub. Essas práticas ajudam a 
organizar o histórico e facilitam o trabalho em equipe.
