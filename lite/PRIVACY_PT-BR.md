---
layout: lite
---

# Política de privacidade do sCollectPlay e do sCollectPlay Lite

Atualizado em: 2026-10-22

## Resumo

O sCollectPlay e o sCollectPlay Lite **não** coletam, não armazenam e não transmitem dados
pessoais. Os apps trabalham exclusivamente no seu Mac ou PC com Windows. Não há contas, não há conexão com a
nuvem, não há serviços de análise e não há publicidade.

## Quais dados o app processa

O app lê os arquivos de mídia nas pastas que você entregou a ele expressamente —
escolhendo-as na janela de abertura: uma pasta para escanear, um XML do iTunes ou do Apple
Music ou uma biblioteca do sCollect. São lidos o nome do arquivo, o tamanho do arquivo, a
data e os metadados do arquivo e, no caso de um XML ou de uma biblioteca, também os dados de
catálogo deles.

Sem a sua escolha o app não acessa arquivo algum. O macOS impõe isso pelo sandbox do app.

## O que o app guarda no seu Mac

- **Configurações e posições das janelas** na pasta protegida do app.
- **A permissão do macOS para reabrir as suas pastas na próxima inicialização.** São
  armazenados os caminhos das pastas, não o conteúdo dos arquivos. Só assim o app não
  precisa perguntar de novo a cada inicialização.
- **No sCollectPlay, além disso:** a lista das pastas, dos arquivos XML e das bibliotecas
  usados recentemente, as suas próprias playlists, a ordenação e o estado do navegador de
  colunas — também na pasta protegida do app.

Tudo isso é removido quando você apaga o app.

## Duas permissões que podem levantar perguntas

**Acesso à rede.** O app a solicita porque, sem essa permissão, o macOS mostra vazia a
janela de ajuda integrada — a ajuda é exibida por um componente do sistema que precisa dela,
mesmo que carregue apenas arquivos do próprio programa. Por conta própria, o app **não chama
nenhum endereço na internet**, não baixa nada e não relata nada.

Pastas em unidades de rede (SMB, NFS) o app alcança pelo sistema de arquivos do seu Mac, não
por uma conexão própria.

**Controle do Apple Music.** Quando você envia uma seleção ao Apple Music como playlist, o
app abre o Apple Music com uma playlist gerada e, se você quiser, substitui uma de mesmo
nome que já exista lá. Para isso o macOS pede o seu consentimento, e ele é solicitado na
primeira vez. O app não controla outros programas.

## Os seus arquivos

O app não grava tags e não altera os metadados dos seus arquivos.

Só quando você apaga um arquivo expressamente, o app o coloca no Lixo do macOS e o tira da
lista; se ele vier de uma biblioteca do sCollect, o catálogo dela também é ajustado de
acordo. Em unidades sem Lixo, o app pergunta antes se o arquivo deve ser apagado
definitivamente.

## No Windows

As seções acima descrevem o Mac. No Windows, o sCollectPlay e o sCollectPlay Lite guardam o seguinte exclusivamente de
forma local, na pasta de dados do app (`%LOCALAPPDATA%\Packages\<pacote>\LocalState` e `Settings`):

- **Configurações e a posição da janela.**
- **A última fonte escolhida** — pastas escaneadas, um arquivo XML do iTunes ou uma biblioteca do sCollect — e o
  resultado do último escaneamento.
- **A correspondência entre as pastas Mac de uma biblioteca e pastas do seu PC** (apenas caminhos de pastas).
- **No sCollectPlay, além disso:** as suas próprias playlists, a lista das pastas, dos arquivos XML e das
  bibliotecas usados recentemente, a ordenação e o estado do navegador de colunas.
- **Um registro de erros** (`fehler.log`), que fica no seu PC.

Tudo isso é removido quando você desinstala o app.

O app só lê arquivos de mídia e arquivos XML onde você os seleciona; uma biblioteca do sCollect é apenas lida. Ele não
faz conexões de rede próprias, não usa serviços de análise e não exibe publicidade. Arquivos que o Windows não reproduz
sozinho são passados ao programa padrão para esse tipo de arquivo, que você escolhe no Windows.

Se você exportar no sCollectPlay uma playlist para o VLC ou um dispositivo, o app copia os arquivos dela para a
pasta que você escolher. No Windows, ele não exclui arquivos de mídia.

## Microsoft Store

No Windows, a compra (sCollectPlay), o download e as atualizações são feitos pela Microsoft Store; para isso vale a
declaração de privacidade da Microsoft. O sCollectPlay Lite é gratuito e menciona a versão completa.

## Sem repasse, sem análise

Não há publicidade, não há serviços de análise, não há relatórios de falha para terceiros e
não há contas.

## Contato

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
