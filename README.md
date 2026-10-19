# Cobrinhas do Jardim 🐛🌼

Um jogo infantil de cobrinhas com frutas, cores suaves e um editor para criar personagens à tua maneira.

**[Jogar online](https://master-devs171.github.io/cobrinhas-do-jardim/)**

## Como jogar

- Come a comida do chão para crescer.
- Faz as adversárias do computador baterem no teu corpo e apanha os pontos que deixam.
- A cabeça tocar na borda elimina a cobra e termina a tua partida.
- Usa as setas/WASD, rato, arrasta no ecrã ou joystick. Espaço ou ⚡ acelera.
- Abre 🎨 para escolher cores, padrões, olhos, bocas, acessórios, bandeiras e rastos.

Arena 4800 × 4800, quatro zonas, 12 adversárias e 1000 peças de comida. Sem multiplayer online, publicidade ou rastreadores.

## Executar e testar

Abre index.html no navegador. Não precisa de instalação nem dependências remotas.

```sh
npm test
```

O teste de UI usa DOM/canvas simulados. A verificação visual e de toque num telemóvel real está pendente.

## Contribuição para DinoPlay

Preparado para [Rjcferreira/dino-color-quiz](https://github.com/Rjcferreira/dino-color-quiz), usando o runtime sandbox e o SDK autorizado na versão integrada. Esta edição autónoma guarda apenas progresso do jogo, visual e recorde no armazenamento local do navegador. Na versão integrada, usa exclusivamente o SDK DinoPlay para esses dados.

## Licença

MIT para o código e as ilustrações SVG deste jogo. Emojis apresentados pela fonte do sistema.

## Versão 1.4.0

Movimento interpolado, segmentos do corpo em cache, desenho limitado à área visível e arena sem redesenho contínuo nos menus. Editor dividido em Corpo, Cara, Magia e Bandeira; menus adaptados a PC e telemóvel, pausa compacta e classificação recolhível.

Verificado no navegador em 320 × 568, 390 × 844, 844 × 390 e PC. Testes de regras e interface simulada passaram. Toque físico e modo avião continuam pendentes.

## Aventuras e recompensas (1.5.0)

Oito tarefas finitas e sem prazo, estrelas, níveis, álbum de autocolantes e quatro skins especiais. As recompensas são fixas e só podem ser recebidas uma vez. Não existem sequências diárias, contagens decrescentes, compras, roletas ou sorteios. O editor base continua disponível.

As tarefas contam fruta recolhida, zonas exploradas e padrões guardados na oficina. O progresso é preservado entre partidas.

Teste adicional: node scripts/test-cobrinhas-progress.cjs (na versão autónoma, node test-cobrinhas-progress.cjs).
