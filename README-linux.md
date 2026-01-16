# 🐧 Comandos Linux — Terminal

## ❓ O que é um comando
- Comando = texto digitado no terminal que executa uma ação no sistema.

---

## 📁 Mudar diretório — `cd`

```bash
cd Documentos        # entra no diretório "Documentos"
cd ..                # volta ao diretório anterior
cd ~                 # vai para o diretório inicial (home)
```
## 📄 Listar arquivos — `ls`
```ls -l                # detalhamento de itens no diretório
ls -a                # mostra arquivos ocultos
ls -la               # combina parâmetros
ls -lh               # tamanho legível para humanos
ls -ltr              # ordenado por data de modificação
```
## Criar arquivo - `touch`
```touch teste.txt (Cria arquivos)``` 
## Ver conteúdo - `cat`
```cat arquivo.txt (mostra o conteúdo do arquivo)
cat arquivo1.txt arquivo2.txt (mostra o conteudo dos 2 arquivos)
cat arquivo1.txt arquivo2.txt > arquivo3.txt (junta 2 arquivos em 1)
cat > nome.txt (permite digitar conteúdo no arquivo) "Use Ctrl + C para cancelar"
```
## Criar diretórios - `mkdir`
```mkdir arquivo (cria um diretório)
mkdir dir1 dir2 dir3 (cria vários diretórios)
mkdir -p dir3/projetos/linux/aula1 (cria toda a estrutura de pastas de uma vez)
```
## Remover arquivos e pastas - `rm`
```rm arquivo.txt (remove o arquivo)
rm -i arquivo.txt (confirma a ação)
rm -rf pasta (remove diretórios) "COM CUIDADO"
rm -d pasta (remove diretórios vazios)
rmdir arquivo (remove arquivo)
```
## Copiar arquivos - `cp`
```cp arquivo1.txt arquivo2.txt (copia o aquivo 1 para o arquivo 2)
cp -r dir1 dir2 (Copia arquivos do dir1 para o dir2)
cp arquivo1.txt dir1 (copia o arquivo1 para o dir1)
cp -r 10 20 (Copia diretorio e arquivos de 10 pra 20)
```
## Mover ou remover - `mv`
```mv teste.txt teste1.txt (Copia o conteudo do test.txt para test1.txt e exclui arquivo test.txt)
mv arquivo.txt /home/tiago/destino (move o arquivo selecionado para a pasta destino)
mv dir1/* dir3/ (move tudo do dir1 para o dir3)
mv dir1 dir2 (Muda nome do diretório)
```
## Atualizar repositórios
```sudo apt-get update```
## Atualizar pactoes
```sudo apt-get upgrade```
## Instalar pacote
```sudo apt-get install nome-do-pacote```
## Remover pacote
```sudo apt-get purge nome-do-pacote```
# 🐧 Comandos Linux — Terminal

## ❓ O que é um comando
- Comando = texto digitado no terminal que executa uma ação no sistema.

---

## 📁 Mudar diretório — `cd`

```bash
cd Documentos        # entra no diretório "Documentos"
cd ..                # volta ao diretório anterior
cd ~                 # vai para o diretório inicial (home)

