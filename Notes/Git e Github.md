### Entendo o Git e sua Importância

Outras pessoas podem ver seu código e lhe auxiliar.  
Você tem varias versões que foram modificadas com o tempo.  



### Navegação via command line interface e instalação

-cd 

-dir ou -ls

-mkdir

-del / dmdir ou -rm -rf


### Entendendo como o Git funciona

**SHA1** - encriptador de segurança, gera chave de 40 dígitos. Muito seguro usado
pelo Git.  
 

### Objetos internos do Git

**Blobs**  
Contem metadados do objeto, guarda o sha1 do arquivo ...  



**Trees**  
Armazena os blobs, contem também metadados, guarda o nome,  
Se algo for mudado no blob, muda toda a estrutura de encriptação.  
Arvore, pode conter outra arvore   



**Commits**

Aponta para as
arvores, contem sha1 também, como o blob e arvores, assim se algo for mudado,
tudo é modificado

Commit, explica o
que é que tem dentro "desse arquivo".  
arvore, parente, autor, a mensagem e até a data de criação ( timestamp).



### Chave SSH

é uma forma de estabelecer uma conexão segura, com o Github, com essas chaves
(publica e privada), o Github autentica que é você mesmo que está acessando e
enviando o codigo ou querendo editar.  



### Token

é uma forma de autenticar também, embora menos segura do que a chave SSH



### Primeiros comandos com GIT

Iniciando o Git

Iniciando
versionamento  
criando um commit  

**Comandos:**  

git init  
git add  
git commit  



### Criando um repositorio



### Repositorio Remoto no Github

git push origin master  
git pull origin master  

git add * ou .  
git  commit -m "mensagem"

git clonar repositorio, colando ctrl+v


