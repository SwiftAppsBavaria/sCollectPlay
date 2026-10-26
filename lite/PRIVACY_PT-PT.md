---
layout: lite
---

# Política de privacidade do sCollectPlay e do sCollectPlay Lite

Atualizado a: 2026-10-23

## Em resumo

O sCollectPlay e o sCollectPlay Lite **não** recolhem, não guardam e não transmitem dados
pessoais. As aplicações trabalham exclusivamente no seu Mac ou PC com Windows. Não há contas, não há ligação à
nuvem, não há serviços de análise e não há publicidade.

## Que dados a aplicação processa

A aplicação lê os ficheiros multimédia nas pastas que lhe entregou expressamente —
escolhendo-as na janela de abertura: uma pasta para analisar, um XML do iTunes ou do Apple
Music ou uma biblioteca do sCollect. São lidos o nome do ficheiro, o tamanho do ficheiro, a
data e os metadados do ficheiro e, no caso de um XML ou de uma biblioteca, também as
respetivas indicações de catálogo.

Sem a sua escolha, a aplicação não acede a ficheiro nenhum. O macOS impõe-o através da
sandbox da aplicação.

## O que a aplicação deposita no seu Mac

- **Definições e posições das janelas** na pasta protegida da aplicação.
- **A autorização do macOS para voltar a abrir as suas pastas no arranque seguinte.** São
  guardados os caminhos das pastas, não os conteúdos dos ficheiros. Só assim a aplicação não
  tem de perguntar de novo em cada arranque.
- **No sCollectPlay, adicionalmente:** a lista das pastas, dos ficheiros XML e das
  bibliotecas usados recentemente, as suas próprias playlists, a ordenação e o estado do
  navegador de colunas — também na pasta protegida da aplicação.

Tudo isto é removido quando apagar a aplicação.

## Duas autorizações que podem levantar dúvidas

**Acesso à rede.** A aplicação pede-o porque, sem esta autorização, o macOS mostra vazia a
janela de ajuda integrada — a ajuda é apresentada por um componente do sistema que dela
necessita, mesmo carregando apenas ficheiros do próprio programa. Por iniciativa própria, a
aplicação **não contacta nenhum endereço na internet**, não descarrega nada e não comunica
nada.

As pastas em unidades de rede (SMB, NFS) a aplicação alcança-as através do sistema de
ficheiros do seu Mac, não através de uma ligação própria.

**Controlo do Apple Music.** Quando envia uma seleção para o Apple Music como playlist, a
aplicação abre o Apple Music com uma playlist gerada e, se o desejar, substitui uma com o
mesmo nome que já lá exista. Para isso o macOS pede o seu consentimento, que é solicitado da
primeira vez. A aplicação não controla outros programas.

## Os seus ficheiros

A aplicação não escreve tags nem altera os metadados dos seus ficheiros.

Se abrir uma biblioteca do sCollect, a aplicação guarda as suas classificações e reproduções (com data e hora) no ficheiro `rueckmeldungen.json` da pasta dessa biblioteca, para que o sCollect as possa incorporar. Não altera a biblioteca em si nem os ficheiros multimédia, e nada disto sai do seu computador.

Só quando apaga expressamente um ficheiro é que a aplicação o coloca no Lixo do macOS e o
retira da lista; se provier de uma biblioteca do sCollect, o respetivo catálogo também é
ajustado em conformidade. Em unidades sem Lixo, a aplicação pergunta antes se o ficheiro
deve ser apagado definitivamente.

## No Windows

As secções acima descrevem o Mac. No Windows, o sCollectPlay e o sCollectPlay Lite guardam o seguinte exclusivamente de
forma local, na pasta de dados da aplicação (`%LOCALAPPDATA%\Packages\<pacote>\LocalState` e `Settings`):

- **Definições e a posição da janela.**
- **A última fonte escolhida** — pastas analisadas, um ficheiro XML do iTunes ou uma biblioteca do sCollect — e o
  resultado da última análise.
- **A correspondência entre as pastas Mac de uma biblioteca e pastas do seu PC** (apenas caminhos de pastas).
- **No sCollectPlay, adicionalmente:** as suas próprias playlists, a lista das pastas, dos ficheiros XML e das
  bibliotecas usados recentemente, a ordenação e o estado do navegador de colunas.
- **Um registo de erros** (`fehler.log`), que fica no seu PC.

Tudo isto é removido quando desinstala a aplicação.

A aplicação só lê ficheiros multimédia e ficheiros XML onde os selecionar; uma biblioteca do sCollect é apenas lida, exceto o ficheiro `rueckmeldungen.json` descrito em «Os seus ficheiros». Não
estabelece ligações de rede próprias, não usa serviços de análise e não apresenta publicidade. Os ficheiros que o
Windows não reproduz sozinho são entregues ao programa predefinido para esse tipo de ficheiro, que escolhe no Windows.

Se exportar no sCollectPlay uma playlist para o VLC ou um dispositivo, a aplicação copia os respetivos ficheiros
para a pasta que escolher.

Só quando apaga expressamente um ficheiro multimédia de pastas analisadas ou de um XML do iTunes é que a aplicação o
coloca na Reciclagem do Windows; numa unidade sem Reciclagem, por exemplo na rede, é apagado definitivamente após
confirmação. Uma biblioteca do sCollect não é alterada com isso.

## Microsoft Store

No Windows, a compra (sCollectPlay), a transferência e as atualizações são feitas através da Microsoft Store; aplica-se
a declaração de privacidade da Microsoft. O sCollectPlay Lite é gratuito e menciona a versão completa.

## Sem transmissão, sem análise

Não há publicidade, não há serviços de análise, não há relatórios de falha para terceiros e
não há contas.

## Contacto

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
