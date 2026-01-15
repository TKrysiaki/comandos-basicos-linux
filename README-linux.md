COMANDOS LINUX - TERMINAL
- Comando sequencia de caracteres que executa um ação

*** COMANDO CD - Mudar diretório ***
LS (Lista os itens)
cd Documentos (entra no diretório "Documentos")
cd .. (Volta ao diretório anterior)
cd ~ (diretório inicial)

*** COMANDO LS - Listagem de Itens ***
LS -L | Detalhamento de itens presentes no diretório
LS -A | Mostra arquivos ocultos
LS -LA | Usando 2 parâmetros juntos
LS - LH | Fácil de ver para os humanos
LS - LTR | Listagem ordenada pela data de modificação

*** COMANDO TOUCH ***
TOUCH - Cria arquivos (touch "test.txt")


*** COMANDOS CAT ***
CAT - mostra conteúdo do arquivo (cat arquivo.txt)
cat arquivo.txt arquivo2.txt (mostra o conteudo dos 2 arquivos)
cat arquivo.txt arquivo2.txt > arquivo3.txt (junta 2 arquivos em 1 so)
cat > nome.txt (Habilita digitar informações dentro do aquivo, Ctrol + C cancela)

*** COMANDOS DE HISTÓRICO ***
- Apertando a setinha pra cima 
- Comando "history"
- Ctrol + R (Ctrol + C Cancela comando atual)

*** CRIANDO DIRETÓRIO ***
- MKDIR nome (Cria um diretório (pasta) com nome escolhido
- MKDIR dir1 dir2 dir3 (cria vários diretorios com 1 comando só)
- MKDIR -P dir3/projetos/linus/aula1 (-p cria tudo de uma vez)


*** REMOVER ARQUIVOS ***
rm nome (arquivo a ser removido)
rm -i nome (confirma a ação)
rm -rf nome (remove diretórios) ***PERIGOSO***
rm -d nome (remove diretórios vazios)
rmdir nome (remove arquivo)

*** COMANDOS CP ***
cp arquivo1.txt arquivo2.txt (copia o aquivo 1 para o arquivo 2)
cp -r dir1 dir2 (Copia arquivos do dir1 para o dir2)
cp arquivo1.txt dir1 (copia o arquivo1 para o dir1)
cp -r 10 20 (Copia diretorio e arquivos de 10 pra 20)

*** COMANDO MOVER (RECORTAR) ***
mv test.txt test1.txt (Copia o conteudo do test.txt para test1.txt e exclui arquivo test.txt)
mv arquivo.txt /home/tiago/destino (move o arquivo selecionado para a pasta destino)
mv dir1/* dir3/ (move tudo do dir1 para o dir3)
mv dir1 dir2 (Muda nome do diretorio)


******* ATUALIZANDO REPOSITÓRIOS DE PACOTES ******* 
sudo apt-get update

******* ATUALIZANDO PACOTES / DEPENDÊNCIAS ******* 
sudo apt-get upgrade

******* INSTALANDO UM PACOTE ******* 
sudo apt-get install nome (nome do aplicativo)

******* REMOVENDO UM PACOTE ******* 
sudo apt-get purge nome (nome do aplicatico)




