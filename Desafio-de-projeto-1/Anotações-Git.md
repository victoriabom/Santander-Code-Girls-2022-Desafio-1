# Anotações sobre Git

##### Git

- Git é uma CLI (_Command Line Interface_), que é uma interface baseada em apenas textos;

- Foi criado em 2005, por Linus Torvalds (_criador do Linux_);

- É um sistema de versionamento de código distribuído, que é uma estratégia para gerenciar diferentes versões de um código.  

##### Markdown

- É uma forma mais humana de escrever html;

- Sintaxe padronizada para facilitar formatação de texto.

##### SHA1

- A sigla SHA (_Secure Hash Algorith_) significa Algoritmo de Segurança de Hash, que é um conjunto de funções hash criptográficas, projetadas pela NSA (_Agência de Segurança Nacional dos EUA_);

- Sua criptografia contem 40 caracteres;

- É uma forma curta de representar um arquivo.

##### Objetos Internos

1. ###### **Blob** (_bolha_)
- Os arquivos ficam guardados no blob; 

- Contem metadados;

- Mostra o tipo do objeto, seu tamanho, \0 e conteúdo do arquivo.
2. ###### **Tree** (_árvore_)
- Armazenam blobs;

- É uma estrutura de localização;

- Mostra o blob, \0, tamanho e nome do arquivo.
3. ###### **Commit**
- Captura e salva o estado do projeto naquele momento, podendo ser movido para o repositório remoto mais tarde;

- Possui timestamp (_data e hora da criação_);

- Mostra a tree, o parente (_último commit realizado_), o autor, a mensagem e o tamanho do arquivo.

##### Chave SSH

- É uma forma de estabelecer uma conexão segura e encriptada entre duas máquinas;

- Possui a chave pública e a chave privada.

##### Estados dos arquivos

- Tracked: Foi pré-salvo e adicionado ao servidor local, o Git sabe de sua existência.
- Untracked: Não foi pré-salvo e nem adicionado ao servidor local, o Git não sabe de sua existência.
- Modified: Arquivo que foi modificado e precisa ser pré-salvo novamente.
- Unmodified: Arquivo que não foi modificado desde o último commit.
- Staged: Arquivo que foi pré-salvo e está em espera para o commit, que é o save local.

##### Comandos básicos

- cd: navega entre os diretórios;

- cd ..: volta um nível de diretório;

- ls: mostra diretórios;

- mkdir: cria diretório;

- clear: limpa o terminal;

- echo: copia a frase entre aspas;

- rm -rf: deleta o diretório;

- cat: permite visualizar o que tem dentro do arquivo;

- pwd: mostra o caminho completo até a pasta ou arquivo que você está;

- git init: cria-se um novo repositório;

- git add: coloca os arquivos em estado de staged;

- git commit: salva a última versão dos arquivos no servidor local;

- git config: configurações do git;

- git push: envia do servidor local para o servidor remoto;

- git pull: puxa do servidor remoto para o servidor local;

- git status: mostra o status dos arquivos;

- git clone: usado para clonar um repositório remoto para o repositório local, usado através de um link.

##### Links úteis

[Download Git](https://git-scm.com/)

[Comandos básicos Git](https://www.hostinger.com.br/tutoriais/comandos-basicos-de-git?ppc_campaign=google_performance_max&gclid=CjwKCAjw_b6WBhAQEiwAp4HyIEyvkHEuafdSVldtqnqaSqcxieCEqb6WvJ27AwCbweS8PNKGMjye0xoCnJ8QAvD_BwE)

[Download de um editor de Markdown recomendado](https://apps.microsoft.com/store/detail/markdown-editor-free/9PKFLMLPCW3C?hl=pt-br&gl=BR)

[Sintaxe básica do Markdown](https://www.markdownguide.org/basic-syntax/)


