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
```
ls -l                # detalhamento de itens no diretório
ls -a                # mostra arquivos ocultos
ls -la               # combina parâmetros
ls -lh               # tamanho legível para humanos
ls -ltr              # ordenado por data de modificação
```
## Criar arquivo - `touch`
```touch teste.txt      # cria o arquivo teste.txt``` 
## Ver conteúdo - `cat`
```
cat arquivo.txt                          # mostra conteúdo do arquivo
cat arquivo1.txt arquivo2.txt            # mostra conteúdo de 2 arquivos
cat arquivo1.txt arquivo2.txt > novo.txt # junta 2 arquivos em 1
cat > nome.txt                           # digitar conteúdo (Ctrl + C para sair)

```
## Criar diretórios - `mkdir`
```
mkdir pasta                               # cria uma pasta
mkdir dir1 dir2 dir3                      # cria várias pastas
mkdir -p dir3/projetos/linux/aula1        # cria toda a estrutura de uma vez

```
## Remover arquivos e pastas - `rm`
```
rm arquivo.txt        # remove arquivo
rm -i arquivo.txt     # confirma antes de remover
rm -rf pasta          # remove diretórios e tudo dentro (CUIDADO)
rm -d pasta           # remove diretórios vazios
rmdir pasta           # remove diretório vazio

```
## Copiar arquivos - `cp`
```
cp arquivo1.txt arquivo2.txt   # copia arquivo1 para arquivo2
cp -r dir1 dir2                # copia pasta dir1 para dir2
cp arquivo1.txt dir1           # copia arquivo para pasta
cp -r 10 20                    # copia diretório 10 para 20
```
## Mover ou remover - `mv`
```
mv teste.txt teste1.txt                 # renomeia arquivo
mv arquivo.txt /home/tiago/destino      # move arquivo para outra pasta
mv dir1/* dir3/                         # move tudo de dir1 para dir3
mv dir1 dir2                            # renomeia diretório
```
## Atualizar repositórios
```sudo apt-get update```
## Atualizar pactoes
```sudo apt-get upgrade```
## Instalar pacote
```sudo apt-get install nome-do-pacote```
## Remover pacote
```sudo apt-get purge nome-do-pacote```

