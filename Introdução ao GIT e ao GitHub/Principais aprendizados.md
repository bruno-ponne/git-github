# Introdução ao GIT e GitHub


### GIT

Sistema de versionamento distribuído para controle das versões de determinado código em um projeto. Desse modo, permite que o projeto seja desenvolvido por vários programadores ao mesmo tempo.

- pode ser utilizado via GUI (Graphical User Interface) ou CLI (command-line interface);
- SHA1 (secure hash algorithm) é um conjunto de funções criptográficas utilizado pelo GIT para representar cada arquivo;
- 3 objetos do GIT
  - Blob (bolha): guarda os arquivos e seus metadados;
  - Tree: armazena e aponta para blobs assim como guarda seus nomes. Tem seu próprio SHA1;
  - Commit: aponta para uma Tree, para um commit anterior, possui SHA1 próprio e contém mensagem descritiva. Ele também informa quem fez o commit e quando este foi feito.
- Estados que um arquivo pode assumir dentro do fluxo GIT:
  - untracked: arquivo ainda não adicionado, arquivo novo;
  - unmodified: arquivo que já sofreu commit;
  - modified: arquivo modificado;
  - staged: arquivo que sofreu add
- Ambiente de desenvolvimento Local: Working Directory (add)---> Staging Area (commit)---> Local Repository
- Local Repo comunica-se ao Remote Repo (GitHub) via comandos de pull e push



### GitHub

Plataforma que serve como repositório para códigos e integra-se ao GIT.

- Clone: processo de baixar o conteúdo de um repositório para fazer uma contribuição;
- Conflito: duas versões de um código são modificadas na mesma linha.
- Resolução do conflito: 
  - pull da versão mais recente;
  - resolução do conflito manualmente;
  - push da resolução para o GitHub.
- Branch: é uma espécie de cópia do código original (default branch/main) que serve para isolar o desenvolvimento de uma feature do restante das branches de um repositório. Cada repositório tem sua branch default e pode ter múltiplas branches adicionais.
- Quando o desenvolvimento em uma branch secundária é concluído, ela pode sofrer merge com a branch default para atualizá-la.
- Fork: é uma cópia de um repositório que você gerencia. Um *fork* permite que você altere um projeto sem afetar o repositório original. Você pode também baixar *updates* do original ou fazer uma solicitação para mandar atualizações ao repositório original por uma *pull request*. Um fork inclui todas as branches presentes no projeto no momento do fork.






