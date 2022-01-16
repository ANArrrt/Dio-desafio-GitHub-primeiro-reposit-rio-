## Introdução ao Git e GitHub - Básico:desktop_computer:

**Passo a passo**:

- git init (Iniciar repositório)
- git add (Mover arquivos e versionamento)
- git commit (Criação do commit)



**Criação do repositório:**

- Criação da pasta no drive C:
- Abrir GIt Bash direto no repositório do drive C:

**Comandos:**

- _ls_ (Para listagem de itens na pasta C:)
- _cd_ (espaço + _nome da pasta criada_)_/_ ... Enter
- _mkdir_ (espaço + nome da pasta que deseja criar, caso necessário) ... Enter
- _ls_ (Para listar e conferir a pasta criada)... Enter
- _cd_ (+ _nome da pasta criada_)_/_ (Para entrar de fato na pasta)... Enter



**Git init dentro da pasta:** (Direcionamento e versionamento do código)

- _git init_ ... Enter (Mensagem: "Initialized empty Git repository in ...")



**Adicionando um arquivo para a pasta** (.md ou .txt)

- Criar o arquivo pelo próprio sistema operacional, dentro da pasta.
- Editar o arquivo como desejar e salvar. (Dica: No caso de .md, use a "Ajuda - Markdown reference" para formatar melhor o seu texto)



**Commitando a pasta**

- _git add *_ ... Enter
- _git commit - m "commit inicial"_ ... Enter
- Mensagem com o pequeno sha1 e commmit.



**Aplicando mais arquivos na pasta**

- _mk dir (+ nome da pasta_) (Para criar outra pasta dentro da pasta).. Enter
- _mv (+ o arquivo criado) ./(nova pasta)/_ ... Enter (Mover para a nova pasta)



**Movendo do Staged e Commitando a nova pasta e arquivo**

- _git add (+ nome do arquivo e nova pasta/)_... Enter
- _gir commit - m "cria pasta (nome da pasta nova, move arquivo para (nome da pasta nova))"_... Enter
- _git status_ (Para conferir a árvore)



**Criando um indexador**

- _echo > README.md_... Enter
- Abrir o Arquivo README.md e editar a Capa!. Salvar!
- _git add *_ ... Enter
- _git commit - m "adiciona index"_ .. Enter



**Repositório local para repositório remoto**

- _git remote add origin (+ link do GitHub de novo repositório)_ ...Enter
- _git status_ (Certificação de repositório sem pendências).
- _git push origin master_ ... Enter
- Mensagem de confirmação do envio!
