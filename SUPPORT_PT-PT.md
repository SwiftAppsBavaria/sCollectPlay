# Ajuda do sCollectPlay e do sCollectPlay Lite

## O que a aplicação faz

O sCollectPlay reproduz música, audiolivros, podcasts, filmes e e-books diretamente das suas
pastas, de um XML do iTunes ou do Apple Music ou de uma biblioteca do sCollect. Não copia
nada, não importa nada e não escreve nada nos seus ficheiros.

## Primeiros passos

Escolha no arranque uma das três fontes — ou mais tarde através do menu **Ficheiro**:

1. **Analisar pasta…** — uma pasta qualquer, com as respetivas subpastas.
2. **Abrir biblioteca XML…** — um ficheiro XML exportado do Apple Music. Cria-o no Apple
   Music em **Ficheiro → Biblioteca → Exportar biblioteca**.
3. **Selecionar biblioteca do sCollect…** (⇧⌘O) — a pasta principal de uma biblioteca criada
   com o sCollect.

A barra de título da janela indica depois o que está carregado, por exemplo Pasta «Música»;
ao apontar para o título, aparece o caminho completo.

## Perguntas frequentes

**Porque é que os tipos de multimédia se chamam «até 10 min» ou «30–60 min»?**
Ao analisar uma pasta, a aplicação não sabe se um ficheiro é uma canção, um audiolivro ou um
podcast — isso não está escrito em pasta nenhuma. Por isso divide o áudio e o vídeo pela
duração. Com um XML ou uma biblioteca do sCollect surgem os tipos reais, ou seja, Música,
Audiolivro, Longa-metragem e assim por diante.

**A aplicação pede uma pasta que já escolhi antes.**
O macOS só permite que uma aplicação aceda às pastas que lhe entrega expressamente. Se os
ficheiros de um XML ou as pastas multimédia de uma biblioteca estiverem fora da pasta
escolhida, a aplicação pede uma vez cada uma dessas pastas e guarda a autorização.

**Uma faixa indica «Ficheiro ilegível».**
Falta à aplicação a autorização para a pasta onde o ficheiro se encontra — ou o disco não
está ligado. Em **Definições → Geral → Pasta multimédia** vê quais as pastas autorizadas e
pode, com **Selecionar**, conceder uma autorização em falta.

**Um filme abre-se noutro programa.**
Os formatos que o macOS não reproduz por si — por exemplo MKV, AVI ou DivX — a aplicação
passa-os a outro leitor. Qual, define-o em **Definições → Reprodução/Playlist → Leitor
externo para codecs não suportados**; o VLC e o IINA são reconhecidos se estiverem
instalados.

**No arranque, a aplicação pergunta se deve carregar uma fonte numa unidade de rede.**
Uma unidade de rede inacessível poderia atrasar muito o arranque. A pergunta pode ser
desativada com **Não voltar a perguntar** e reativada em **Definições → Geral**.

**Posso editar tags ou as indicações das faixas?**
Não. O sCollectPlay é um leitor e não altera metadados.

**Como levo uma seleção para o Apple Music?**
Através do menu de contexto **Enviar como playlist para o Apple Music** ou de **Ficheiro →
Enviar playlist para o Apple Music…**. Da primeira vez, o macOS pergunta se a aplicação pode
controlar o Apple Music.

**O que faz o sCollectPlay que a edição Lite não faz?**
O sCollectPlay oferece adicionalmente o navegador de colunas, a escolha das colunas visíveis, playlists próprias e
inteligentes, a junção de várias pastas, as listas das fontes usadas recentemente e a
reposição da última fonte no arranque. O sCollectPlay Lite reproduz uma fonte por sessão.

**Posso desfazer uma eliminação?**
Sim, com ⌘Z, enquanto o ficheiro ainda estiver no Lixo. Em unidades sem Lixo, a aplicação
pergunta antes se deve apagar definitivamente — isso não pode ser desfeito.

## Contacto

SwiftAppsBavaria · SwiftAppsBavaria@gmx.net
