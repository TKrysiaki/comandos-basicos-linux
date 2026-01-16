# 🐧 Comandos Linux — Terminal

## O que é um comando
- Comando = texto digitado no terminal que executa uma ação no sistema.

---

## Mudar diretório — `cd`

```bash
cd Documentos
cd ..
cd ~
```
## Listar arquivos - `ls`
```ls
ls -l
ls -a
ls -la
ls -lh
ls -ltr
```
## Criar arquivo - `touch`
```touch teste.txt
```
## Verconteúdo - `cat`
```cat arquivo.txt
cat arquivo1.txt arquivo2.txt
cat arquivo1.txt arquivo2.txt > arquivo3.txt
cat > nome.txt
```
## Criar pastas - `mkdir`
```mkdir pasta
mkdir dir1 dir2 dir3
mkdir -p dir3/projetos/linux/aula1
```
## Remover arquivos e pastas - `rm`
```rm arquivo.txt
rm -i arquivo.txt
rm -rf pasta
rm -d pasta
rmdir pasta
```
## Copiar arquivos - `cp`
```cp arquivo1.txt arquivo2.txt
cp -r dir1 dir2
cp arquivo1.txt dir1
cp -r 10 20
```
## Mover ou remover - `mv`
```mv teste.txt teste1.txt
mv arquivo.txt /home/tiago/destino
mv dir1/* dir3/
mv dir1 dir2
```
## Atualizar repositórios
```sudo apt-get update
```
## Atualizar pactoes
```sudo apt-get upgrade
```
## Instalar pacote
```sudo apt-get install nome-do-pacote
```
## Remover pacote
```sudo apt-get purge nome-do-pacote
```
