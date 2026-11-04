# Comanda – versão para celular (teste)

Esta pasta é um aplicativo web instalável (PWA). Ele funciona no navegador do celular e pode ser
colocado na tela inicial como se fosse um app.

## Como colocar no ar
1. Envie **toda esta pasta** para um serviço gratuito de hospedagem de sites estáticos
   (por exemplo Netlify, Cloudflare Pages ou GitHub Pages). O endereço precisa ser **https**,
   senão o GPS, a instalação e o modo offline não funcionam.
2. Abra o endereço gerado no celular.

## Como instalar no celular
- **Android (Chrome):** menu ⋮ → "Instalar app" ou "Adicionar à tela inicial".
- **iPhone (Safari):** botão Compartilhar → "Adicionar à Tela de Início".

## O que testar
- Explorar: GPS ("Localização atual"), estado e cidade, busca, ordenação e mapa (abre Google Maps ou Waze).
- Minhas Avaliações: meia estrela, até 5 fotos, editar, excluir, favoritar e compartilhar o cartão.
- Quero Conhecer: adicionar local novo (pede cozinha, estado e cidade), horário e mapa.
- Perfil: foto, privacidade, preferências e conquistas.

## Limites desta versão de teste
- Os dados ficam **só no aparelho** (armazenamento do navegador). Não há conta, nem sincronização
  entre aparelhos, e limpar os dados do navegador apaga as avaliações.
- Restaurantes, horários, endereços e notas base são de exemplo.
- Para atualizar o app, substitua o `index.html` na hospedagem. O app busca a versão nova quando há internet.
