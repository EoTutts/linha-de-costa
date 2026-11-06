# Linha de Costa

Corrida arcade acessível pelo litoral, com pista de dois quilômetros, três voltas, cinco rivais, treino e orientação sonora.

Este é o repositório de distribuição dos pacotes preparados no projeto R36S. A versão interna do jogo é **0.1.1**; a release de distribuição é de 06/11/2026.

## Baixar

[Pacote R36S ARM64](https://github.com/EoTutts/linha-de-costa/releases/download/v0.1.1-distribution.20261106/linha-de-costa-linux-arm64.zip) · [Release e SHA-256](https://github.com/EoTutts/linha-de-costa/releases/tag/v0.1.1-distribution.20261106)

## Requisitos e estado

Luma/ArkOS em R36S **RK3326, Linux ARM64**, com as bibliotecas de áudio e vídeo da plataforma. O pacote usa o runtime .NET 10 compartilhado do Luma. Não é um pacote para GA36/ARMv7. Distribuição experimental. O pacote foi compilado para Linux ARM64; a validação física desta revisão no console permanece pendente.

## Instalar ou atualizar

Extraia o ZIP inteiro e copie a pasta `linha-de-costa` para `a11y/games/` na partição EASYROMS do cartão. O `game.json` deve ficar diretamente dentro dessa pasta. Com Luma ligado, a lista reconhece o jogo automaticamente. Também é possível enviar o ZIP pela opção Instalar jogo da Página no PC do Luma. Feche o jogo antes de atualizar; preserve a pasta `a11y/saves/`.

## Controles

B acelera; A freia; direcional ou analógico dirige; X buzina; Start pausa; Select consulta o estado e repete a orientação. Fn, Power e volume continuam reservados ao sistema.

## Arquivos e salvamentos

O pacote foi conferido quanto ao manifesto, executável e SHA-256. Não acompanha salvamentos, preferências pessoais ou registros de testes. Os saves ficam na pasta de dados atribuída pelo Luma, normalmente `a11y/saves/linha-de-costa/`. Esta publicação não representa uma nova campanha completa ou teste físico.

## Créditos e licenças

Consulte CREDITOS.md, ASSETS-SHA256.txt e os avisos das bibliotecas no pacote. Os avisos de terceiros presentes no pacote devem ser mantidos. Não se atribui uma licença única a todo o conteúdo.
