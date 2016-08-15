# finisher.(guru|tech): slides de início dos projetos

## Requisitos

1. Tenha um shell [Bash] para executar o script [build]. Se estiver no Windows, instale o [Cygwin]. Uma forma de fazer isso é seguir os procedimentos descritos em "[Instalação do Cygwin](https://github.com/paulojeronimo/dicas-windows/blob/master/instalacao-cygwin.asciidoc)".
1. Se estiver utilizando o [OS X] e ainda não estiver utilizando o [Homebrew], instale-o.
1. Se não estiver utilizando o [OS X], procure como instalar os softwares a seguir. Caso contrário, o script [build] fará a instalação deles através do [Homebrew].
  1. [asciidoc].
  1. [qrencode].

## Configuração

As configurações de diretórios padrão estão no arquivo [build.conf.sample]. Se desejar alterá-las, copie este arquivo para `build.conf` e edite-o conforme tuas necessidades.

## Geração dos slides

  ./build

## Visualização local dos slides

Execute um servidor HTTP com o comando a seguir:

  ./build server

Abra o teu browser em http://localhost:3000 para ter acesso aos slides.

## Remoção dos slides gerados

  ./build clean

## Aprenda mais ...

Os slides deste repositório foram escritos no [formato AsciiDoc][asciidoc]. Outros bons exemplos de como fazer a escrita de slides nesse formato podem são os seguintes:

1. [Discover the Zen of Writing (Ascii)Docs](http://mojavelinux.github.io/decks/discover-zen-writing-asciidoc/cojugs201305)
1. [Drop the angled brackets. Write (Ascii)Docs with pleasure!](http://mojavelinux.github.io/decks/asciidoc-with-pleasure/rwx2012)

Os fontes desses slides estão em https://github.com/mojavelinux/decks/.

[Bash]: https://www.gnu.org/software/bash/
[Cygwin]: http://cygwin.com
[asciidoc]: http://www.methods.co.nz/asciidoc/
[qrencode]: https://github.com/fukuchi/libqrencode
[Homebrew]: http://brew.sh
[OS X]: http://www.apple.com/br/osx/

[build]: build
[build.conf.sample]: build.conf.sample
