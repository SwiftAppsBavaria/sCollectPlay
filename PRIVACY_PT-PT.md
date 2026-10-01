# Política de privacidade do sCollectPlay e do sCollectPlay Lite

Atualizado a: 2026-10-01

## Em resumo

O sCollectPlay e o sCollectPlay Lite **não** recolhem, não guardam e não transmitem dados
pessoais. As aplicações trabalham exclusivamente no seu Mac. Não há contas, não há ligação à
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

Só quando apaga expressamente um ficheiro é que a aplicação o coloca no Lixo do macOS e o
retira da lista; se provier de uma biblioteca do sCollect, o respetivo catálogo também é
ajustado em conformidade. Em unidades sem Lixo, a aplicação pergunta antes se o ficheiro
deve ser apagado definitivamente.

## Sem transmissão, sem análise

Não há publicidade, não há serviços de análise, não há relatórios de falha para terceiros e
não há contas.

## Contacto

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
