# nlw-esports-aula-01
Repositório para estudo seguindo os aprendizados do evento NLW-Esports by Rocketseat.

Construindo uma aplicação web com Node usando typeScript. Usando o https://hoppscotch.io/pt-br/ para facilitar o uso das rotas. Utilizando também o https://www.prisma.io/ como ORM não esquecendo de instalar a biblioteca cors para poder permitir o acesso as rotas back-end por fronts diversos

Construindo o front-end com React. Usando o https://vitejs.dev/ para facilitar a constução do front. Na estilização usou-se o https://tailwindcss.com/ e  https://phosphoricons.com/

Construindo o app mobile com ReactNative. Ferramenta https://docs.expo.dev/ para rodar app já no smartphone. 

------

# Back-end

## Entidades

### Games

id
title
bannerUrl

### Ad

id
gameId
name
yearsPlaying
discord
weekDays
hourStart
hourEnd
useVoiceChannel
createdAt

## Caso de Uso

- Listagem de games com contagem de anúncios
- Criação de novo anúncio
- Listagem de anúncios por Game
- Buscar discord pelo ID do anúncio