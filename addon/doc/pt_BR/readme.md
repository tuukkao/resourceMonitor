# Monitor de recursos #

* Autores: Alex Hall, Joseph Lee, beqa gozalishvili e outros colaboradores
  do NVDA
* Baixe a [versão estável][1]

Este plug-in fornece informações acerca de carga da CPU, uso de memória e
outras informações sobre uso de recursos.

# Atalhos #

* NVDA+Shift+E mostra uso da RAM, carga média do processador e informações
  de bateria caso disponíveis.
* NVDA+Shift+1 Mostra a carga média do processador e caso se tratem de CPUs
  multinúcleo mostra a carga de cada núcleo.
* NVDA+Shift+2/5 Mostra espaço usado e total das memórias RAM física e
  virtual.
* NVDA+Shift+3 Mostra espaço usado e o total das unidades fixas e
  removíveis.
* NVDA+Shift+4 Mostra porcentagem da bateria, status de carga, tempo
  restante (se não estiver carregando) e alerta caso a bateria esteja baixa
  ou crítica.
* NVDA+Shift+6 apresenta arquitetura da CPU (32/64-bit) e a versão de
  Windows com números do service pack.

Caso possua instalado o NVDA 2013.3 ou mais novo, pode alterar essas teclas
de atalho.

## Notas de uso ##

Este complemento não substitui o gerenciador de tarefas e outros programas
de informações de sistema para Windows. Note também o seguinte:

* O uso de CPU é fornecido em processadores lógicos e não em núcleos
  físicos. Nota-se isso em processadores que usam Hyper-Threading, em que o
  número de CPUs é o dobro do número de núcleos de CPU.
* If there is heavy disk activity such as copying large files, there might
  be delays when obtaining disk usage information.

## Version 17.02

* Updated psutil dependency to 5.0.1.
* When checking disk usage, NVDA will no longer present an error dialog on
  some systems where a removable media is not properly recognized (such as
  when a card isn't inserted into a card reader).)

## Version 16.08

Starting with version 16.08, add-on releases will be shown as
year.month.revision.

* Various revisions of Windows 10 are now properly recognized (such as 1607
  for build 14393).
* Windows 10 build revisions (after installing cumulative updates) are
  properly recognized (such as 14393.51).
* If using Insider Preview builds, this fact is recognized.

## Changes for 4.5 ##

* Add-on repository has moved to GitHub (can be found at
  https://github.com/josephsl/resourcemonitor).
* Windows Server 2016 is properly recognized.

## Mudanças na 4.0 ##

* Atualizada dependência psutil para 2.2.1.
* Aprimorado largamente o desempenho ao obter informações de carga da CPU.
* Adicionado suporte ao reconhecimento de Windows 10.
* No Windows 10, o número de compilação também será anunciado.
* Você pode usar o gestor de complementos para acessar a ajuda do
  complemento.

## Mudanças na 3.1 ##

* O Monitor de Recursos suporta oficialmente Windows 8.1.
* Atualizadas traduções.

## Mudanças na 3.0 ##

* Atualizada dependência psutil para 1.2.1.
* Anunciar versão atual de Windows, arquitetura da CPU e service pack se
  houver (NVDA+Shift+6).
* Capacidade de alterar as teclas de atalho do complemento (NVDA 2.13.3 ou
  superior).
* Capacidade de copiar as informações dum recurso individual para a área de
  transferência pressionando duas vezes o comando do recurso.

## Mudanças na 2.4 ##

* Novos idiomas: Chinês (simplificado), Ucraniano.
* Atualizadas traduções.

## Mudanças na 2.3 ##

* Adicionada tradução Búlgara.

## Mudanças na 2.2 ##

* Acrescentadas as seguintes traduções: Árabe, Alemão, Aragonês, Coreano,
  Croata, Eslovaco, Esloveno, Espanhol, Finlandês, Francês, Galego,
  Holandês, Húngaro, Japonês, Italiano, Nepalês, Português do Brasil, Russo,
  Tâmil e Turco.

## Mudanças na 2.1 ##

* Atualizada dependência psutil para versão 0.6.1.
* Corrigida lentidão ao obter informações sobre unidades de disco.
* Enxugamento de código.

## Mudanças na 2.0 ##

* Adicionado suporte a traduções e comentários para tradutores.

## Mudanças na 1.0 ##

* Primeira versão

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=rm
