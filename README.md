# MarkDown para Devs 🧑‍💻

Tutorial de notação markdown para desenvolvedores contendo dicas e exemplos, para uso na documentação de software.

## **Índice**
<ol>
  <li><a href="#basico">MarkDown Básico</a></li>
  <li><a href="#diretorios">Gerando estrutura de diretórios de seus projetos para markdown</a></li>
  <li><a href="#links">Links Úteis</a></li>
</ol>

<a id="basico"> <h2> 1 - MarkDown Básico </h2></a>


<a id="diretorios"> <h2> 2 - Gerando estrutura de diretórios de seus projetos para markdown ( Windows e Linux ) </h2></a>

<ol>
  <li>Acesse seu <b>terminal do linux ou o Prompt do Windows</b></li>
  <li>Navegue até o <b>diretório que deseja montar a arvore</b> do mesmo</li>
  <li>No prompt ou terminal dentro do diretório selecionado <b>digite</b> $ <i><b>tree</b></i> </li>
  <li>logo abaixo seram listados toda estrutura de pastas e arquivos do diretório selecionado</li>
  <li>Copie essa estrutura de texto das pastas e arquivos gerada</li>
  <li>Agora faça como na estrutura abaixo( abra e feche com crase e coloque o tipo de código que sera mostrado na frente ex: shell )</li>
</ol>

`````markdown
```shell
  .
  ├── lib
  │   └── blackjack.ex
  ├── mix.exs
  ├── README.md
  └── test
      ├── blackjack_test.exs
      └── test_helper.exs
```
`````

Ficará assim : 
```shell
  .
  ├── domain
  │   └── blackjack.ex
  ├── mix.exs
  ├── README.md
  └── test
      ├── blackjack_test.exs
      └── test_helper.exs
```
### 🗔 - Dicas do Comando **tree** no Windows
```shell

# Exemplos de Uso do comando tree no Windows 
$ tree \               # Exibe todos os subdiretórios no disco na unidade atual
$ tree c:\ /f | more   # Exibe uma tela de cada vez, os arquivos em todos os diretórios na unidade C ou unidade desejada
$ tree c:\ /f > <driveletter>:\<filepath>\filename.txt # Para imprimir uma lista de todos os diretórios na unidade C em um arquivo
```

### 🐧- Dicas do Comando **tree** no Linux
```shell

# Caso não tenha no linux o comando tree vc pode instala-lo 
$ sudo pacman -S tree        # Arch Linux
$ yum install -y tree        # Centos e Fedora
$ sudo apt-get install tree  # Ubuntu  

# Exemplos de Uso do comando tree no linux 
$ tree        # Mostra os diretórios e arquivos.
$ tree -d     # Mostra somente os diretórios.
$ tree -L X   # Mostra até X diretórios de profundidade.
$ tree -f     # Mostra os arquivos com sua respectiva rota.
$ tree -a     # Mostra todos os arquivos incluindo os ocultos.
$ tree /      # Mostra a arvore de todo o nosso sistema.
$ tree -ugh   # Mostra os arquivos com seu respectivo proprietário (-u), o grupo (-g) e o tamanho de cada arquivo (-h).
$ tree -H . -o seudiretorio.html  # Exporta sua arvore de diretórios para uma arquivo HTML.

```

<a id="links"> <h2>🔗 Links Úteis</h2></a>
* [Emojis para MarkDown](https://emojipedia.org/)
* [Linguist - Arquivo de linguagens e cores dos realces de código do markdown para github](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml)
* [MarkDown Guide](https://www.markdownguide.org/)
