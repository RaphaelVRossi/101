# Linux 101


## Navegação de pastas

`ls`: Lista arquivos e diretórios.

```shell
ls
pasta1 pasta2 arquivo1.txt image.jpg

ls -l
pasta1
pasta2
arquivo1.txt
image.jpg

ls -la
.arquivo-oculto
pasta1
pasta2

ls -lrta # o ultimo arquivo sempre é o mais atual
.arquivo-oculto
pasta1
pasta2
```

`cd`: Permite navegar entre diretórios.

```shell
cd pasta1
ls
arquivo2.txt
```

`pwd`: Exibe o diretório de trabalho atual.

```shell
pwd
/home/user/pasta1
```

`mkdir`: Cria um novo diretório.

```shell
mkdir nova_pasta

# Cria varias pastas
mkdir -p nova_pasta/outra_pasta/mais_uma_pasta


```

`rm`: Remove arquivos e diretórios.

```shell
rm arquivo.txt

rm -r pasta1
``` 

`cp`: Copia arquivos e diretórios.

```shell
cp nome.txt nome_copia.txt

cp -r pasta pasta_copia
```

`mv`: Move ou renomeia arquivos e diretórios.

```shell
mv nome_antigo.txt nome_novo.txt
mv pasta_antiga pasta_nova
```



Para ver depois: 
`cat`: Exibe o conteúdo de um arquivo.
`touch`: Cria um arquivo vazio.
`echo`: Exibe texto na tela.
`man`: Exibe o manual de um comando.
`sudo`: Executa um comando com privilégios de superusuário.
`clear`: Limpa a tela do terminal.
`history`: Exibe o histórico de comandos executados.
`df`: Mostra o espaço livre em disco.
`du`: Mostra o uso de espaço em disco.
`top`: Exibe processos em execução.
`ps`: Exibe snapshots de processos.
`kill`: Encerra um processo.
`chmod`: Altera as permissões de acesso a arquivos e diretórios.
`chown`: Altera o proprietário de arquivos e diretórios.
`find`: Localiza arquivos e diretórios.
`grep`: Procura por texto em arquivos.
`tar`: Arquiva e descompacta arquivos.
`gzip`: Comprime arquivos.
`gunzip`: Descomprime arquivos.
`zip`: Cria arquivos zip.
`unzip`: Descompacta arquivos zip.
`wget`: Baixa arquivos da internet.
`curl`: Transfere dados de ou para um servidor.
