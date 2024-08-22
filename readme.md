# Repositorio 
- Criado apenas para testar os comandos (pratica)
- Criando para facilitar o acesso aos comandos (teoria)

# Boas praicas commit:
- feat: nova funcionalidade;
- fix: correçao de bugs;
- docs: mudança de documenação;
- style: mudança na formatação (css);
- refactor: melhora a legibilidade do código, sem adicionar funcionalidades nem corrigir bugs (deixar o cod mais limpo);
- test: adição ou correção de testes;
- chore: adiciona novas pastas para organização de build e ferramentas.

# Comandos basicos:
- git init;
- git add nomeDoArquivo.extensao ou git add . 
- git commit -m "msg explicando o commit" --> nao esquecer das boas praticas.
- git branch -M main;
- git remote add origin (linkDoRepositorioDoGitHub);
- git push -u origin main;

# Outros comandos:
- git status; (ver as alterações).
- git branch nomeNovaBranch;
- git checkout nomeDaBranch OU **_codigoDaModificacao_** OU head~N; (mudar de branch)
- git merge nomeDaBranch; (mesclar a branch atual com a escolhida)
- git pull origin nomeDaBranch; (atualizar o repositorio local (da maquina) com o do servidor (github))
- git reset; -> tira do stage.
- git clean -df; -> tirar as modificações.
- git checkout -- .; --> reverter as modficações, usar junto com o de cima.

# Comandos do terminal (auxilia no uso git):
- mkdir nomeDaPasta; -> criar pasta.
- touch nomeDoArquivo.extensao; -> criar arquivo.
- cd nomeDaPasta; ->entar na pasta.
- cd .. ;-> voltar um repositorio(posição).
- ls; -> mostra todos os arquivos dentro da pasta.
- code . ; -> abrir o vs code dentro da pasta.
- git log ou git log --oneline; --> mostrar historicos de commits, o 1º forma geral, o 2º forma resumida. **ATENÇÃO:** na 1º opção,presssiona a tecla 'q' em seguida.
- git diff nomeDoArquivo.extensao; --> mostra as alterações feitas


# Atalhos
- tecla q; -> interrope as açoes do git.
- tecla tab -> em algumas ocasiões ela incrementa/completa o nome.


# Alguns conceitos:
--> main (branch); <br>
--> origin (nome do remote); <br>
--> extensao: .html. css, etc;<br>
--> o . é tudo modificado; <br>
--> stage -> git add; <br>
--> ~N -> quantas versões você quer voltar? **LEMBRANDO:** a main é a principal, voce volta apartir dela.
# Observações

- Depois que você fez o **git push - u origin main** pela primeira vez, nas demais vezes, só digitar **git push**.
- **_codigoDaModificacao_** é dado no **git log** ou na **pagina do historicos de commits**.
- Enquanto tiver no **git checkout head~N** não pode alterar o arquivo.

